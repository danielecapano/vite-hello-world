<script>
export default {
    data() {
    return {
      message: 'La mia prima app con Vite!'
      
      
    }
  },
}
</script>

<template>
    <section class="hero">
        <div class="container">
            <div class="content">
                <h1>{{ message }}</h1>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Earum molestiae dicta placeat ipsa necessitatibus non saepe sunt! Laboriosam, repudiandae dolores!</p>
            </div>
            
        </div>
        
    </section>
</template>

<style scope>
.hero {
    background-image: url(../assets/background.jpg);
    background-size: cover;
    background-repeat: repeat;
    background-position: top;
    display: flex;
    align-items: center;
    justify-content: space-between;
    height: 100vh;
    color: #FFF;
    text-shadow: 2px 2px rgba(0, 0, 0, 0.3);
}

h1 {
    font-size: 4rem;
    text-transform: uppercase;
}


    

</style>