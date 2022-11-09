<template>
    <section>
  <div class="about-us">
    <h2>We are hiring.</h2>
    <p>Are you looking for a new challenge? You are passionate about innovation and enjoy working with people? Then you've come to the right place.</p>
   </div>
    <div class="image-wrapper">
    <img src="../assets/img/georgie-cobbs-muOHbrFGEQY-unsplash.jpg" />
  </div>
</section>
</template>

<script>
    export default {
        name:'AppHero',
        data() {
            return {
                
            }
        },
    }
</script>

<style lang="css">
body {
  height: 100%;
  display: grid;
  place-items: center;
  background-color: #F9FAFB;
}

section {
  max-width: 80rem;
  background: linear-gradient(to right, #4C1D95 30%,  #8B5CF6);
  color: white;
  line-height: 1.5;
  font-family: 'Nunito', sans-serif;
}

@media (min-width: 600px) {
  section {
    display: grid;
    grid-template-columns: 1fr 1fr;
  }
  
  .about-us {
    padding: 3vw 0 3vh 3vw;
  }
  
  .image-wrapper {
    filter: hue-rotate(20deg);
    clip-path: polygon(0% 100%, 50% 0%, 100% 0%, 100% 100%);
  }
}

.about-us {
  display: flex;
  flex-direction: column;
  justify-content: center;
  padding: 2rem;
}
  h2 {
    font-weight: 600;
    white-space: nowrap;
    font-size: clamp(2rem, 5vw, 4rem);
    margin-bottom: .5rem;
  }
  
  p {
    font-size: clamp(1rem, 1.5vw, 3rem);
  }


.image-wrapper {
  height: 100%;
  width: 100%;
  clip-path: polygon(0%, 0%, 0% 0%);
}
  img {
    display: block;
    height: 100%;
    width: 100%;
    object-fit: cover;
    object-position: right center;
  }



</style>