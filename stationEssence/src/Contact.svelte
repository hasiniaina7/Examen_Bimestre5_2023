<script>
    import {
        Label,
        Input,
        Select,
        Textarea,
        GradientButton,
        Heading,
    } from "flowbite-svelte";
    let selectedRegion;
    let textareaprops = {
        id: "message",
        name: "message",
        label: "Votre Messages:",
        rows: 4,
        placeholder: "Ecrir ici...",
    };
    let regions = [
        { value: "an", name: "Analamanga" },
        { value: "vk", name: "Vakinankaratra" },
        { value: "bg", name: "Bongolava" },
        { value: "it", name: "Itasy" },
        { value: "hm", name: "Haute Matsiatra" },
        { value: "am", name: "Amoron'i Mania" },
        { value: "vf", name: "Vatovavy-Fitovinany" },
        { value: "aa", name: "Atsimo-Atsinanana" },
        { value: "ih", name: "Ihorombe" },
        { value: "me", name: "Menabe" },
        { value: "aa2", name: "Atsimo-Andrefana" },
        { value: "ad", name: "Androy" },
        { value: "an2", name: "Anosy" },
        { value: "al", name: "Alaotra-Mangoro" },
        { value: "aj", name: "Analanjirofo" },
        { value: "at", name: "Atsinanana" },
        { value: "bo", name: "Boeny" },
        { value: "bi", name: "Betsiboka" },
        { value: "me2", name: "Melaky" },
        { value: "bg2", name: "Bongolava" },
        { value: "di", name: "Diana" },
        { value: "sa", name: "Sava" },
        { value: "aj2", name: "Analanjirofo" },
    ];
</script>

<div id="contact" class="container my-7 lg:max-w-lg">
    <div>
        <Heading tag="h3">Pour Nous contacter:</Heading><span
            class="text-blue-500">Veuillez remplir la formulaire</span
        >
    </div>
    <div class="mb-6">
        <Label type="mail" for="mail" class="block mb-2"
            >Entrer votre E-Mail:*</Label
        >
        <Input
            id="large-input"
            size="lg"
            placeholder="E-Mail:exemple@exemple.com"
        />
    </div>
    <div class="mb-6">
        <Label type="name" for="name" class="block mb-2"
            >Entrer votre Nom:*</Label
        >
        <Input id="large-input" size="lg" placeholder="Kotozafy" />
    </div>
    <div class="mb-6">
        <Label type="last-name" for="last-name" class="block mb-2"
            >Entrer votre Prenom:*</Label
        >
        <Input id="large-input" size="lg" placeholder="Alexis" />
    </div>
    <div class="mb-6">
        <Label type="phone-number" for="phone-number" class="block mb-2"
            >Telephone:</Label
        >
        <Input id="large-input" size="lg" placeholder="(261 )" />
    </div>

    <div class="mb-6">
        <Label type="region" for="region" class="block mb-2">
            Sélectionnez votre région:*
            <Select class="mt-2" items={regions} bind:value={selectedRegion} />
        </Label>
    </div>

    <Textarea {...textareaprops} />
    <div class="text-center">
        <GradientButton class="" color="purpleToPink">Envoyer</GradientButton>
    </div>
</div>
