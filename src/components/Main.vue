<template>
    <main class="container">
        <section class="content">
            <h1>Escutar muda tudo</h1>
            <p>Milhões de músicas e podcasts para explorar. E nem precisa de cartão de crédito.</p>
        </section>
        <div>
            <button>Baixe o spotify free</button>
        </div>
    </main>
</template>

<script>
export default {
    data() {
        return {
            outline: false
        }
    },
    methods: {
        activeButton() {
            this.outline = !this.outline
        }
    }

}
</script>

<style scoped>
    .container {
        background: #2941AB no-repeat;
        background-image: url("https://www-growth.scdn.co/static/home/bursts.svg");
        background-size: 175%;
        background-position: 46% 5%;
        padding-top: 80px;
        height: 100vh;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }

    .content {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        gap: 32px;
        margin-bottom: 48px;
    }

    .content h1 {
        font-size: 7.5rem;
        font-weight: 800;
        color: #25CB60;
    }

    .content p {
        color: #1ECB87;
        font-size: 1rem;
        font-weight: 600;
    }
    
    .container div button {
        padding: 16px 32px;
        border: none;
        border-radius: 50px;
        color: #2941AB;
        font-size: 0.8rem;
        font-weight: 700;
        text-transform: uppercase;
        background: #25CB60;
        cursor: pointer;
        transition: .2s;
        outline: none;
    }

    .container div button:hover {
        transform: scale(1.05);
    }
</style>