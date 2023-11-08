<template>
    <div id="global">
        <header>
            <nav>
                <img src="../assets/logosolutis.jpg" alt="">
                <img src="../assets/sec.png" alt="">
                            
                <a href="#apresentacao">Apresentação</a>
                <a href="#contrato">Contrato</a>
                <a href="#estrutura">Estrutura Organizacional</a>
                <a href="#canais">Canais de Atendimento</a>
                <a href="#ferramentas">Ferramentas</a>
                <a href="#volumetria">Volumetria</a>
                <a href="#indicadores">Indicadores</a>
                <a href="#auditoria">Auditoria</a>
                <a href="#automação">Automação</a>
            
                
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
        background-color: #fff;
        height: 5rem;
        width: 100%;
        color: #000;
    }
    header a{
        text-decoration: none;
        color: inherit;
        padding: 0.5rem;
    }
    header img{
        height: 100%;
        padding: 0.5rem;
    }
    nav{       
        display: flex;
        align-items: center;
        justify-content: center;
        flex-direction: row;   
        position: fixed;
        color: #000;
        z-index: 999;
        height: 5rem;
        width: 100%;
                background-color: #fff;

    }
    nav router-link{
        
        text-decoration: none;
        color:#fff; /*rgba(0, 149, 235, 1);;*/
        cursor: pointer;
        padding: 0.5rem;
        color: #000;
        
    }
    nav router-link:hover{
        color:#0075bd

    }
</style>


<script>
  export default {
    name: "Header"
  }
</script>