<template>
    <div v-if="status.listening_to_spotify == true" class="flex items-center gap-2"> 
        <span>
            <i class='bx bxl-spotify text-2xl' style='color:#4eef3c' aria-hidden="true" ></i>
        </span>
        
        <p class="inline">
            Listening to 
            <span class="text-white animate-pulse">{{ status.spotify.song }}</span> by
            <span class="text-white animate-pulse">{{ status.spotify.artist }}</span> 
        </p>
        
    </div>
    
    <div v-else class="flex items-center gap-2"> 
        <span>
            <i class='bx bxl-spotify text-2xl' style='color:#4eef3c' aria-hidden="true" ></i>
        </span>
        
        <p class="inline">
           Not Listening to Spotify
            
        </p>
        
    </div>
    

    
    

</template>

<script>
 
  import  axios  from 'axios'

  
  export default {
      name: "Lanyard",
      mounted() {
          this.getStatus();
      },
      data() {
          return {
              status: [],
              activity: [],
              
          };
      },
   
      methods: {
          getStatus() {
              axios
                 .get("https://api.lanyard.rest/v1/users/932865250930360331")
                  .then(response => {
                  this.status = response.data.data;
                  this.activity = response.data.data.activities;
                  
                  console.log(this.status);
                  console.warn(this.activity);
              })
                  .catch((error) => {
                  console.log(error);
              });
          }
      },

  }
  
  </script>

<style lang="sass" scoped>

</style>