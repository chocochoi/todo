<template>
  <div>
    <input type="text" name="" id="" v-model="todoText">
    <button type="button" v-on:click="submitTodo">입력</button>
  </div>
</template>

<script>
export default {
  data(){
    return{
      todoText:""
    }
  },
  methods:{
    submitTodo(){

    }
  }
}
</script>
