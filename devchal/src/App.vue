<template>
  <body id="app" class="black-1">
    <link href="https://cdnjs.cloudflare.com/ajax/libs/tailwindcss/2.2.19/tailwind.min.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta2/css/all.min.css" integrity="sha512-YWzhKL2whUzgiheMoBFwW8CKV4qpHQAEuvilg9FAn5VJUDwKZZxkJNuGM4XkWuk94WCrrwslk8yWNGmY1EduTA==" crossorigin="anonymous" referrerpolicy="no-referrer" />
<!-- -->
    <div class="w-full h-screen">
          
      <Navbar></Navbar>

      <!-- Hero -->
      <div class="w-full h-screen">

        <div class="py-10 px-96  flex justify-between">

          <h1 class="flex justify-center pt-60 text-6xl text-white font-bold">
            <img class="h-14 " src="./assets/Logo-D.png">
              <p class="">DevChall</p>
            <img class="h-14 " src="./assets/Logo-C.png">
          </h1> 

          <img class="h-96" alt="Vue logo" src="./assets/logo.png">

        </div>

      </div>
      <!-- /Hero -->


      <!-- Projects -->
      <div class="flex justify-center pt-20">
        
        <!-- CARD -->
        <div class="w-80 h-96 gray-1">

        </div>
        <!-- /CARD -->

      </div>
      <!-- /Projects -->          

    </div>

    <div class="w-full h-screen bg-indigo-800"></div>

  </body>    

</template>

<script>
import Navbar from './components/Navbar.vue'

export default {
  name: 'App',
  components: {
    Navbar,
  }
}
</script>

<style>
#app {
      font-family: ui-sans-serif,system-ui,-apple-system,BlinkMacSystemFont,Segoe UI,Roboto,Helvetica Neue,Arial,Noto Sans,sans-serif,Apple Color Emoji,Segoe UI Emoji,Segoe UI Symbol,Noto Color Emoji;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

.black-1 {
  background-color: #1D1D20;
}

.gray-1 {
  background-color: #2E2E33;
}

.green-1 {
  background-color: #4FD1C5;
}

.title {
  font-family: Red Hat Display,sans-serif;
}
</style>
