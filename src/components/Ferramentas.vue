<template>
    <section id="global">
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
        </div>
    </section>
</template>

<style scoped>
#global{
    display: flex; 
    flex-direction: column;
    justify-content: center;
    align-items: center;
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