<template>
<div>

 

  <v-banner class="red white--text">Mortal</v-banner>
<v-toolbar-side-icon class="grey--text">DARSHAN GADA</v-toolbar-side-icon> 
  <v-toolbar class="yellow red--text">Jonathan</v-toolbar>

      <h1>Homepage</h1>

    <v-btn class="red white--text">click me</v-btn>

     <v-spacer></v-spacer>

     <v-btn color="red">click me </v-btn>
     <v-spacer></v-spacer>

    <!-- <v-btn depressed small dark color="purple">
    <v-icon>ƒavourite</v-icon>  
    </v-btn> -->

     <v-spacer></v-spacer>

<v-btn flat color="grey">

  <span>Sign Out</span>



  <!-- <v-icon >exit_to_app</v-icon> -->
</v-btn>
    
<v-navigation-drawer v-model="drawer" app class="indigo white--text">

  <p>Hacker</p>

</v-navigation-drawer>


 <v-navigation-drawer app v-model="drawer" class="warning">
   <p>test</p>
 </v-navigation-drawer>

  <!-- <v-list>
    <v-list-tile>
      <v-list-tile-content>
        <v-list-tile-tittle class="white--text">Dashboard</v-list-tile-tittle>
      </v-list-tile-content>
    </v-list-tile>
  </v-list> -->
<br>

<v-list-item-group class=" red yellow--text"><h1>Danish zehen ♠</h1></v-list-item-group>


</div>

</template>

<script>


export default({
  setup() {
    return{
      drawer:false
    }
  },
})
</script>

<style scoped>

</style>
