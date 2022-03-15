<template>
    <nav>
        <div>
            <button  v-if="isShown" @click="showP()">Show paragraph</button> <br>
            <button v-else@click="showP()">Hide paragraph</button>
        <p  v-if="isShown" class="p-if"> I was hiding</p>
        </div>
    </nav>
</template>
<script>

export default {
  name: 'Navbar',
  data() {
      return{
          isShown: false,
      }
  },
  methods: {
      showP(){
          this.isShown = ! this.isShown
      }
}
}
</script>
