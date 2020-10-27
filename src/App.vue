<template>
  <div id="app">
    <h1>HelloWorld.</h1>
    <Button 
    :onClick = registerUser>
    登録
    </Button>
  </div>
</template>

<script>
import Button from "@/components/Button.vue"

export default {
  name: 'App',
  components: {
    Button
  },
  setup(){
    const registerUser = () => {
      console.log("ok");
    }
    return {
      registerUser
    }
  }

}
</script>

<style>
</style>
