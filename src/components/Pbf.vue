<template>
    <div>
             <b-table striped hover :pbfs="pbfs"></b-table>
    </div>
</template>
 <script>
 export default{
    name: 'App', 
    data() {
    return {
      pbfs:[]
    }
  },
  mounted: function(){
      axios.get('http://127.0.0.1:8000/api/pbf/')
      .then(response => this.pbfs = response.data);  
  }
}
 
 </script>