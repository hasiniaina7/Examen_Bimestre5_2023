<script>
    import Navbar from "./Navbar.svelte";
    import { DarkMode, Footer } from "flowbite-svelte";
    import Home from "./Home.svelte";
    import Presentation from "./Presentation.svelte";
    import Produits from "./Produits.svelte";
    import Maps from "./Maps.svelte";
    import Contact from "./Contact.svelte";
    import MyFooter from "./MyFooter.svelte";
</script>

<Navbar />
<DarkMode class="relative" />
<Home />
<Presentation />
<Produits />
<Maps />
<Contact />
<MyFooter />
