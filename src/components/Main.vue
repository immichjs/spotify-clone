<template>
    <main class="container">
        <div class="content">
            <h1>Escutar muda tudo</h1>
            <p>Milhões de músicas e podcasts para explorar. E nem precisa de cartão de crédito.</p>
            <button>Baixe o spotify free</button>
        </div>
    </main>
</template>

<script>
export default {

}
</script>

<style scoped>
    .container {
        background: #2941AB no-repeat;
        background-image: url("https://www-growth.scdn.co/static/home/bursts.svg");
        background-size: 175%;
        background-position: 46% 4%;
        padding-top: 80px;
        height: 100vh;
        display: flex;
        justify-content: center;
    }

    .content {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        gap: 32px;
    }

    .content h1 {
        font-size: 7.5rem;
        font-weight: 800;
        color: #25CB60;
    }

    .content p {
        color: #25CB60;
        font-size: 1.1rem;
        font-weight: 500;
    }

    .content button {
        padding: 16px 32px;
        border: none;
        border-radius: 50px;
        color: #2941AB;
        font-size: 0.8rem;
        font-weight: 700;
        text-transform: uppercase;
        background: #25CB60;
    }
</style>