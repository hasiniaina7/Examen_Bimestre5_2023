<script>
    // @ts-nocheck

    import { Carousel } from "flowbite-svelte";
    // ./imageData/+server.js has the following
    export const images = [
        {
            alt: "Payer avec VISA (TPE)",
            src: "/images/visa.jpg",
            title: "Jovena",
        },
        {
            alt: "Jovena Manakara",
            src: "/images/Jovena1.jpg",
            title: "Jovena",
        },
        {
            alt: "Jovena Manakara",
            src: "/images/Jovena.gif",
            title: "Jovena",
        },
    ];
</script>

<div class="max-w-4xl">
    <Carousel {images} duration="3000" />
</div>
