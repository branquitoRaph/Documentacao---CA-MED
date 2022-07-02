# TRABALHO DE PI:  Catálogo de Medicamentos Ca'Med
![Logo](https://user-images.githubusercontent.com/108133362/177004618-b4eb892c-cf18-461a-9a1e-f9afbe9681e9.png)
<br>
Trabalho desenvolvido durante a disciplina de Banco de Dados do Integrado


# Sumário

### 1. COMPONENTES<br>
Integrantes do grupo<br>
João Eid Dias Pinto: jaooeiid@gmail.com<br>
Jonathan Castro Silva: jonathancastrosilva8@gmail.com<br>
Raphael Da Silva Branco: raphaelbranco2004@gmail.com<br>
...

### 2.MINIMUNDO<br>

Tema: Catálogo de Medicamentos<br>

Um cliente solicitou um sistema para catalogar os medicamentos existentes no mercado baseado nos sintomas mais comuns da população brasileira. Nesse sistema os medicamentos possuem: nome, PMVC (Preço Máximo Vendido ao Consumidor) e se precisa de receita ou não. Já nos sintomas registramos somente o nome do sintoma. Um sintoma pode ter vários medicamentos para tratar e um medicamento pode ter vários sintomas para tratar. Além de, o cliente também solicitou uma página de contato (Fale Conosco) e ele quer armazenar o usuário que irá utilizar o site, cadastrando-o e consequentemente fazendo seu login toda vez que for acessar o site, os dados pedidos durante o cadastro, contato e login fica a cargo dos desenvolvedores. Fica também a cargo dos desenvolvedores, adicionar mais itens se possível. O cliente solicita também, um menu (janela) com notícias sobre assuntos relacionados: saúde, medicação dentre outros.<br>


### 3.PMC<br>
![Exemplo de PMC](Link "PMC")
<br>

### 4.Personas e Histórias de usuário<br>
<img src="https://neilpatel.com/wp-content/uploads/2019/07/exemplo-carlos.png" Personas src="https://neilpatel.com/wp-content/uploads/2019/07/exemplo-carlos.png" width="500" height="500" /> <br>
a) inclusão dos Persons desenvolvidos pelo grupo<br>
<br>
<img src="https://miro.medium.com/max/1400/1*r5GVnOvqpMdxnGUYNRXqbg.png" UserStory src="https://miro.medium.com/max/1400/1*r5GVnOvqpMdxnGUYNRXqbg.png" width="500" height="300" /> <br>
b) inclusão das Histórias de usuário desenvolvidas pelo grupo
<br>
<b>Histórias de Usuário da Jarula:</b>
<br>
<p>1) Eu, Jarula, quero ter acesso a um bom catálogo de medicamentos que seja fácil e prático de usar, para que eu possa encontrar remédios para meus problemas de saúde sem dificuldade.</p>
<br>
<p>2) Eu, Jarula, quero poder encontrar medicamentos baratos sem precisar procurar fora de casa, para ter tempo de cuidar dos meus filhos e ter dinheiro sobrando para sustentá-los. </p>
<br>
<p>3) Eu, Jarula, quero poder encontrar remédios através dos sintomas sentidos, para que possa achar medicamentos sem precisar conhecer os nomes dos mesmos.</p>
<br>
<p>4) Eu, Jarula, quero poder encontrar os preços de medicamentos desejados, vendo o preço máximo vendido ao consumidor, para que possa comparar diferentes preços e encontrar aquele que possui maior custo-benefício.</p>
<br>
<p>5) Eu, Jarula, quero poder ter informações acerca da prescrição médica dos medicamentos, sabendo se ele precisa ou não de receita, para facilitar a parte de pesquisa e poupar tempo na hora de comprar o remédio. </p>
<br>
<p>6) Eu, Jarula quero poder repassar esse catálogo para meus filhos, para que quando não puder acessar pedir a eles para verem.</p>
<br>
<p>7) Eu, Jarula quero que o catálogo seja bastante intuitivo, com cores e caixas para que fique fácil de usar.</p>
<br>
<p>8) Eu, Jarula Auxiliar de Serviços Gerais quero que o catálogo não gere nenhum tipo de pagamento pelo serviço, pois tenho um salário baixo e muitas despesas.</p>
<br>
<br>


