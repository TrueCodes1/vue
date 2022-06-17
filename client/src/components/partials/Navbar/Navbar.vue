<script setup>

    import NavItem from "./NavItem.vue";

</script>

<template>

    <nav id="nav-bar">

        <NavItem route="Home" />
        <NavItem route="About" />
        <NavItem route="Contact" />

    </nav>

</template>

<style>

    #nav-bar {

        max-width: 600px;
        min-height: 2em;
        display: flex;
        flex-direction: row;
        align-items: center;
        justify-content: space-between;
        border: 2px solid red;
        position: absolute;
        left: 0;
        right: 0;
        margin: 0 auto;

    }

    .nav-item {

        font-size: 24px;
        color: black;
        list-style: none;

    }

</style>