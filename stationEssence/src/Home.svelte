<script>
    import Carroussel from "./lib/Carroussel.svelte";
    import { cascade, concurrent, loop } from "svelte-typewriter";
    import { fade } from "svelte/transition";
    import IntersectionObserver from "svelte-intersection-observer";
    import Modal from "./lib/Modal.svelte";
    import { Span } from "flowbite-svelte";
    let element;
    let intersecting;
</script>

<header class:intersecting>
    {intersecting ? "" : ""}
</header>
<div class="container mx-auto">
    <div
        class="introduction text-3xl font-extrabold md:text-5xl lg:text-6xl text-center bg-gradient-to-r from-purple-500 to-pink-500 bg-clip-text text-transparent"
    >
        JOVENA est une <Span gradient>Source d'Energie</Span>
    </div>
    <div class="md:grid gap-2 grid-cols-4 justify-center">
        <div
            use:cascade={{ interval: 50, delay: 0, cursor: true }}
            class=" rounded-lg shadow-md home-text station col-span-1 text-center text-gray-300"
        >
            <!-- We will use it latter use:cascade={{ interval: 50, delay: 0, cursor: true }} -->
            <p>De nouveaux services,</p>
            <p>De nouveaux métiers,</p>
            <p>De nouvelles couleurs.</p>
            <p>Des nouvelles stations</p>
        </div>
        <div class=" col-span-2">
            <Carroussel />
        </div>
        <!-- Use it latter use:concurrent={{ interval: 50 }} -->
        <div
            use:cascade={{ interval: 50, delay: 2000 }}
            class=" rounded-lg shadow-md home-text jovena col-span-1 text-center text-gray-300"
        >
            Jovena se transforme et diversifie ses activités. En plus d’être un
            distributeur de carburants et de lubrifiants, Jovena vise à être un
            acteur incontournable dans le domaine de l’énergie à Madagascar.
        </div>
    </div>

    <IntersectionObserver {element} bind:intersecting>
        <div bind:this={element}>
            {#if intersecting}
                <div
                    transition:fade={{ delay: 4000, duration: 600 }}
                    class="text-center mt-4"
                >
                    Bienvenue sur la page web de Jovena Fianarantsoa
                </div>
            {/if}
        </div>
    </IntersectionObserver>
    <div class="flex justify-center modal-btn">
        <Modal />
    </div>
</div>

<style>
    .home-text {
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        min-height: 200px;
        background: url(./back.jpg) no-repeat center;
        background-size: cover;
    }
    .modal-btn {
        margin-top: 30px;
    }
    .introduction {
        margin-bottom: 20px;
    }
</style>
