<template>
<div>
  {{loadedData}}

  //properties dropdown und list
  <dropdown></dropdown> 
  <list></list>
  </div>
</template>

<script>
import dropdown from '../components/dropdown.vue'
import list from '../components/list.vue'
import axios from 'axios'


  export default {
    name: 'Plan',
    components: {
      dropdown, list
    },
      props: {
        msg: String
      }, 
data: function() {
  return {
    loadedData: 'no data loaded',
  }
}, 
      mounted() {
        axios.get("https://foaas.com/linus/Test/me")
        .then(response => {
          this.loadedData = response
         })
         .catch(err => {
           console.log(err);
         })
      }
    }
    

</script>

<style scoped>

 </style>