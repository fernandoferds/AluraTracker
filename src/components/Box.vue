<template>
    <div class="box has-text-weight-bold" :style="estilos">
        <slot></slot>
    </div>
</template>

<script lang="ts">
import { DefineComponent, defineComponent } from 'vue';
export default defineComponent({
    name: 'BoxComp',
    data() {
        return {
            estilos: {
                backgroundColor: '#FAF0CA'
            }
        }
    }
})
</script>

