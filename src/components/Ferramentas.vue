<template>
    <section id="ferramentas">
        <h2>Ferramentas</h2>
        <div class="tools">
            <div>
                <img src="../assets/glpi.png" alt="">
            </div>
            <div>
                <img src="../assets/logmein.png" alt="">
            </div>
            <div>
                <img src="../assets/microsip.png" alt="">
            </div>
            <div>
                <img src="../assets/powerbi.png" alt="">
            </div>
            <div>
                <img src="../assets/excel.png" alt="">
            </div>
            <div> 
                <!--Adicionar LOGO GSERV-->
                <img src="../assets/insiraaqui" alt="">
            </div>
            <div>
                <!--Adicionar LOGO hermes itoc-->
                <img src="../assets/insiraaqui" alt="">
            </div>
        </div>
    </section>
</template>

<style scoped>
#ferramentas{
    display: flex; 
    flex-direction: column;
    justify-content: center;
    align-items: center;
    padding: 5rem;
}
    .tools{
        display: flex;
        gap: 2rem;
    }
    .tools img{
        height: 4rem;
    }
</style>


<script>
  export default {
    name: "Ferramentas"
  }
</script>