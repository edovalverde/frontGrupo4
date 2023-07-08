<script>
import NavLogo from './NavLogo.vue';
import NavMenu from './NavMenu.vue';
export default {
    name: `NavContainer`, components: {
        NavLogo,
        NavMenu
    }
}
</script>

<template>
    <nav id="NavContainer">
        <NavLogo />
        <NavMenu/>
    </nav>
</template>

<style>
#NavContainer{
    background-color: black;
    display: flex;
    justify-content: space-between;
}

</style>