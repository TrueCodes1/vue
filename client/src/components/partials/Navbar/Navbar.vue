
<template>

    <nav id="nav-bar">

        <NavItem v-bind:to="home['link']" v-bind:text="home['text']" v-bind:color="home['color']" v-bind:rounded="home['rounded']" />
        <NavItem v-bind:to="about['link']" v-bind:text="about['text']" v-bind:color="about['color']" v-bind:rounded="about['rounded']" />
        <NavItem v-bind:to="contact['link']" v-bind:text="contact['text']" v-bind:color="contact['color']" v-bind:rounded="contact['rounded']" />

    </nav>

</template>

<script>

    import NavItem from "./NavItem.vue";

    export default {

        name: 'Navbar',
        components: {

            NavItem

        },
        data () {

            return {

                home: {

                    link: '/home',
                    text: 'Home',
                    color: 'red',
                    rounded: 'false'
                
                },
                about: {

                    link: '/about',
                    text: 'About',
                    color: 'green',
                    rounded: 'true'
                
                },
                contact: {

                    link: '/contact',
                    text: 'Contact',
                    color: 'purple',
                    rounded: 'false'
                
                }

            }

        }

    }

</script>

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