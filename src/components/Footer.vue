<template>
  <div >
      <footer class="footer">
          <p>{{2+2}}</p>
          <p>{{printText()}}</p>
      </footer>
  </div>
</template>

<script>
export default {
    name:"footer",
    data(){
        return{
            text:"what?"
        }
    },
    methods:{
        printText(){
            return this.text
            
        }
    }
}
</script>

