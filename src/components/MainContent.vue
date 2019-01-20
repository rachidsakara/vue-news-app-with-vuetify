<template>

    <v-layout row wrap align-center>
          
          <v-flex xs8  offset-md2>
            <div v-for="article in articles" :key="article.title">
              <!--The Card Component go here-->
              <Card :article="article"></Card>
            </div>
          </v-flex>

  </v-layout>

</template>

<script>

import Card from './Card.vue' // import the Card component


export default {

  components:{
    Card
  },

  props: {
      articles: Array
  }

}

</script>
