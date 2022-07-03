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

![pmc](https://user-images.githubusercontent.com/108133362/177018922-9a29dec7-e97a-44fd-9bd4-f2b64505ff1c.jpg)


<br>

### 4.Personas e Histórias de usuário<br>

![persona_jarula](https://user-images.githubusercontent.com/108133362/177020265-61c2f88f-eb84-4bba-92a9-e89deb54ff36.jpg)


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

![persona_pedro](https://user-images.githubusercontent.com/108133362/177020300-8c528851-42e9-437a-ae6b-212732fceee6.jpg)


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

![persona_sergio](https://user-images.githubusercontent.com/108133362/177020311-1a38b470-ef38-4372-816d-5a53253acd6e.jpg)


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


![Página Home(Principal)](https://user-images.githubusercontent.com/108133362/177021363-b107bfc3-a598-48ff-af28-6ece144c9e93.jpg)


[Arquivo PDF com o Protótipo completo](https://github.com/branquitoRaph/template_projeto_integrador/files/9033947/Joao.Eid.Jonathan.Castro.e.Raphael.Branco.-.Os.Dois.Prototipos.pdf)


<br>


#### 5.1 QUAIS PERGUNTAS PODEM SER RESPONDIDAS COM O SISTEMA PROPOSTO?


<br>

<ul>
 
  <li>Relatório sobre os Preços Máximos Vendido ao Consumidor (PMVC) dos medicamentos, dados estes, disponibilizados pela Anvisa (Agência Nacional de Vigilância Sanitária).</li>
  <li>Relatório quanto a necessidade de prescrição médica dos medicamentos, informando quais medicamentos precisam de prescrição médica e quais não precisam de prescrição médica.</li>
  <li>Relatório informando a data (período) em que as pessoas acessaram o sintoma, ou seja, nos pertindo analisar em qual período este sintoma é mais acessado.</li>
  <li>Relatório dos medicamentos, nos permitindo ver a quantidade de medicamentos para um determinado sintoma, para analisar se a página está boa em relação a quantidade de medicamentos (exemplo: se tiver muitos medicamentos em um determinado sintoma, pode causar uma poluição visual).</li>
  <li>Relatório das mensagens enviadas pelos usuários, podendo analisar se tivemos mais reclamações, sugestões ou dúvidas dos usuários.</li>
 
</ul>


<br>
 

### 6 TABELA DE DADOS DO SISTEMA:
<br>


![Planilha de Dados](https://github.com/branquitoRaph/template_projeto_integrador/blob/main/arquivos/Planilha%20com%20Dados%20-%20João%20Eid%2C%20Jonathan%20Castro%20e%20Raphael%20Branco.xlsx?raw=true "Planilha de Dados")


<br>

 ### 7.MODELO CONCEITUAL<br>
<br>    
<p><b>Três principais entidades:</b></p>
<p>MEDICAMENTO;</p>
<p>USUARIO;</p>
<p>SINTOMA</p>
<br>


![camed_conceitual](https://user-images.githubusercontent.com/108133362/177015666-007b501f-7019-4e36-afdb-e0c4c5d80a74.png)



<br>


#### 7.1 Descrição dos dados 

<br>

<p>MEDICAMENTO: Entidade que armazena as informações relativas aos medicamentos</p>
<p>idMedicamento: Identificador do medicamento (Chave Primária)</p>
<p>nomeMedicamento: Nome do medicamento</p>
<p>PMVC: Preço Máximo Vendido ao Consumidor do medicamento</p>
<p>necessarioReceita: Informa se o medicamento precisa ou não de prescrição médica</p>

<br>

<p>SINTOMA: Entidade que armazena as informações relativas aos sintomas</p>
<p>idSintoma: Identificador do sintoma (Chave Primária)</p>
<p>nomeSintoma: Nome do sintoma</p>

<br>

<p>USUARIO: Entidade que armazena as informações relativas aos usuários</p>
<p>idUsuario: Identificador do usuário (Chave Primária)</p>
<p>nomeUsuario: Nome do usuário</p>
<p>senha: Senha do usuário</p>
<p>dataNascimento: Data de nascimento do usuário</p>

<br>

<p>ENDERECO: Entidade que armazena as informações relativas aos endereços dos usuários</p>
<p>idEndereco: Identificador do endereço (Chave Primária)</p>
<p>numero: Número do endereço do usuário</p>

<br>

<p>MENSAGEM: Entidade que armazena as informações relativas as mensagens enviadas pelos usuários</p>
<p>idMensagem: Identificador da mensagem (Chave Primária)</p>
<p>descriMensagem: Conteúdo da mensagem</p>

<br>

<p>TIPO_CONTATO: Entidade que armazena os tipos de contatos existentes</p>
<p>idTipo: Identificador do tipo de contato (Chave Primária)</p>
<p>descriTipoContato: Descrição do tipo de contato</p>

<br>

<p>TIPO_LOGRADOURO: Entidade que armazena os tipos de logradouros existentes</p>
<p>idTipo_Logradouro: Identificador do tipo de logradouro (Chave Primária)</p>
<p>descriTipo_Logradouro: Descrição do logradouro</p>

<br>

<p>BAIRRO: Entidade que armazena as informações relativas de um bairro</p>
<p>idBairro: Idenntificador do bairro (Chave Primária)</p>
<p>descriBairro: Nome do bairro</p>

<br>

<p>MUNICIPIO: Entidade que armazena as informações relativas de um município</p>
<p>idMunicipio: Identificador do município (Chave Primária)</p>
<p>descriBairro: Nome do município</p>

<br>

<p>ESTADO: Entidade que armazena as informações relativas de um Estado</p>
<p>idEstado: Identificador do Estado (Chave Primária)</p>
<p>descriEstado: Nome do Estado</p>

<br>

<p>COMPLEMENTO: Entidade que armazena as informações relativas de um complemento do endereço de um usuário</p>
<p>idComplemento: Identificador do complemento (Chave Primária)</p>
<p>descriComplemento: Descrição do complemento do endereço do usuário</p>

<br>

<p>SINTOMA_MEDICAMENTO: Relacionamento entre as entidades SINTOMA e MEDICAMENTO</p>

<br>

<p>SINTOMA_USUARIO: Relacionamento entre as entidades SINTOMA e USUARIO</p>
<p>dataSintoma: Data em que o usuário teve o sintoma</p>

<br>

<p>USUARIO_ENDERECO: Relacionamento entre as entidades USUARIO e ENDERECO</p>

<br>

<p>ENDERECO_COMPLEMENTO: Relacionamento entre as entidades ENDERECO e COMPLEMENTO</p>

<br>

<p>USUARIO_MENSAGEM: Relacionamento entre as entidades USUARIO e MENSAGEM</p>

<br>

<p>USUARIO_TIPO_CONTATO: Relacionamento entre as entidades USUARIO e TIPO_CONTATO</p>
<p>descricao: Descricao do tipo de contato do usuário</p>

<br>

<p>ENDERECO_TIPO_LOGRADOURO: Relacionamento entre as entidades ENDERECO e TIPO_LOGRADOURO</p>

<br>

<p>ENDERECO_BAIRRO: Relacionamento entre as entidades ENDERECO e BAIRRO</p>

<br>

<p>ENDERECO_MUNICIPIO: Relacionamento entre as entidades ENDERECO e MUNICIPIO</p>

<br>

<p>MUNICIPIO_ESTADO: Relacionamento entre as entidades MUNICIPIO e ESTADO</p>

<br>

### 8	RASTREABILIDADE DOS ARTEFATOS<br>
        a) Historia de usuários vs protótipo (mockup)
<br>


[Rastreabilidade_ HUs X Protótipo.xlsx](https://github.com/branquitoRaph/template_projeto_integrador/files/9033741/Rastreabilidade_.HUs.X.Prototipo.xlsx?raw=true "Rastreabilidade: HUs X Protótipo")


<br>
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
