# TRABALHO 01:  Cartão do torcedor
Trabalho desenvolvido durante a disciplina de BD1, cursada em 2017/2 no IFES.

# Sumário

### 1. COMPONENTES<br>
Gustavo Graciliano: gustavo.graciliano@gmail.com<br>
Pedro Cruz: pedrocruzns@gmail.com<br>
Wagner Maurício: wmauriciu@gmail.com<br>

### 2.INTRODUÇÃO E MOTIVAÇAO<br>

Pela primeira vez na história das Copas do Mundo de futebol ter um ingresso<br>
em mãos não será o suficiente para entrar no estádio. As autoridades russas vão <br>
barrar qualquer um que não tiver também uma credencial. Trata-se da Fan ID <br>
(Identidade do Fã, em português).<br>
<br>
O documento será confeccionado gratuitamente para o torcedor que possuir bilhetes.<br>
Para isso, será necessário preencher um cadastro no site (www.fan-id.ru) ou <br>
comparecer pessoalmente a um dos centros de distribuição das 11 cidades-sedes.<br>
O espectador só tem acesso ao formulário após receber da Fifa um código de identificação individual.<br>
As entradas para o Mundial deverão ser comercializadas a partir de agosto.<br>
<br>
O objetivo das autoridades russas é ter controle total sobre quem entra e sai das<br>
arenas e evitar que hooligans já fichados pela polícia na Rússia e em outros países<br>
possam comparecer aos jogos.
<br>
<br>
Parte da matéria <a href="http://www1.folha.uol.com.br/esporte/2017/06/1891498-russia-cria-cartao-de-torcedor-para-afastar-hooligans-da-copa.shtml">Rússia cria cartão de torcedor para afastar hooligans da Copa</a>, <br>
retirada do site Folha de São Paulo.
<br>
<br>

O gosto pelo futebol nos trouxe até aqui. Mais do que isso, o desejo de frequentar um estádio<br>
sem se preocupar com a possibilidade de brigas entre torcidas organizadas, explosões de bombas ou rojões,<br>
uso do gás de pimenta feito pela polícia para controlar os torcedores mais exaltados ou <br>
aquele torcedor sem noção que invade o campo e atrapalha o espetáculo.<br>
<br>
A vontade de ver o estádio de futebol como um lugar tranquilo para ser frequentado<br>
pela família toda, com sentimento de segurança.<br>

### 3.MINI-MUNDO<br>
<b>O sistema em si:</b><br>
O sistema, apesar de estar vinculado ao acesso de torcedores ao estádio de<br>
futebol, não tem relação com ingresso.<br>
Os serviços serão oferecidos para o governo e terão dois usuários,<br>
os torcedores e as empresas gestoras dos estádios. O primeiro usará <br>
para se cadastrar e poder ter o acesso ao estádio e o segundo usará <br>
para ter o controle de acesso de torcedores e o bloqueio daquele torcedor<br>
que foi proibido judicialmente de frequentar o estádio.<br>
<br>

<b>Banco de dados:</b><br>
O banco de dados terá o cadastro de todos os torcedores que frequentarem <br>
os estádios pelo menos uma vez. Dentro dos campos com as informações <br>
terá o status com a informação se ele está ou não liberado para frequentar o estádio.<br>
Esse status será verificado com a lista de torcedores punidos fornecida pelo TJ de cada estado.<br>
<br>

<b>Aplicação:</b><br>
O usuário poderá fazer o seu próprio cadastro pelo site ou realizar o cadastro <br>
no estádio antes da partida. No cadastro será pedido os dados pessoais do torcedor como por exemplo:<br>
nome, rg, cpf, endereço e uma senha para acesso ao site.<br>
Para a verificação da liberação do torcedor o mesmo recepcionista que irá validar<br>
os ingressos irá validar o ID do torcedor.<br>
O link abaixo mostra a lista da FPF (Federação Paulista de Futebol) de torcedores que foram<br>
julgados e proibidos pela justiça de frequentar os estádios, atualizada pela última vez <br>
dia 03/08/2017. Nela tem as mesmas informações fornecidas pelo torcedor durante o cadastro <br>
além da data de início da punição e data de término da mesma.<br>
<br>
<a href="http://2016.futebolpaulista.com.br/ListadeTorcedoresPunidos.pdf" target="_blank">Lista de torcedores punidos pela FPF</a>
<br>
<br>
### 4.RASCUNHOS BÁSICOS DA INTERFACE (MOCKUPS)<br>

