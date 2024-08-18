<script lang='ts'>
    export let date : String;
    export let title : String;
    export let company : String;
</script>


<div class="bg-secondary py-16  p-8 rounded-xl items-center shadow-xl flex justify-between gap-16">
    <div class="flex flex-col min-w-32">
        <span class="text-primary font-bold">
      {date}
        
        </span>
        <span class="font-bold">
            {title}
        </span>
        <span>
            {company}
        </span>
    </div>
<div>
<slot />
</div>
</div>