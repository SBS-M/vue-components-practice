<template>
    <div>
        <div class="plan" @click="seleccionar()" :class="{'plan-activo': seleccionado}">
            <div class="descripcion">
                <span class="titulo">{{ nombre }}</span>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Plan',
    props: {
        nombre: {
            type: String,
            default: "Plan 0 - Prueba",
            required: true
        },
    },
    data() {
        return {
            seleccionado: false
        }
    },
    methods: {
        seleccionar(){
            this.$emit('select', this.nombre);
            this.seleccionado = !this.seleccionado;
        }
    }
}
</script>

<style>
    
</style>