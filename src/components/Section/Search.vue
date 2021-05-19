<template>
  <div>
    <b-input-group>
        <template #prepend>
        <b-input-group-text >Search</b-input-group-text>
        </template>
        <b-form-input></b-form-input>
        <b-input-group-append>  
        <b-button variant="info">Find</b-button>
        </b-input-group-append>
    </b-input-group>
  </div>
</template>

<script>
export default {
    data: () => ({
        selected: null,
        options: [
            { value: null, text: 'Type find' },
            { value: 'film', text: 'Film' },
            { value: 'cinema', text: 'Cinema' }
        ]
    })
}
</script>

<style>

</style>