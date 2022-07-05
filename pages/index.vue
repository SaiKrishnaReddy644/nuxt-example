<template>
  <v-row justify="center" class="py-5" align="center">
    <input @input="getValue()"/>
    {{name}}
  </v-row>
</template>

<script>
export default {
  layout: 'dashboard',
  data(){
    return {
      name:""
    }
  },
  methods:{
    getValue(){
      console.log(this.name)
    }
  }
}
</script>
