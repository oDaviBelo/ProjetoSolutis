<template>
    <section id="global">
        <h2>Sobre a SEC</h2>
        <article id="content">
            <p>
            A Secretaria de Educação do Estado da Bahia, é o órgão responsável pela gestão
             da educação pública no estado da Bahia, Brasil. Tem como principal objetivo desenvolver políticas educacionais, supervisionar as escolas públicas,
             promover a formação de professores e garantir o acesso à educação de qualidade para os cidadãos do estado.
            </p>
            <img src="../assets/sec.png" alt="Logo da Secretaria de Educação do Estado da Bahia" style="width:15vw">
        </article>

    </section>
</template>

<style scoped>
    #global{
        background: rgba(244, 244, 243, 1);
        width:50vw;
        height: 70vh;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        margin: 0 auto;
        margin-top: 3rem;
        margin-bottom: 3rem;
        border-radius: 3rem 3rem 3rem 3rem;
        box-shadow: 3px 3px #f00, -0.5em 0 .4em #00f;
    }
    #global:hover{
        transform: scale(1.01);
    }
    #global h2{
        display: flex;
        justify-content: center;
    } 
    article{
        display: grid;
        grid-template-columns: 60% 30%;
        justify-content: center;
        margin: 0 auto;
        align-items: center;

    }
</style>


<script>
  export default {
    name: "Sobre"
  }
</script>