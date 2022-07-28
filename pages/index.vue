<template>
  <div class="flex items-center justify-center w-screen h-screen p-5 font-">
    <div class=" flex items-">
      <div>
        <img src="./assets/" alt="">
      </div>
    <h1 class="text-justify text-purple-700 ">
      {{ message }}
    </h1>
    </div>
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
  data () {
    return {
      message: 'قريباً أشياء جميلة تحدث هنا ',
      users: [
        {
          id: 1,
          name: 'imousart'
        },
        {
          id: 2,
          name: 'ifalcondes'
        }
      ]
    }
  },
  head () {
    return {
      script: [
        {
          src: 'https://cdn.splitbee.io/sb.js'
        }
      ]
    }
  }
}
</script>
