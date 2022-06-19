
<template>

    <router-link
    to="link"
    class="nav-item" 
    :style="[{background: color}, rounded=='true' ? { borderRadius: '10px' } : { borderRadius: 0 }] ">
        
        {{ text }}
            
    </router-link>

</template>

<script>

    export default {

        name: 'NavItem',
        // props: {
        //     text: {
        //         type: String,
        //         default: 'Route'
        //     },
        //     route: {
        //         type: String,
        //         default: 'Route'
        //     },
        //     color: {
        //         type: String,
        //         default: 'green'
        //     },
        //     rounded: {
        //         type: String,
        //         default: 'true'
        //     }
        // }
        props: ['link', 'text', 'color', 'rounded']

    }

</script>