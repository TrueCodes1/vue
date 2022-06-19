
<template>

    <div class="info">
        
        <div v-for="inf in info" :key="inf.id" class="about-person">

            {{ inf.name }} {{ inf.surname }} - {{ inf.age }}

        </div>
        
    </div>

</template>

<script>

    export default {

        name: 'AboutPieceOfInfo',
        props: [

            'name', 
            'surname',
            'age',
            'id'

        ]

    }

</script>
