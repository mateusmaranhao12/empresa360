<template>
    <div>
        <h5>Opções</h5>
        <p>Poderiamos recuperar as opções do serviço ID {{id}}</p>
    </div>
</template>

<script>

    export default ({

        name: 'Opcoes',
        props: ['id'],
        created() {
            //console.log('Parametro via props: ', this.id)
        },

        //beforeRouteUpdate(to, from, next) 
        
        beforeRouteUpdate() {
            console.log('Guarda de componente BeforeRouteUpdate')
        }

    })

</script>