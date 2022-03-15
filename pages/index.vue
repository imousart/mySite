<template>
  <div>
    <h1 class="flex justify-center mt-10 font-ibm-200 text-purple-700 ">
      {{ message }}
    </h1>
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
  data () {
    return {
      message: ':)في المرة القادة لزيارتك سوف نقوم بإضافة بعض المزيد من المعلومات عن الموقع'
    }
  }
}
</script>
