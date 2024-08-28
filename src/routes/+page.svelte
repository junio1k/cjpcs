<script>
    import imgIntroducao from "../assets/introducao.jpg"
</script>


<section class="intro" style="background-image: url({imgIntroducao});">
    <div class="intro__wrapper wrap">
        <h1>
            Estilo e performance, monte seu PC e arrebente em seus jogos
        </h1>
        <p>
            Onde você encontra a maior e mais completa linha de produtos para elevar seu nível.
        </p>
        <a class="" href="">sobre</a>
    </div>
</section>

<style>
    .intro{
        min-height: 360px;
        background-size: cover;
        background-position: center;

        display: grid;
        align-items: center;
        position: relative;
    }
    .intro::after {
        content: "";
        position: absolute;
        inset: 0;
        background-color: rgba(0,0,0,0.40);
    }

    .wrap {
    z-index: 1;
    display: grid;
    align-items: center;
    justify-content: start;
  }
</style>
