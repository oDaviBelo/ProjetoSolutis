<template>
    <div id="global">
        <header>
            <nav>
                            <img src="../assets/sec.png" alt="">

                <router-link>Apresentação</router-link>
                <router-link>Contrato</router-link>
                <router-link>Estrutura Organizacional</router-link>
                <router-link>Canais de Atendimento</router-link>
                <router-link>Ferramentas</router-link>
                <router-link>Volumetria</router-link>
                <router-link>Indicadores</router-link>
                <router-link>Automação</router-link>
                
            </nav>
        </header>
    </div>
</template>

<style scoped>
   
    header{
        display: flex;
        align-items: center;
        justify-content: center;
        flex-direction: row;       
        background-color: #000;
        height: 5rem;
        width: 100%;
    }

    header img{
        height: 100%;
    }
    nav{       
        display: flex;
        align-items: center;
        justify-content: center;
        flex-direction: row;   
        background: rgba(0, 0, 0, .7); 
        position: fixed;
        z-index: 999;
        height: 5rem;
        width: 100%;
        
    }
    nav router-link{
        
        text-decoration: none;
        color:#fff; /*rgba(0, 149, 235, 1);;*/
        cursor: pointer;
        padding: 0.5rem;
        
    }
    nav router-link:hover{
        color:rgba(0, 149, 235, 1);

    }
</style>


<script>
  export default {
    name: "Header"
  }
</script>