![Alt text](https://github.com/cartaodotorcedor/trab01/blob/master/inicio.png?raw=true "Title")
<br>
![Alt text](https://github.com/cartaodotorcedor/trab01/blob/master/inicio.png?raw=true "Title")
<br>
![Alt text](https://github.com/cartaodotorcedor/trab01/blob/master/cadastro.png?raw=true "Title")
<br>
![Alt text](https://github.com/cartaodotorcedor/trab01/blob/master/meuperfil.png?raw=true "Title")
<br>
![Alt text](https://github.com/cartaodotorcedor/trab01/blob/master/quemsomos.png?raw=true "Title")
<br>
![Alt text](https://github.com/cartaodotorcedor/trab01/blob/master/manualdobomtorcedor.png?raw=true "Title")
<br>

#### 4.1 TABELA DE DADOS DO SISTEMA:
    a) Esta tabela deve conter todos os atributos do sistema e um mínimo de 10 linhas.
    b) Esta tabela tem a intenção de simular um relatório com todos os dados que serão armazenados 
    e deve ser criada antes do modelo conceitual
    c) Após criada esta tabela não deve ser modificada, pois será comparada com a tabela final na conclusão do trabalho
   
   
   <br>
   Observar o arquivo ![Alt text](https://github.com/cartaodotorcedor/trab01/blob/master/Mapeamento%20entidades.xlsx?raw=true "Title") na raiz do projeto.
    
    
#### 4.2 QUAIS PERGUNTAS PODEM SER RESPONDIDAS COM O SISTEMA PROPOSTO?
    a) O sistema proposto poderá fornecer quais tipos de relatórios e informações?<br>
    
    b) Crie uma lista com os 10 principais relatórios que poderao ser obtidos por meio do sistema proposto!<br>
    1. Torcedores proibidos de frequentar estádios no Brasil todo.<br>
    2. Torcedores proibidos de frequentar estádios em determinado estado.<br>
    3. Torcedor com maior número de punições.<br>
    4. Time com maior número de torcedores punidos.<br>
    5. Time com menor número de torcedores punidos.<br>
    6. Quantidade de torcedores punidos que consomem bebida alcóolica.<br>
    7. Quantidade de torcedores punidos que fazem parte de torcida organizada.<br>
    8. Idade média dos torcedores punidos.<br>
    9. Quais torcedores estão próximos do fim da punição.<br>
    10. Qual é o estádio preferido em cada estado.<br>
    
        
## Marco de Entrega 01 em: (Data definida no cronograma)<br>

### 5.MODELO CONCEITUAL<br>
    A) NOTACAO ENTIDADE RELACIONAMENTO 
        * Para nosso prótótipo limitaremos o modelo conceitual nas 6 principais entidades do escopo
        * O protótipo deve possui no mínimo duas relações N para N
        * o mínimo de entidades do modelo conceitual será igual a 5
        
![Alt text](https://github.com/discipbd1/trab01/blob/master/sample_MC.png?raw=true "Modelo Conceitual")
    
    B) NOTACAO UML (Caso esteja fazendo a disciplina de analise)
    C) QUALIDADE 
        Garantir que a semântica dos atributos seja clara no esquema
        Criar o esquema de forma a garantir a redução de informação redundante, possibilidade de valores null, 
        e tuplas falsas
    
        
    
#### 5.1 Validação do Modelo Conceitual
    [Grupo01]: [Nomes dos que participaram na avaliação]
    [Grupo02]: [Nomes dos que participaram na avaliação]

#### 5.2 DECISÕES DE PROJETO
    [atributo]: [descrição da decisão]
    
    EXEMPLO:
    a) Campo endereço: em nosso projeto optamos por um campo multivalorado e composto, pois a empresa 
    pode possuir para cada departamento mais de uma localização... 
    b) justifique!

#### 5.3 DESCRIÇÃO DOS DADOS 
    [objeto]: [descrição do objeto]
    
    EXEMPLO:
    CLIENTE: Tabela que armazena as informações relativas ao cliente<br>
    CPF: campo que armazena o número de Cadastro de Pessoa Física para cada cliente da empresa.<br>


### 6	MODELO LÓGICO<br>
        a) inclusão do modelo lógico do banco de dados
        b) verificação de correspondencia com o modelo conceitual 
        (não serão aceitos modelos que não estejam em conformidade)

>## Marco de Entrega 02 em: (Data definida no cronograma)<br>

### 7	MODELO FÍSICO<br>
        a) inclusão das instruções de criacão das estruturas DDL 
        (criação de tabelas, alterações, etc..)
          
        
### 8	INSERT APLICADO NAS TABELAS DO BANCO DE DADOS<br>
#### 8.1 DETALHAMENTO DAS INFORMAÇÕES
        a) inclusão das instruções de inserção dos dados nas tabelas criadas pelo script de modelo físic
        b) formato .SQL

#### 8.2 INCLUSÃO DO SCRIPT PARA CRIAÇÃO DE TABELA E INSERÇÃO DOS DADOS
        a) Junção dos scripts anteriores em um único script 
        (create para tabelas e estruturas de dados + dados a serem inseridos)
        b) Criar um novo banco de dados para testar a restauracao 
        (em caso de falha na restauração o grupo não pontuará neste quesito)
        c) formato .SQL
