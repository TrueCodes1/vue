
<script setup>

    import AboutPieceOfInfoVue from './AboutPieceOfInfo.vue'

</script>

<template>
    
    <AboutPieceOfInfo :info="info" />

</template>

<script>

    export default {

        name: 'AboutInfo',
        data: () => {

            return {

                info: [

                    {
                        id: 'about-1',
                        name: 'John',
                        surname: 'Doe',
                        age: '14'
                    },
                    {
                        id: 'about-2',
                        name: 'Jane',
                        surname: 'Delovere',
                        age: '23'
                    },
                    {
                        id: 'about-3',
                        name: 'Eugene',
                        surname: 'Ebenezer',
                        age: '81'
                    }

                ]

            }

        }

    }

</script>