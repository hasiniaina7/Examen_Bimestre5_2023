<script>
    import { Card, GradientButton, Span, Heading } from "flowbite-svelte";
</script>

<div id="produits" class=" my-6 container text-gray-800 dark:text-gray-400">
    <div class="nos-produits shadow-2xl">
        <Heading
            tag="h1"
            class="text-4xl sm:text-6xl text-blue-600 dark:text-gray-400"
            >Nos produits</Heading
        >
        <Card padding="none" size="xl" class="grid md:grid-cols-2">
            <div
                class="flex flex-col justify-center items-center p-8 text-center bg-white rounded-t-lg border-b border-gray-200 md:rounded-t-none md:rounded-tl-lg md:border-e dark:bg-gray-800 dark:border-gray-700"
            >
                <img src="./images/pompist.png" alt="" />
                <GradientButton class="w-full " color="pinkToOrange"
                    >Carburant premium</GradientButton
                >
                <div
                    class="flex justify-center items-center space-x-3 rtl:space-x-reverse"
                >
                    <div
                        class="space-y-0.5 font-medium dark:text-white text-left"
                    >
                        <div class="text-blue-500 pt-4">
                            Les Produit Blanc:
                            <span
                                class="text-sm font-light text-gray-500 dark:text-gray-400"
                            >
                                Super sans plomb 95, gasoil, pétrole lampant
                            </span>
                        </div>
                        <div class="text-blue-500">
                            Les Produit Noir:
                            <span
                                class="text-sm font-light text-gray-500 dark:text-gray-400"
                            >
                                Fuel oil Pour toute information complémentaire,
                            </span>
                            <span
                                class="text-sm contact-flex text-center font-light text-gray-500 dark:text-gray-400"
                            >
                                <br />Merci de contacter <br />
                                Le département réseau <br />
                                + 261 34 07 202 15
                                <br />e-mail : dpt.reseau@jovena.mg
                            </span>
                        </div>
                    </div>
                </div>
            </div>
            <div
                class="flex flex-col justify-center items-center p-8 text-center bg-white rounded-t-lg border-b border-gray-200 md:rounded-t-none md:rounded-tl-lg md:border-e dark:bg-gray-800 dark:border-gray-700"
            >
                <img src="./images/bidon.jpg" alt="" />
                <GradientButton class="w-full " color="pinkToOrange"
                    >Lubrifiant</GradientButton
                >
                <div
                    class="flex justify-center items-center space-x-3 rtl:space-x-reverse"
                >
                    <div
                        class="space-y-0.5 font-medium dark:text-white text-left"
                    >
                        <div class="text-blue-500">
                            <Span gradient>
                                LA PLUS GRANDE GAMME DE LUBRIFIANTS "AU MEILLEUR
                                PRIX"</Span
                            >
                        </div>
                        <div class="text-blue-500">
                            <span
                                class="text-sm font-light text-gray-500 dark:text-gray-400"
                            >
                                Distributeur exclusif de la marque Caltex
                                Chevron Texaco oil et de sa propre marque de
                                lubrifiant Jovena Pour toute information
                                complémentaire,
                            </span>
                            <span
                                class="text-sm contact-flex text-center font-light text-gray-500 dark:text-gray-400"
                            >
                                <br />Merci de contacter <br />
                                Le département réseau <br />
                                + 261 34 07 202 15
                                <br />e-mail : dpt.reseau@jovena.mg
                            </span>
                        </div>
                    </div>
                </div>
            </div>
            <div
                class="flex flex-col justify-center items-center p-8 text-center bg-white rounded-t-lg border-b border-gray-200 md:rounded-t-none md:rounded-tl-lg md:border-e dark:bg-gray-800 dark:border-gray-700"
            >
                <img src="./images/boutique.jpg" alt="" />
                <GradientButton class="w-full " color="pinkToOrange"
                    >Boutique</GradientButton
                >
                <div
                    class="flex justify-center items-center space-x-3 rtl:space-x-reverse"
                >
                    <div
                        class="space-y-0.5 font-medium dark:text-white text-left"
                    >
                        <div class="pt-4">
                            Plus de 80% des stations-service ont une boutique.
                            La surface cumulée de ces boutiques représente plus
                            de 5000m2, soit l’équivalent de deux hypermarchés.
                            Les consommateurs peuvent trouver une large gamme de
                            produits alimentaires et non-alimentaires.
                            Généralement bien situées, les boutiques Jovena
                            constituent de véritables commerces de proximité qui
                            répondent parfaitement aux attentes des clients.
                        </div>
                    </div>
                </div>
            </div>
            <div
                class="flex flex-col justify-center items-center p-8 text-center bg-white rounded-t-lg border-b border-gray-200 md:rounded-t-none md:rounded-tl-lg md:border-e dark:bg-gray-800 dark:border-gray-700"
            >
                <img src="./images/SD.png" alt="" />
                <GradientButton class="w-full " color="pinkToOrange"
                    >Services diversifiés</GradientButton
                >
                <div
                    class="flex justify-center items-center space-x-3 rtl:space-x-reverse"
                >
                    <div
                        class="space-y-0.5 font-medium dark:text-white text-left"
                    >
                        <div class="pt-4">
                            Jovena offre à ses clients, particuliers,
                            entreprises et administrations une large gamme de
                            produits et services adaptés en stations-service.
                            Pour satisfaire au mieux les besoins de ses clients,
                            Jovena propose en plus des services à la pompe, une
                            large gamme de lubrifiants, de pneumatiques, de
                            lavage et de services d’entretien. Ces derniers sont
                            assurés avec des matériels et équipements aux normes
                            professionnelles.
                        </div>
                    </div>
                </div>
            </div>
        </Card>
    </div>
</div>

<style>
    .contact-flex {
        display: flex;
        flex-direction: column;
    }
    img {
        margin-bottom: 20px;
    }
</style>
