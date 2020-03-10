<template>
    <div>
        <section>
            <br>
            <h3>Curso que estoy realizando:</h3>
            <h5>{{ miCurso }}</h5>
            <br>
            <h3>Generación:</h3>
            <h5>{{ miGeneracion }}</h5>
            <br>
            <h3>Fecha Inicio:</h3>
            <h5>{{ inicioClases }}</h5>
            <br>
        </section>
    </div>
</template>

<script>
export default {
    name: 'Curso',
    data()
    {
        return {
            miCurso: 'Front End Trainee',
            miGeneracion: '3',
            inicioClases: '13 de Enero, 2020'
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