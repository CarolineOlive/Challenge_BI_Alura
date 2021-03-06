# Challenge_BI_Alura
Repositório destinado a compartilhar os projetos desenvolvidos durante o Challenge de BI da Alura.  
#alurachallengebi


<h1>Desafios</h1>

  <li><a href="#week01"> Semana 1: Desafio de logística - Alura Log</a></li>
  <li><a href="#week02"> Semana 2: Desafio de marketing - Alura Shop</a></li>
  <li><a href="#week03"> Semanas 3 e 4: Desafio de finanças - Alura Store </a></li>
  
<!--Título da semana 1 -->
<h2><a id="week01"</a>Semana 1: Desafio de logística - Alura Log</h2>
  <p>A empresa de logística <b>Alura Log</b> possui uma gama de produtos e faz entregas para todo o país. Ela quer manter a qualidade do serviço prestado e, por isso, precisa de obter constantemente informações para tomada de decisões de forma mais eficaz.</p>
  <img src="https://github.com/CarolineOlive/Challenge_BI_Alura/blob/main/alura_log.png"/>
  <h3><strong>Dados</strong></h3>
    <p>Foram disponibilizadas 4 bases de dados sobre logística no formato CSV sendo essas bases:</p>
      <li>tabela pedidos - contém o registro de todos os pedidos feitos pelos clientes.</li>
      <li>tabela produtos - contém os produtos cadastrados e seus valores.</li>
      <li>tabela veículos - contém veículos registrados que fazem o transporte dos produtos.</li>
      <li>tabela estoque - contém o registro de estoque dos produtos por mês.</li>
      
  <h3><strong>Tratamento dos dados</strong></h3>
    <p> O tratamento dos dados e desenvolvimento do Dashboard foi feito utilizando a ferramenta Power BI e Power Query.</p>
    <p>Foram feitos os seguintes tratamentos:</p>
    <p><b>Tabela pedidos:</b></p>
    <ul>
      <li>alteração da tipagem das colunas</li>
      <li>formatação dos dados das colunas latitude e longitude e alteração da categoria</li>
      <li>formatação da coluna data de entrega e substituição do erro do formato (células sem data) por <i>null</i></li>
    </ul>
    <p><b>Tabela produtos:</b></p>
    <ul>
      <li>alteração da tipagem das colunas</li>
      <li>separação da ID do Produto do nome do produto</li>
    </ul>
    <p><b>Tabela veículos:</b></p>
    <ul>
      <li>formatação dos dados da coluna ID Veículo</li>
    </ul>
    <p><b>Tabela estoque:</b></p>
    <ul>
      <li>formatação dos dados de data</li>
    </ul>
  <h3><strong>Resultados</strong></h3>
    <p><b>Requisitos:</b></p>
    <ul>
      <li>visualizar a quantidade de entregas feitas no prazo
      <li>visualizar a quantidade de entregas feitas em atraso
      <li>mostrar o número de veículos disponíveis
      <li>calcular o Ship to Door (S2D) em dias
      <li>visualizar o nível médio de estoque por ano
      <li>mostrar o índice de ocorrências por estado
    </ul> 
    <p><b>Outros Insights:</b></p>
   
   <p><strong><a href="https://app.powerbi.com/view?r=eyJrIjoiZjg3ODQzMTktMWVjOC00ZDBhLTk0ZmItNmY3MmE4Y2UxMjRjIiwidCI6ImMzZjM2NDZlLWRmY2ItNDlhNS04ZGUxLTc1ODA1Mjg4NTc1YyJ9&pageName=ReportSection">Dashboard Logística</a></strong></p>

