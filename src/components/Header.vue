<template>
    
        
            <header >
                <div class="container">
                    <nav class="glass">
                        <div class="logo">
                            <img src="../assets/vue.svg" alt="logo">
                        </div>
                
                        <ul>
                            <li><a href="#">Home</a></li>
                            <li><a href="#">About</a></li>
                            <li><a href="#">Works</a></li>
                            <li><a href="#">Contanct</a></li>
                            <li><button>Login</button></li>
                        </ul>
                    </nav>
                </div>
            </header>
       
    
</template>

<style scope>

.glass {
background: rgba(255, 255, 255, 0.025);
border-radius: 8px;
box-shadow: 0 4px 30px rgba(0, 0, 0, 0.4);
backdrop-filter: blur(4px);
border-top: 1px solid rgba(255, 255, 255, 0.15);
border-left: 1px solid rgba(255, 255, 255, 0.15);
color: #FFF;
text-shadow: 0px 0px 10px rgba(0,0,0,0.4);
}

header {
    position: absolute;
    top: 1rem;
    left: 0;
    right: 0;
    color: #FFF;
    padding: 0 2rem;
}
nav {
    padding: 0 1rem;
    display: flex;
    align-items: center;
    justify-content: space-between;
}

.logo {
    font-weight: 700;
    font-size: 2rem;
}

ul {
    display: flex;
    gap: 2rem;
    align-items: center;
    list-style: none;
}


</style>