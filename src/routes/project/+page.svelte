<script lang="ts">
     // @ts-ignore
     import P2 from "$lib/components/paragraph2.svelte";
    import { Button } from '$lib/components/ui/button/index.js';
</script>
<div class="max-w-screen-lg mx-auto pt-16 flex flex-col gap-16 ">
    <h1 class="mx-auto w-fit text-5xl font-bold flex items-center  ">
        <div class="bg-blue-500 w-5 h-5 me-4"></div>
        <span>Project</span>
        </h1>

    <P2 title='calculator' subtitle=''> 
  <ul class="flex flex-col gap-4 list-disc">
<p class="text-xl">
  A simple, beautiful, and wonderful calculator.
</p>
  <Button href="https://endearing-boba-038d8d.netlify.app/" variant='ghost' class='w-32 h-32 rounded-full text-xl'>Click here</Button>

  </ul>
    </P2>
    </div >