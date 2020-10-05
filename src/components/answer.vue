<template>
  <div class="alert alert-success text-center">
         <h1 class="text-center">That's Correct</h1>
         <br>
         <button class="btn btn-primary" @click="onNextQuestion">Next Question</button>
  </div>
</template>

<script>


export default {
  name: 'Answer',
  
  methods: {
    onNextQuestion(){
        this.$emit('confirmed');
    }
  }
}
</script>

<style>

</style>
