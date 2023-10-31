<template>
    <section id="global">
        <div id="escopodoContrato"> 
            <h2>Escopo do Contrato</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Molestiae facere vel eligendi tempore laborum, minus ipsum similique at,
             ea eos veniam. Culpa facilis, reprehenderit repellat quae cumque reiciendis praesentium velit!Lorem ipsum dolor sit amet, consectetur adipisicing elit. Molestiae facere vel eligendi tempore laborum, minus ipsum similique at,
             ea eos veniam. Culpa facilis, reprehenderit repellat quae cumque reiciendis praesentium velit</p>
        </div>
        <div id="atendimentoHorario">
            <table>
                <caption><strong>Horário de Atendimento</strong></caption>
                <tr>
                    <th>Segunda</th>
                    <th>Terça</th>
                    <th>Quarta</th>
                    <th>Quinta</th>
                    <th>Sexta</th>


                </tr>
                <tr>
                    <th>8:00 - 17:00</th>
                    <th>8:00 - 17:00</th>
                    <th>8:00 - 17:00</th>
                    <th>8:00 - 17:00</th>
                    <th>8:00 - 17:00</th>
                </tr>
            </table>
        </div>
    </section>
</template>

<style scoped>
    #global{
        display: flex;
        flex-direction: column;
        justify-content: center;
       background: #161922;
       color: #ccc;
       padding-bottom: 3rem;
    }

    #escopodoContrato{
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        width:50vw;
        margin: 0 auto;
    }
    table{
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }

    table {
  border-collapse: collapse;
}

th{
  text-align: left;
  padding: 4px;
  border: 1px solid #ccc;

}
</style>


<script>
  export default {
    name: "Contratos"
  }
</script>