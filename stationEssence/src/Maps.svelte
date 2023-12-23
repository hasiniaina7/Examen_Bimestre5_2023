<script>
    // @ts-nocheck

    import { Heading, Span } from "flowbite-svelte";
</script>

<div id="presentation" class="container text-gray-800 dark:text-gray-400 my-6">
    <div class="qui-somme-nous shadow-2xl">
        <Heading
            tag="h1"
            class="text-4xl sm:text-6xl text-blue-600 dark:text-gray-400"
            >Localisation G-Maps</Heading
        >
        <div class="small md:grid gap-2 grid-cols-3 justify-center">
            <div class="py-7 small-localisation-intro">
                Jovena possede 2 station à Fianarantsoa dont une à <Span
                    underline
                    gradient
                >
                    Tsaramandroso
                </Span> sortie RN7 vers Tuléar, et une autre à <Span
                    underline
                    gradient>Talatamaty</Span
                >
                route RN7, entré venant d'Antananarivo
            </div>
            <div class=" shadow-sm sm flex justify-center">
                <iframe
                    src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3713.69679770696!2d47.093560310603536!3d-21.441159487057558!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x21e7b95af742433f%3A0x71dcf48e3171b673!2sJovena!5e0!3m2!1sen!2smg!4v1703345737447!5m2!1sen!2smg"
                    title="Jovena Fianarantsoa"
                    style="border:0; border-radius:40px"
                    allowfullscreen=""
                    loading="lazy"
                    width="360"
                    height="300"
                    referrerpolicy="no-referrer-when-downgrade"
                ></iframe>
            </div>
        </div>
        <div class="medium md:grid gap-2 grid-cols-3 justify-center">
            <div class="col-span-1 localisation-intro">
                Jovena possede 2 station à Fianarantsoa dont une à <Span
                    underline
                    gradient
                >
                    Tsaramandroso
                </Span> sortie RN7 vers Tuléar, et une autre à <Span
                    underline
                    gradient>Talatamaty</Span
                >
                route RN7, entré venant d'Antananarivo
            </div>
            <div class="col-span-2 pt-7 shadow-sm sm flex justify-center">
                <iframe
                    src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3713.69679770696!2d47.093560310603536!3d-21.441159487057558!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x21e7b95af742433f%3A0x71dcf48e3171b673!2sJovena!5e0!3m2!1sen!2smg!4v1703345737447!5m2!1sen!2smg"
                    title="Jovena Fianarantsoa"
                    style="border:0; border-radius:40px"
                    allowfullscreen=""
                    loading="lazy"
                    width="600"
                    height="450"
                    referrerpolicy="no-referrer-when-downgrade"
                ></iframe>
            </div>
        </div>
        <div class="large md:grid gap-2 grid-cols-3 justify-center">
            <div class="col-span-1 localisation-intro">
                Jovena possede 2 station à Fianarantsoa dont une à <Span
                    underline
                    gradient
                >
                    Tsaramandroso
                </Span> sortie RN7 vers Tuléar, et une autre à <Span
                    underline
                    gradient>Talatamaty</Span
                >
                route RN7, entré venant d'Antananarivo
            </div>
            <div class="col-span-2 pt-7 shadow-sm sm">
                <iframe
                    src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3713.69679770696!2d47.093560310603536!3d-21.441159487057558!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x21e7b95af742433f%3A0x71dcf48e3171b673!2sJovena!5e0!3m2!1sen!2smg!4v1703345737447!5m2!1sen!2smg"
                    title="Jovena Fianarantsoa"
                    style="border:0; border-radius:40px"
                    allowfullscreen=""
                    loading="lazy"
                    width="800"
                    height="400"
                    referrerpolicy="no-referrer-when-downgrade"
                ></iframe>
            </div>
        </div>
    </div>
</div>

<style>
    .small-localisation-intro {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }
    .localisation-intro {
        display: flex;
        flex-direction: column;
        justify-content: center;
    }
    @media (max-width: 765px) {
        .small {
            display: block;
        }
        .medium {
            display: none;
        }
        .large {
            display: none;
        }
    }
    /* @media (min-width: 640px) {
        .small {
            display: block;
        }
        .medium {
            display: none;
        }
        .large {
            display: none;
        }
    } */
    @media (min-width: 768px) {
        .small {
            display: none;
        }
        .medium {
            display: grid;
        }
        .large {
            display: none;
        }
    }
    @media (min-width: 1024px) {
        .small {
            display: none;
        }
        .medium {
            display: none;
        }
        .large {
            display: grid;
        }
    }
</style>
