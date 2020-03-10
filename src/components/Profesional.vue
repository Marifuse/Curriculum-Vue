<template>
    <div>
        <section>
            <br>
            <h3>Profesión:</h3>
            <h5>{{ miProfesion }}</h5>
            <br>
            <h3>Habilidades:</h3>
            <h5>{{ miHabilidad }}</h5>
            <br>
            <h3>Otros:</h3>
            <h5>{{ otros }}</h5>
            <br>
        </section>
    </div>
</template>

<script>
export default {
    name: 'Profesional',
    data()
    {
        return {
            miProfesion: 'Profesora de Historia y Geografía',
            miHabilidad: 'Dibujar, Investigar, Leer, Diseñar Páginas Web',
            otros: 'Realicé una investigación FONDECYT desde el año 2014 hasta el 2017'
        }
    }
}
</script>

<style scoped>
    h3 {
        font-size: 2em;
        text-decoration: underline;
        color: black;
    }
    h5 {
        font-size: 2em;
        color: black;
    }
</style>