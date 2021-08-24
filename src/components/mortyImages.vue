<template>
    <div>
        
        <div id="Morty" v-for="personaje in personajes" 
        :key="personaje.name" 
        style="display:flex; align-items: center">    
            <img :src="personaje.image" 
            style="width:20%;
            border-radius: 50%;
            padding: 15pt " 
            alt="">
            <h2>{{personaje.name}}</h2>
            
        </div>
        <div v-for="personaje in personajes" :key="personaje.image">
            
        </div>

    </div>
</template>

<script>
//import image from "https://rickandmortyapi.com/api/character"

export default {
    name: "PersonajesMorty",
    data: () => ({
        
        personajes:[
            {
                name: "Rick Sanchez",
                image: "https://rickandmortyapi.com/api/character/avatar/1.jpeg"
            },
            {
                name: "Morty Smith",
                image: "https://rickandmortyapi.com/api/character/avatar/2.jpeg"
            },
            {
                name: "Summer Smith",
                image: "https://rickandmortyapi.com/api/character/avatar/3.jpeg"
            },
            {
                name: "Beth Smith",
                image: "https://rickandmortyapi.com/api/character/avatar/4.jpeg"
            },
            {
                name: "Jerry Smith",
                image: "https://rickandmortyapi.com/api/character/avatar/5.jpeg"
            },
            
        ],
    })

}
</script>

<style scoped>


</style>