<b>Histórias de Usuário do Pedro:</b>
<br>
<p>1) Eu, Pedro Martins, quero diferentes tipos de remédios genéricos para possíveis problemas de saúde que eu tenha. </p>
<br>
<p>2) Eu, Pedro Martins, quero os menores preços possíveis para o menor gasto possível </p>
<br>
<p>3) Eu, Pedro Martins, quero a mais rápida disponibilidade desses remédios para a menor espera possível.</p>
<br>
<p>4) Eu, Pedro Martins, quero se possível, ter acesso a bula antes da compra de um produto, para saber seus componentes. </p>
<br>
<p>5) Eu, Pedro Martins, quero saber se é necessário uma receita para fazer a compra desse remédio. </p>
<br>
<p>6) Eu, Pedro Martins, quero ter acesso ao preço máximo vendido ao consumidor (PMVC) para saber se estou pagando muito em um medicamento. </p>
<br>
<p>7) Eu, Pedro Martins, quero se possível, fazer login e armazenar em minha conta os remédios que mais uso.</p>
<br>
<p>8) Eu, Pedro Martins, quero que o catálogo seja bastante intuitivo, para que o acesso seja simples, prático e objetivo, sem muitas alegorias ou contextualidades. </p>
<br>
<br>


<b>Histórias de Usuário do Sérgio:</B>
<br>
<p>1) Eu, Sérgio, quero encontrar um catálogo de medicamentos que possa me atender de maneira rápida e sem burocracia, para que eu possa encontrar rapidamente os remédios de que preciso. </p>
<br>
<p>2) Eu, Sérgio, quero encontrar remédios bons, que tenham efeito rápido, para me garantir melhoria, independentemente de seu preço.</p>
<br>
<p>3) Eu, Sérgio, quero conseguir remédios que funcionem, também, a longo prazo, para que eu não me preocupe para o resto de minha vida com o uso rotineiro de medicamentos. </p>
<br>
<p>4) Eu, Sérgio, quero poder ter uma melhor qualidade de vida e um tempo mais proveitoso com meus filhos, sem os incômodos constantes que sinto, para que eu possa me aproximar mais da minha família. </p>
<br>
<p>5) Eu, Sérgio, quero ter acesso a uma plataforma dinâmica e organizada para procurar medicamentos, onde as informações sejam bem dispostas, para que eu encontre o que quero saber facilmente e sem problemas.</p>
<br>
<p>6) Eu, Sérgio, quero que meus filhos também consigam utilizar o site, para que eu consiga mais rapidez em encontrar o medicamento.</p>
<br>
<p>7) Eu, Sérgio, quero poder guardar os medicamentos que eu pesquisei, para que quando precisar novamente, encontrá-lo com mais rapidez e facilidade.</p>
<br>
<p>8) Eu, Sérgio, quero também que o site tenha um campo com notícias sobre essa questão de saúde/medicação, para conseguir resolver meu problema o mais rápido possível, pois, como meu tempo é precioso, gostaria de ter acesso a essas informações quando entrar no site para procurar por medicamentos.</p>
<br>
<br>



### 5.RASCUNHOS BÁSICOS DA INTERFACE (MOCKUPS)<br>
Neste ponto a codificação não e necessária, somente as ideias de telas devem ser desenvolvidas. O princípio aqui é pensar na criação da interface para identificar possíveis informações a serem armazenadas e/ou descartadas <br>

Sugestão: https://balsamiq.com/products/mockups/<br>

