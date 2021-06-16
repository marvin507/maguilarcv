<template>
<Nav/>
  <main>
    
  </main>
</template>
<script>
import Nav from '@/components/Nav'
import './app.css'
import coin from '../src/assets/coin.mp3'
import {onMounted} from 'vue'
import {Howl, Howler} from 'howler';
export default {
    components:{
      Nav
    },
    setup(){

      onMounted(() => {
        document.title = "Marvin Aguilar"
      })
      const test = 0

      function sonar(){
        var sound = new Howl({
          src: [coin]
        });

        sound.play();
      }
      return{
        sonar
      }
    }
}
</script>

