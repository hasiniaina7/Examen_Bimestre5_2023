<script>
    import { Heading, Span, Alert } from "flowbite-svelte";
</script>

<div id="presentation" class="container text-gray-800 dark:text-gray-400 my-6">
    <div class="qui-somme-nous shadow-2xl">
        <Heading
            tag="h1"
            class="text-4xl sm:text-6xl text-blue-600 dark:text-gray-400"
            >Qui somme nous?</Heading
        >
        <div class="md:grid gap-2 grid-cols-3 justify-center">
            <div class="col-span-1"></div>
            <div class="col-span-2 pt-7">
                <p class="p-5">
                    <img class="w-60 h-14" src="/Logo-Axian.png" alt="" />
                    <Span gradient>Filiale du Groupe Axian,</Span>
                    Jovena Madagascar est le leader dans la distribution des carburants
                    à Madagascar. Fort de ses 105 stations-service, Jovena offre
                    les meilleurs services et un large choix de produits de qualité
                    disponibles dans ses boutiques. Nous avons pour mission de développer
                    de nouvelles solutions adaptées aux besoins de chacun et investissons
                    en permanence dans des projets sur le long terme pour assurer
                    la pérennité de la distribution d’énergie dans tout Madagascar.
                    <a
                        href="https://www.linkedin.com/company/jovenna/?trk=public_profile_experience-item_profile-section-card_image-click&originalSubdomain=fr"
                        class="text-blue-600">Source</a
                    >
                </p>
                <p class="p-5">
                    <img class="w-60 h-15" src="/logo-source.jpg" alt="" />
                    <Span gradient>
                        Jovena se transforme et diversifie ses activités.
                    </Span>
                    En plus d’être un distributeur de carburants et de lubrifiants,
                    Jovena vise à être un acteur incontournable dans le domaine de
                    l’énergie à Madagascar. Ceci en investissant dans de nouvelles
                    stations, mais aussi dans des projets de barrages hydrauliques,
                    des turbines à fuel lourd et des énergies renouvelables.
                    <a href="https://www.jovena.mg/" class="text-blue-600"
                        >Site officiel</a
                    >
                </p>
            </div>
        </div>
        <Alert class="text-center " color="red">
            <span class="font-medium">Copyright alert!</span>
            Ces logos sont soumises aux droits de leur pocesseurs respectifs
        </Alert>
    </div>
</div>

<style>
    .qui-somme-nous {
        display: flex;
        flex-direction: column;
        justify-content: center;
    }
</style>
