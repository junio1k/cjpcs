<script>
    import imgIntroducao from "$lib/assets/introducao.jpg";
    import imgmonteseupc from "$lib/assets/monteseupc.jpg"
    import icon from "$lib/assets/introducao.jpg"; 

    export let tittle;
    export let content;
    export let img;
    if (img === "introducao") img = imgIntroducao;
    if(img === "monteSeuPC") img = imgmonteseupc;
    export let href; 
    export let btn; 
</script>


<section class="intro" style="background-image: url({img});">
    <div class="intro__wrapper wrap">
        <h1>
            {tittle}
        </h1>
        <p>
           {content}
        </p>
        {#if href && btn}
        <a class="btn__sobre" href= {href}>{btn}</a>
        {/if}
    </div>
</section>

<style>
    .intro{
        min-height: 360px;
        background-size: cover;
        background-position: center;

        display: grid;
        align-items: center;
        justify-content: start;
        position: relative;
        
    }
    .intro::after {
        content: "";
        position: absolute;
        inset: 0;
        background-color: rgba(0,0,0,0.40);
        
    }

    .intro__wrapper {
    z-index: 1;
    max-width: 600px;
  }

</style>
