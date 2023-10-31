<template>
    <div>
        <section>
            <h1>Secretaria de Educação da Bahia</h1>
            <h2>Coordernação</h2>
            <div id="lider">
                <div class="card">
                    <h3>Líder</h3>
                <img src="../assets/ueslei.jpeg" alt="">
                <h4>{{lider}}</h4>
                </div>
            </div>
            
            <div id="liderados">
                <div class="membros">
                    <h3>Liderados</h3>
                <div>
                    <div class="card">
                    <h4>{{liderado1}}</h4>
                <img src="../assets/head.png" alt="">
                </div>
                <div class="card">
                    <h4>{{liderado2}}</h4>
                <img src="../assets/head.png" alt="">
                </div>
                <div class="card">
                    <h4>{{liderado3}}</h4>
                <img src="../assets/head.png" alt="">
                </div>
                <div class="card">
                    <h4>{{liderado4}}</h4>
                <img src="../assets/head.png" alt="">
                </div>
                </div>
                <div>
                    <div class="card">
                    <h4>{{liderado5}}</h4>
                <img src="../assets/head.png" alt="">
                </div>
                
                <div class="card">
                        <h4>{{liderado6}}</h4>
                <img src="../assets/head.png" alt="">
                </div>
                
                <div class="card">
                    <h4>{{liderado7}}</h4>
                <img src="../assets/head.png" alt="">
                </div>
                <div class="card">
                    <h4>{{liderado8}}</h4>
                <img src="../assets/head.png" alt="">
                </div>
                </div>
                </div>

            </div>
        </section>
    </div>
</template>

<style scoped>
    
    section{
        background-color: #283142;
        display: flex;
        justify-content: center;
        flex-direction: column;
        align-items: center;
        color: #fff;
        height: 100%;
        width: 100%;
        padding-bottom: 1.2rem;
    }
    #lider{
        display: flex;
        justify-content: center;
    }
    .membros{
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: column;
        width: 100%;
        flex-wrap: wrap;
    }
    .membros div{
        display: flex;
        flex-direction: row;
        justify-content: center;
    }

    .card{
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        background-color: rgba(244, 244, 243, 1);
        margin: 0.5rem;
        border-radius: 1rem 1rem 1rem 1rem;
        width: 10vw;
        padding: 1rem;
        color:#2c2c2c;
        
    }

    .card:hover{
        transform: scale(1.05);
    }
    img{
        height: 8rem;
        width: 6rem;
    }
</style>
<script>
  export default {
    name: "Banner",
    data(){
    return{
        lider: "Ueslei",
        liderado1:"Pedro",
        liderado2:"Paulo",
        liderado3:"Joao",
        liderado4:"Marcio",
        liderado5:"Davi",
        liderado6:"Carlos",
        liderado7:"Wagner",
        liderado8:"Cauly",

    }
  }
  }
</script>