![Alt text](https://github.com/discproint/template_projeto_integrador/blob/main/arquivos/balsamiq.png?raw=true "Title")
![Arquivo PDF do Protótipo Balsamiq feito para Empresa Devcom](https://github.com/discproint/template_projeto_integrador/blob/main/arquivos/EmpresaDevcom.pdf?raw=true "Empresa Devcom")


#### 5.1 QUAIS PERGUNTAS PODEM SER RESPONDIDAS COM O SISTEMA PROPOSTO?
 1. Consigo ter uma estimativa do preço do medicamento?<br>

<p>Consegue, sim. Utilizamos o PMVC (Preço Máximo Vendido ao Consumidor), disponibilizado pela Anvisa (Agência Nacional de Vigilância Sanitária), para indicar o preço máximo por qual cada medicamento pode ser vendido.</p><br>

2. Consigo acesso a informação se o medicamento precisa de receita?<br>

<p>Consegue. É informado, para cada medicamento, se é prescrição médica.</p><br>

3. Preciso pesquisar pelo sintoma que estou sentindo?<br>

<p>Não. Existem botões (links) de redirecionamento de páginas, e, portanto, ao clicar neles (cada um com seu respectivo sintoma), haverá o redirecionamento para a página que deseja, com os medicamentos do sintoma selecionado.</p><br>

4. Quanto à quantidade, terá muitos medicamentos?<br>

<p>Não. Para uma maior intuitividade, não encheremos a página de medicamentos, para que não fique desgastante.</p><br>

5. Consigo entrar em contato com os desenvolvedores para tirar dúvidas ou dar sugestões sobre o site?<br>

<p>Consegue, sim, afinal, nosso site está sendo feito para o público, e, portanto, precisamos da opinião de vocês para melhorarmos cada vez mais. Existe uma página de contato no site, através da qual será possível enviar mensagens a nós (desenvolvedores), para tirar dúvidas ou enviar sugestões.</p><br>

 

### 6 TABELA DE DADOS DO SISTEMA:
<br>
[Planilha com Dados - João Eid, Jonathan Castro e Raphael Branco.xlsx](https://github.com/branquitoRaph/template_projeto_integrador/files/9033655/Planilha.com.Dados.-.Joao.Eid.Jonathan.Castro.e.Raphael.Branco.xlsx)
<br>

 ### 7.MODELO CONCEITUAL<br>
    A) Utilizar a Notação adequada (Preferencialmente utilizar o BR Modelo 3)
    B) O mínimo de entidades do modelo conceitual pare este trabalho será igual a 4.
        * informe quais são as 3 principais entidades do sistema em densenvolvimento
<br>
![camed_conceitual](https://user-images.githubusercontent.com/108133362/177015282-1a020857-5ccd-4ded-b1a3-c69b6ae5d500.png)
<br>
#### 7.1 Descrição dos dados 
    [objeto]: [descrição do objeto]
    
    EXEMPLO:
    CLIENTE: Tabela que armazena as informações relativas ao cliente<br>
    CPF: campo que armazena o número de Cadastro de Pessoa Física para cada cliente da empresa.<br>

### 8	RASTREABILIDADE DOS ARTEFATOS<br>
        a) Historia de usuários vs protótipo (mockup)
        b) Protótipo vs Modelo conceitual
        (não serão aceitos modelos que não estejam em conformidade)
        c) Backlog (caso solicitado)

### 9	MODELO LÓGICO<br>
        a) inclusão do esquema lógico do banco de dados
        b) verificação de correspondencia com o modelo conceitual 
        (não serão aceitos modelos que não estejam em conformidade)

### 10	MODELO FÍSICO<br>
        a) inclusão das instruções de criacão das estruturas em SQL/DDL 
        (criação de tabelas, alterações, etc..) 
        
       
### 11	INSERT APLICADO NAS TABELAS DO BANCO DE DADOS<br>
        a) inclusão das instruções de inserção dos dados nas tabelas criadas pelo script de modelo físico
        (Drop para exclusão de tabelas + create definição de para tabelas e estruturas de dados 
 <br> + insert para dados a serem inseridos)
        b) Criar um novo banco de dados para testar a restauracao 
        (em caso de falha na restauração o grupo não pontuará neste quesito)
        c) formato .SQL
<br>
 #### 12.3 ANTEPROJETO VERSÃO 1
 
 Link para [Modelo de Anteprojeto](https://docs.google.com/document/d/1oeVS2CUffbSNYWxIWZFY_mX6E5ao_PHU/edit?usp=sharing&ouid=104104747195236161434&rtpof=true&sd=true)
