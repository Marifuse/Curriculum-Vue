<template>
    <div>
        <header>
            <h1>{{ titulo }}</h1>
        </header>
        <section>
            <h3>Nombre:</h3>
            <h5>{{ miNombre }}</h5>
            <br>
            <h3>Rut:</h3>
            <h5>{{ miRut }}</h5>
            <br>
            <h3>Edad:</h3>
            <h5>{{ miEdad }}</h5>
            <br>
            <h3>Nacionalidad:</h3>
            <h5>{{ miNacionalidad }}</h5>
            <br>
        </section>
    </div>
</template>

<script>
export default {
    name: 'Personal',
    props: {
        titulo: String
    },
    data()
    {
        return {
            miNombre: 'María Jesús Fuenzalida Serrano',
            miRut: '17.544.923-K',
            miEdad: '29',
            miNacionalidad: 'Chilena'
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
