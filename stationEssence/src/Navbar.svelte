<script>
    import {
        Navbar,
        NavBrand,
        NavLi,
        NavUl,
        NavHamburger,
    } from "flowbite-svelte";
</script>

<Navbar class="my-navbar">
    <NavBrand href="/">
        <img src="/logo.png" class="sm:h-9" alt="Logo de Jovena Madagascar" />
        <span
            class="self-center whitespace-nowrap text-xl font-semibold dark:text-white"
            >Jovena</span
        >
    </NavBrand>
    <NavHamburger />
    <NavUl>
        <NavLi href="/">Acceuil</NavLi>
        <NavLi href="/#presentation">A propos de nous</NavLi>
        <NavLi href="/#produits">Nos Produits</NavLi>
        <NavLi href="/services">Nos services</NavLi>
        <NavLi href="/#contact">Contact</NavLi>
    </NavUl>
</Navbar>
