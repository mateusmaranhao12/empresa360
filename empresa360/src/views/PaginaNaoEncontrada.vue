<template>
    <div class="alert alert-danger d-flex align-items-center" role="alert">
        <div>
            <h5><i class="bi bi-exclamation-circle-fill"></i> Ops, essa página não foi encontrada</h5>
        </div>
    </div>
    <div class="col-auto d-flex justify-content-around">
        <button type="button" class="btn btn-danger" @click="$router.push('/')">Voltar para a página inicial</button>
        <button type="button" class="btn btn-danger" @click="$router.push('/dashboard')">Voltar para o Dashboard</button>
    </div>
</template>

<script>
    export default {
        name: 'PaginaNaoEncontrada'
    }
</script>