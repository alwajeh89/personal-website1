<script lang="ts">
    import { page } from "$app/stores";
    import Button from "$lib/components/ui/button/button.svelte";
import "../app.css";
import { ModeWatcher } from "mode-watcher";
import * as Sheet from "$lib/components/ui/sheet";
    import ThemeSwitch from "$lib/components/ThemeSwitch.svelte";
    import Footer from "$lib/components/Footer.svelte";

const links=[
{
    text: 'about me',
    href: '/'
},
{
    text: 'resume',
    href: '/resume'
},
{
    text: 'project',
    href: '/project'
},
,

];
let sheetopen: boolean;
</script>
<ModeWatcher />

<nav  class="  max-w-[100dvw] bg-secondary w-[100dvw] h-16  flex justify-between items-baseline  px-4 py-3 ">
<div class="flex gap-2 ">
<div class="w-5 h-5 bg-primary"></div>
    <a href="/" class="text-secondary-foreground text-xl">
        Abdulrahman Al-Harbi
    </a>
</div>


<div class="flex">
    <ThemeSwitch  /> 
    <div class="uppercase flex hidden lg:flex">
       
        {#each links as link}
        <Button class=" {$page.url.pathname == link.href && 'text-primary' }"
        href={link.href} variant='link'>{link.text}</Button>
        
        
        {/each}
        
        </div>

        <Sheet.Root bind:open={sheetopen}>
            <Sheet.Trigger>        <Button variant="ghost" class='lg:hidden text-secondary-foreground'><svg xmlns="http://www.w3.org/2000/svg" width="1em" height="1em" viewBox="0 0 24 24"><path fill="currentColor" d="M3 18h13v-2H3zm0-5h10v-2H3zm0-7v2h13V6zm18 9.59L17.42 12L21 8.41L19.59 7l-5 5l5 5z"/></svg></Button>
            </Sheet.Trigger>
            <Sheet.Content class="flex flex-col gap-4 justify-center">
                {#each links as link}
                <Button class=" text-2xl font-bold {$page.url.pathname == link.href && 'text-primary' }"
                href={link.href} variant='link'
                on:click={() => {
                    sheetopen=false;
                }}
                >{link.text}</Button>
                
                
                {/each}
            </Sheet.Content>
          </Sheet.Root>

    </div>


</nav>
    
<main class="min-h-[100vh]">
    <slot />
</main>
<Footer />
