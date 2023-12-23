<script>
    import { Button, Modal } from "flowbite-svelte";
    import { Span } from "flowbite-svelte";
    let defaultModal = false;
</script>

<Button on:click={() => (defaultModal = true)}>A lire avant de commencer</Button
>
<Modal title="Note de presentation" bind:open={defaultModal} autoclose>
    <p class="text-base leading-relaxed text-gray-500 dark:text-gray-400">
        Je suis <Span>LOVANIRINA Hasiniaina Christian</Span>
        Ce projet est un projet d'examen en Technologie Web, le code source sera
        sur GithHub en mode publique, du coup je vous invite à le consulter
        <a href="https://github.com/hasiniaina7/Examen_Bimestre5_2023"
            >GithHub ici</a
        >
    </p>

    <div class="container mx-auto my-8">
        <h1 class="text-3xl font-bold mb-4">Station Essence</h1>

        <h2 class="text-2xl font-bold mb-4">Svelte + Vite</h2>
        <p>
            Ce projet est disponible grâce à Vite et Javascript, avec le
            framework Svelte.
        </p>

        <p>
            "Vite (French word for 'quick', pronounced /vit/, like 'veet') is a
            build tool that aims to provide a faster and leaner development
            experience for modern web projects." Vous pouvez le trouver sur: <a
                href="https://vitejs.dev/guide/">Vite Website</a
            >
        </p>

        <p>
            Svelte est le framework le plus admiré par la communauté de
            StackOverflow. Moi aussi, après avoir parcouru quelques frameworks
            JS pendant mes études précédentes à l'EMIT Fianarantsoa, je trouve
            que Svelte fait partie des meilleurs.
        </p>

        <p>
            "We're proud that Svelte was recently voted the most admired JS web
            framework in one industry survey while drawing the most interest in
            learning it in two others. We think you'll love it too."
            <a href="https://svelte.dev/">Svelte</a>
        </p>

        <h2 class="text-2xl font-bold mb-4">Flowbite Svelte</h2>
        <p>
            On dit toujours de ne pas réinventer les roues, moi j'ai déjà fait
            du développement web depuis 2021, je trouve qu'il vaut mieux
            utiliser des librairies personnalisables pour ne pas dépenser
            beaucoup de temps à coder/re-coder des fonctionnalités Javascript.
        </p>

        <p><strong>Pourquoi Flowbite?</strong></p>
        <p>
            "Flowbite Svelte is a free and open-source UI component library
            based on the core Flowbite components and built with native Svelte
            components and interactivity handling.
        </p>

        <p>
            This library features hundreds of interactive elements such as
            navbars, dropdowns, modals, and sidebars all handled by Svelte and
            based on the utility classes from Tailwind CSS."
            <a href="https://flowbite-svelte.com/docs/pages/introduction"
                >Flowbite Svelte</a
            >
        </p>

        <h2 class="text-2xl font-bold mb-4">TailwindCSS</h2>
        <p>
            Avant j'ai utilisé Bootstrap comme framework CSS. Mais je trouve que
            TailwindCSS fait mieux que lui, il est aussi facile à installer avec <a
                href="http://npmjs.com/">NPM</a
            >.
        </p>

        <p>
            "Rapidly build modern websites without ever leaving your HTML. A
            utility-first CSS framework packed with classes like flex, pt-4,
            text-center and rotate-90 that can be composed to build any design,
            directly in your markup."
            <a href="https://tailwindcss.com/">TailwindCSS</a>
        </p>

        <h2 class="text-2xl font-bold mb-4">Copyright</h2>
        <p>
            Tous les copyrights sont entièrement dédiés aux produits cités
            ci-dessus. Ce projet ne serait pas commercialisé et n'est pas
            autorisé à être commercialisé.
        </p>
    </div>
    <svelte:fragment slot="footer">
        <Button on:click={() => alert('Je vous remercie!"')}>Continuer</Button>
    </svelte:fragment>
</Modal>
