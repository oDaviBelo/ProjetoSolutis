<template>
    <div>
        <section id="apresentacao">
            <h1>Secretaria de Educação da Bahia</h1>
            <h2>Coordernação</h2>
            <div id="lider">
                <div class="card">
                    <h3>Líder</h3>
                <img src="../assets/ueslei.jpeg" alt="" mouseover="handleMouse()">
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
        background-color: #0075bd;
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
        background-color: rgba(256, 256, 256, 1);
        margin: 0.5rem;
        border-radius: 1rem 1rem 1rem 1rem;
        width: 10vw;
        padding: 1rem;
        color:#2c2c2c;
        position: relative;
        transition: transform 1s ease, z-index 0.1s ease;
    }

    .card:hover{
        transform: scale(1.05);
        transform: rotateY(180deg);
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
  },mouted(){
    var card = document.querySelector('.card');
    card.addEventListener('mouseover',this.handleMouse)
  },methods:{
    handleMouse(){
    console.log('oi')
    },
  }

  
  }
  
</script>


  