<!--Título da semana 2 -->
<h2><a id="week02"</a>Semana 2: Desafio de marketing - Alura Shop</h2>
  <p>A Alura Shop investiu em publicidade para se destacar no mercado, e a gerência da empresa tem dúvidas se o retorno dessa propaganda surtiu efeito.</p>
  <p>A nossa missão é apoiar a gerência em suas tomadas de decisão, e elucidar as dúvidas. Para isso desenvolveremos um dashboard estratégico de marketing com o objetivo de monitorar uma campanha de publicidade paga durante o mês de julho de 2021. Apresentaremos indicadores relevantes para a validação estratégica do negócio.</p>
  <img src="https://github.com/CarolineOlive/Challenge_BI_Alura/blob/main/alura_shop.png"/>
  <h3><strong>Dados</strong></h3>
    <p>Foram disponibilizadas 2 bases de dados no formato JSON sendo essas bases:</p>
      <li>Tabela dipositivos - contém informações de acessos por dispositivo.
      <li>Tabela idade e gênero - contém informações de pessoas que acessaram a página e realizaram ou não compras.
      <p>Ambas possuem os mesmos tipos de informações, a primeira em função dos dispositivos e a segunda em função da idade e gênero.
  <h3><strong>Resultados</strong></h3>
   <p><b>Requisitos:</b></p>
   <ul>
      <li>calcular o total de compras
      <li>calcular o total de valor convertido em compras
      <li>mostrar o total do valor investido na campanha
      <li>calcular o custo por clique
      <li>exibir a jornada de compra
      <li>calcular a taxa de conversão
      <li>mostrar o ticket médio por dispositivo
      <li>mostrar retorno do investimento em publicidade (ROAS) por idade e gênero
      <li>calcular o valor convertido em compras por dia
      <li>configurar o relatório para que atualize todo dia útil às 9 horas da manhã
      <li>exibir data e hora da atualização
    </ul>       
  <h3><strong>Dashboard</strong></h3>
    <p><strong><a href="https://app.powerbi.com/view?r=eyJrIjoiYWUzYzVjYWYtYTQxYi00YWY3LWEzODAtMjBmNGNkNmJmMGYzIiwidCI6ImMzZjM2NDZlLWRmY2ItNDlhNS04ZGUxLTc1ODA1Mjg4NTc1YyJ9&pageName=ReportSection">Dashboard Marketing</a></strong></p>
        
<!--Título da semana 3 -->
<h2><a id="week03"</a>Semana 3: Desafio de finanças - Alura Store</h2>
  <p>Desenvolveremos um dashboard tático da área financeira da Alura Store, no qual vamos criar duas páginas, sendo uma delas exibindo um overview de toda a área financeira e a outra página  realizando uma análise de cenários.</p>
  <p>Teremos duas etiquetas indicando o que precisaremos pensar, sendo elas:</p>
    <li> 1. Overview financeiro.
    <li> 2. Análise de cenário.
  <h3><strong>Dados</strong></h3>
    <p>Foram disponibilizadas 4 bases de dados sobre o setor financeiro, no formato mysql, sendo essas bases:</p>
      <li>Notas fiscais
      <li>Pedidos
      <li>Produtos
      <li>Vendedores
  <h3><strong>Resultados</strong></h3>
   <p><b>Requisitos:</b></p>
   <ul>
      <li>calcular a receita
      <li>calcular o lucro
      <li>exibir os custos
      <li>calcular e exibir despesas
      <li>analisar e exibir mensalmente as métricas
      <li>escolher o ano a ser analisado
      <li>análise de cenário
    </ul>       
  <h3><strong>Dashboard</strong></h3>
         <p><b>Em construção...</b></p>
    <p><strong><a href="">Dashboard Financeiro</a></strong></p>
        
<h1>Badges</h1>
<img alt="badge1" height="160" width="160" src="https://media.discordapp.net/attachments/894955747656482886/894956560311263232/Badge_AlurBI_-_First_.png?width=473&height=473"/><img alt="badge1" height="160" width="160" src="https://camo.githubusercontent.com/72abc3e59c3067ddc923b9eecc2ef7ff431233a779af17b8806e9d8a6272db47/68747470733a2f2f692e706f7374696d672e63632f59535444503447332f42616467652d416c75722d42492d48656c7065722e706e67"/> <img alt="badge1" height="160" width="160" src="https://ci4.googleusercontent.com/proxy/vn3Si6VmIVBsf8hKQ8LJFljIBIthFrT51DLaeqlwH_sOk20N5OCzGccoHbuJKPI75SIyRGcTxdxkP14IEEi5My-Xy5jc70-Klima_FaxbbgfcI60o9GRFTsRFmXVWcw9klaJq9x3U2obPf6pRJRK6MyYY_i4vOSW=s0-d-e1-ft#https://user-images.githubusercontent.com/79534537/137536379-7621259e-c9c3-47f2-b6a8-c9ef3b738d86.png"/> <img alt="badge1" height="160" width="160" src="https://cdn.discordapp.com/attachments/899969795951321118/900124766487330866/Badge_AlurBI_-_Talker.png"/> 
