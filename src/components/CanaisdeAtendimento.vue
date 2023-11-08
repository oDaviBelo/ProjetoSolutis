<template>
    <section id="canais">
                <h2>Canais de Atendimento</h2>

        <div class="data">
        <div class="canais-1">
          <div class="floating-element rotate-animation">
          <img src="../assets/smartphone.png" alt="">
        </div>
        <h4>Telefone: <a href='tel:0800-095-1414'>0800-095-1414</a></h4>
        </div>
        <div class="canais-1">
          <div class="floating-element">
          <img src="../assets/email.png" alt="">
        </div>
        <h4>E-mail SEC: <a href="mailto:centraldeservicos@educacao.ba.gov.br">centraldeservicos@educacao.ba.gov.br</a></h4>
        </div>
        <div class="canais-1">
          <div class="floating-element">
          <img src="../assets/email.png" alt="">
        </div>
        <h4>E-mail SEC SISTEMAS: <a href="mailto:suportes.sistemas@enova.educacao.ba.gov.br">suportes.sistemas@enova.educacao.ba.gov.br</a></h4>
        </div>
        <div class="canais-1">
          <div class="floating-element">
          <img src="../assets/input.png" alt="">
        </div>
        <h4>Sistemas de Chamados: <a href="http://servicedesk.sec.solutis.net.br/">http://servicedesk.sec.solutis.net.br/</a></h4>
        </div>
        <div class="canais-1">
          <div class="floating-element">
          <img src="../assets/bot.png" alt="">
        </div>
        <h4>Chatbot (WhatsApp) <a href="https://wa.me/557130212944">(71)3021-2944</a></h4>
        </div>
        </div>
        
    </section>

    
</template>

<style scoped>

    section{
        display: flex;
        flex-direction: column;
        text-align: center;
        background: #f2f3f5;
        padding: 05rem;
}
section h2{
  color: #000;
}
section h4{
  color: #0075bd;
}

.data{
  justify-content: center;
  align-self: center;
  align-items: center;
  
}

.floating-element {  
    animation-name: floating;
    animation-duration: 3s;
    animation-iteration-count: infinite;
    animation-timing-function: ease-in-out;
    margin-left: 30px;
    margin-top: 5px;
}
 
@keyframes floating {
    0% { transform: translate(0,  0px); }
    50%  { transform: translate(0, 3px); }
    100%   { transform: translate(0, -0px); }
}
.floating-element img{
  height: 70px;

}


.canais-1{
  display: flex;
  gap: 1rem;
  align-items: center;
}

body a{
  color: inherit;
}


</style>


<script>
  export default {
    name: "Canais"
  }
</script>