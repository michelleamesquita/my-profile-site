<template>
   <v-toolbar color="#0d192e">
       <v-flex mb-4>
       <v-btn icon href="https://www.linkedin.com/in/michelleamesquita/">
           <v-icon color="#90fbdc" class="linkedin">mdi-linkedin-box </v-icon>
       </v-btn>
       </v-flex>

         <v-btn icon href="https://github.com/michelleamesquita">
           <v-icon color="#90fbdc" class="git">mdi-github-circle </v-icon>
       </v-btn>

       <v-spacer></v-spacer>

        <v-toolbar-items> 
            <!-- <v-btn  color="#90fbdc"  text class="tangerine" href="#whoami">0.1 $whoami</v-btn> -->
            <v-btn color="#90fbdc"  text class="tangerine" href="#whoami">0.1 whoami</v-btn>
             <v-btn color="#90fbdc"  text class="tangerine" href="#exp">0.2 experiência</v-btn>
             <v-btn tile outlined color="#90fbdc" class="ma--2" href="https://drive.google.com/file/d/1V3C_N8Xy-T9ZXwIG0q6B04m7MxIlGCXX/view?usp=sharing">Currículo</v-btn>

      </v-toolbar-items>
     
    </v-toolbar>
</template>
<script>
    
</script>
<style>
@import url('https://fonts.googleapis.com/css?family=Roboto+Mono&display=swap');
.tangerine {
  font-family: 'Roboto Mono', monospace;
  text-transform: none !important;
  font-size: 15px !important;
  
} 

.number {
    color: #cbcbef !important;
}

.linkedin{
    padding-left: 45px !important;
    padding-top: 20px !important;
    font-size: xx-large !important;
}

.git{
    padding-right: 1300px !important;
    padding-top: 20px !important;
    font-size: xx-large !important;
    padding-bottom: 15px !important;
}

</style>