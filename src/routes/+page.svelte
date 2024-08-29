<script>
    import imgIntroducao from "$lib/assets/introducao.jpg";
    import icon from "$lib/assets/introducao.jpg"; 
</script>


<section class="intro" style="background-image: url({imgIntroducao});">
    <div class="intro__wrapper wrap">
        <h1>
            Estilo e performance, monte seu PC e arrebente em seus jogos
        </h1>
        <p>
            Onde você encontra a maior e mais completa linha de produtos para elevar seu nível.
        </p>
        <a class="btn__sobre" href="">sobre</a>
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
