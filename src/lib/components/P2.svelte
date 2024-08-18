<script lang='ts'>

    export let title : String;
    export let subtitle : String;
</script>


<div class="bg-secondary py-16 ps-0  p-8  rounded-xl  shadow-xl flex justify-between flex-col sm:flex-row ">
   

    
<div class="flex flex-col gap-8">
    <div class="">
        <span class=" font-bold text-2xl border-s-8 border-primary ps-8">
            {title}
        </span>
        <span>
            {subtitle}
        </span>
    </div>
    <div class="ps-10 ">
    <slot />
    </div>
</div>
<img src="/calc.jpg" alt="" class="w-auto sm:w-64 ">
</div>
