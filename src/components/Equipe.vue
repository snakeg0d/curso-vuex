<template>
    <div>
        <div class="row">
            <div class="col-2" ><strong>ENFERMEIRO</strong></div>
            <div class="col-2" ><strong>SOCORRISTA</strong></div>
            <div class="col-2" ><strong>MEDICO</strong></div>
            <div class="col-2" ><strong>CARRO</strong></div>
            <div class="col-2" ><strong>TELEFONE</strong></div>
            <div class="col-2" ><strong>KIT DE REANIMACAO</strong></div>
      </div>
        <div class="row">
            <div class="col-2" v-text="dados.enfermeiro"></div>
            <div class="col-2" v-text="dados.socorrista"></div>
            <div class="col-2" v-text="dados.medico"></div>
            <div class="col-2" v-text="dados.carro"></div>
            <div class="col-2" v-text="dados.telefone"></div>
            <div class="col-2" v-text="dados.kitsDeReanimacao"></div>
        </div>

    </div>
</template>

<script>
export default {
    name: 'Equipe',
    props: {
        dados: Object
    }
}
</script>