#### 8.3 INCLUSÃO DO SCRIPT PARA EXCLUSÃO DE TABELAS EXISTENTES, CRIAÇÃO DE TABELA NOVAS E INSERÇÃO DOS DADOS
        a) Junção dos scripts anteriores em um único script 
        (Drop table + Create de tabelas e estruturas de dados + dados a serem inseridos)
        b) Criar um novo banco de dados para testar a restauracao 
        (em caso de falha na restauração o grupo não pontuará neste quesito)
        c) formato .SQL


### 9	TABELAS E PRINCIPAIS CONSULTAS<br>
    OBS: Incluir para cada tópico as instruções SQL + imagens (print da tela) mostrando os resultados.<br>
#### 9.1	CONSULTAS DAS TABELAS COM TODOS OS DADOS INSERIDOS (Todas) <br>
#### 9.2	CONSULTAS DAS TABELAS COM FILTROS WHERE (Mínimo 4)<br>
#### 9.3	CONSULTAS QUE USAM OPERADORES LÓGICOS, ARITMÉTICOS E CAMPOS RENOMEADOS (Mínimo 6)
     a) Criar no mínimo 2 com operadores lógicos
     b) Criar no mínimo 2 com operadores aritméticos
     c) Criar no mínimo 2 com operação de renomear campo
#### 9.4	CONSULTAS QUE USAM OPERADORES LIKE (Mínimo 4) <br>

>## Marco de Entrega 03 em: (Data definida no cronograma)<br>
    
#### 9.5	ATUALIZAÇÃO E EXCLUSÃO DE DADOS (Mínimo 6)<br>
#### 9.6	CONSULTAS COM JUNÇÃO E ORDENAÇÃO (Mínimo 6)<br>
        a) Uma junção que envolva todas as tabelas possuindo no mínimo 3 registros no resultado
        b) Outras junções que o grupo considere como sendo as de principal importância para o trabalho
#### 9.7	CONSULTAS COM GROUP BY E FUNÇES DE AGRUPAMENTO (Mínimo 6)<br>
#### 9.8	CONSULTAS COM LEFT E RIGHT JOIN (Mínimo 4)<br>
#### 9.9	CONSULTAS COM SELF JOIN E VIEW (Mínimo 6)<br>
        a) Uma junção que envolva Self Join
        b) Outras junções com views que o grupo considere como sendo de relevante importância para o trabalho
#### 9.10	SUBCONSULTAS (Mínimo 3)<br>
### 10	ATUALIZAÇÃO DA DOCUMENTAÇÃO DOS SLIDES PARA APRESENTAÇAO FINAL (Mínimo 6 e Máximo 10)<br>
### 11	TUTORIAL COMPLETO DE PASSOS PARA RESTAURACAO DO BANCO E EXECUCAO DE PROCEDIMENTOS ENVOLVIDOS NO TRABALHO PARA OBTENÇÃO DOS RESULTADOS<br>
        a) Outros grupos deverão ser capazes de restaurar o banco 
        b) executar todas as consultas presentes no trabalho
        c) executar códigos que tenham sido construídos para o trabalho 
        d) realizar qualquer procedimento executado pelo grupo que desenvolveu o trabalho
        
### 12   DIFICULDADES ENCONTRADAS PELO GRUPO<br>
### 13   TRABALHO DE MINERAÇÃO DE DADOS
        a) captura das informaçõs
        b) integração com banco de dados em desenvolvimento
        c) atualização da documentação do trabalho incluindo a mineração de dados
        
### 13  FORMATACAO NO GIT: https://help.github.com/articles/basic-writing-and-formatting-syntax/

### 14 Backup completo do banco de dados postgres 
    a) deve ser realizado no formato "backup" 
        (Em Dump Options #1 Habilitar opções Don't Save Owner e Privilege)
    b) antes de postar o arquivo no git o mesmo deve ser testado/restaurado por outro grupo de alunos/dupla
    c) informar aqui o grupo de alunos/dupla que realizou o teste.
    
>## Marco de Entrega 04/Entrega Final em: (Data definida no cronograma)<br>
    
### OBSERVAÇÕES IMPORTANTES

#### Todos os arquivos que fazem parte do projeto (Imagens, pdfs, arquivos fonte, etc..), devem estar presentes no GIT. Os arquivos do projeto vigente não devem ser armazenados em quaisquer outras plataformas.
1. Caso existam arquivos com conteúdos sigilosos, comunicar o professor que definirá em conjunto com o grupo a melhor forma de armazenamento do arquivo.

#### Todos os grupos deverão fazer Fork deste repositório e dar permissões administrativas ao usuário deste GIT, para acompanhamento do trabalho.

#### Os usuários criados no GIT devem possuir o nome de identificação do aluno (não serão aceitos nomes como Eu123, meuprojeto, pro456, etc). Em caso de dúvida comunicar o professor.


Link para BrModelo:<br>
http://sis4.com/brModelo/brModelo/download.html
