<script lang="ts">
	
    import ThemeSwitch from "$lib/components/ThemeSwitch.svelte";
    import Theme from "$lib/components/ThemeSwitch.svelte";
    import Button from "$lib/components/ui/button/button.svelte";
 
</script>
<div class="bg-background flex justify-end pb-[35rem] lg:pb-0">
    <div class="bg-secondary lg:min-h-[calc(100vh)] w-full  lg:w-[60vw] min-h-[40vw] relative flex justify-center items-center pb-32">
        <div class="bg-background shadow-2xl h-[30rem] w-[20rem] absolute  lg:start-10  lg:-translate-x-full lg:translate-y-2/4 flex  flex-col items-center p-4 gap-4 rounded-3xl self-start translate-y-[117%] ">
<img src="https://upload.wikimedia.org/wikipedia/commons/b/bc/Unknown_person.jpg" class="rounded-full w-64 h-64  grayscale" alt="صورة شخصية">
<div class="flex flex-col items-center gap-4">
    <h1 class="font-bold text-2xl">
        Abdul Rahman Al-Harbi
       </h1>
       
       <hr class="w-32 border-primary border-2  " />
       <h2 class="text-2xl">
        Se Student
       </h2>
</div>
<div class="bg-background flex gap-3 ">
    <Button variant="ghost"><svg xmlns="http://www.w3.org/2000/svg" width="1em" height="1em" viewBox="0 0 24 24"><path fill="currentColor" fill-rule="evenodd" d="M9.429 8.969h3.714v1.85c.535-1.064 1.907-2.02 3.968-2.02c3.951 0 4.889 2.118 4.889 6.004V22h-4v-6.312c0-2.213-.535-3.461-1.897-3.461c-1.889 0-2.674 1.345-2.674 3.46V22h-4zM2.57 21.83h4V8.799h-4zM7.143 4.55a2.53 2.53 0 0 1-.753 1.802a2.57 2.57 0 0 1-1.82.748a2.6 2.6 0 0 1-1.818-.747A2.55 2.55 0 0 1 2 4.55c0-.677.27-1.325.753-1.803A2.58 2.58 0 0 1 4.571 2c.682 0 1.336.269 1.819.747s.753 1.126.753 1.803" clip-rule="evenodd"/></svg></Button>
    <Button variant="ghost"><svg xmlns="http://www.w3.org/2000/svg" width="1em" height="1em" viewBox="0 0 16 16"><path fill="currentColor" d="M12.6.75h2.454l-5.36 6.142L16 15.25h-4.937l-3.867-5.07l-4.425 5.07H.316l5.733-6.57L0 .75h5.063l3.495 4.633L12.601.75Zm-.86 13.028h1.36L4.323 2.145H2.865z"/></svg></Button>
    <Button variant="ghost"><svg xmlns="http://www.w3.org/2000/svg" width="1em" height="1em" viewBox="0 0 24 24"><path fill="currentColor" d="M15.12 5.32H17V2.14A26 26 0 0 0 14.26 2c-2.72 0-4.58 1.66-4.58 4.7v2.62H6.61v3.56h3.07V22h3.68v-9.12h3.06l.46-3.56h-3.52V7.05c0-1.05.28-1.73 1.76-1.73"/></svg></Button>
    <Button variant="ghost"><svg xmlns="http://www.w3.org/2000/svg" width="1em" height="1em" viewBox="0 0 24 24"><g fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2"><rect width="20" height="20" x="2" y="2" rx="5" ry="5"/><path d="M16 11.37A4 4 0 1 1 12.63 8A4 4 0 0 1 16 11.37m1.5-4.87h.01"/></g></svg></Button>

</div>
</div>
<div class="ms-3 text-secondary-foreground  max-w-[30rem] flex flex-col gap-8">
    <h1 class=" text-8xl font-bold">HELLO</h1>
    <h4 class=" text-4xl">
        Here's who I am & what I do
    </h4>
    <div class="text-secondary-foreground  flex gap-2">
        <Button variant='outline' class='hover:bg-blue-500 w-32 rounded-full' href="/resume">
            RESUME
        </Button>
        <Button  variant='outline' class=" hover:bg-blue-500 w-32 rounded-full " href="/project">PROJECT</Button>
        
    </div>
    <div class="text-secondary-foreground">
        <p class="text-xl">
            A Software Engineering student at Umm Al-Qura University.        </p>
       
    </div>
</div>


    </div>
    
</div>

