
<template>

    <router-link 
    class="nav-item" 
    :style="[{background: color}, rounded=='false' ? { borderRadius: '10px' } : { borderRadius: 0 }] ">
        
        {{ route }}
            
    </router-link>

</template>

<script>

    export default {

        name: 'NavItem',
        props: {
            route: {
                type: String,
                default: 'Route'
            },
            color: {
                type: String,
                default: 'green'
            },
            rounded: {
                type: String,
                default: 'true'
            }
        }

    }

</script>