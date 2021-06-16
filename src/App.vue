<template>
<Nav/>
  <main>
    
  </main>
</template>
<script>
import Nav from '@/components/Nav'
import './app.css'
import coin from '../src/assets/coin.mp3'
import {Howl, Howler} from 'howler';
export default {
    components:{
      Nav
    },
    setup(){
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

