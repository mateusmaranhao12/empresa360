<template>
    <div>
        <h5>Indicadores</h5>
        <p>Poderiamos recuperar os indicadores do serviço ID {{id}}</p>
    </div>
</template>

<script>

    export default ({

        name: 'Indicadores',
        props: ['id'],

        created() {
            //console.log('Indicadores - parametro', this.id)
        }

    })

</script>
