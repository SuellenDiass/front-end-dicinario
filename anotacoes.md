 Anotações feitas durante o curso:
 
 Criando o efeito accordion
 O accordion nada mais é do que um comportamento onde podemos abrir e ocultar informações do site
 Estrutura:
 <details>
    <summary> titulo</summary>
    <p>Descriçao de texto</p>
 </details>

 <blockquote> - Tag que nos permite criar blocos de marcação indicando que aquele texto é uma citação, ajudando o navegador a entender o que é aquilo, semanticamente falando. Junto com o blockquote há também uma outra tag na qual podemos utilizar que é o <q> 

<q> -  Nada mais é do que o quote, com ele costumamos usar para adicionar aspas em pequenas frases. 

A importação do javaScript de ser feito antes do fechamento da tag <body>

LISTA DAS PRINCIPAIS PROPRIEDADES E ATRIBUTOS DO JS REVISADAS NESTA AULA: 


Condicionais (if e else)
“Se” a regra for verdadeira retorna um resultado, “se não” retorna outro resultado

Operadores Lógicos ( && - II)
&& significa “e”, ele verifica as duas regras
II significa “ou”, ele define se a regra vai funcionar para um ou outro

Conhecendo o getElementById (document.getElementById)
Acessa um elemento que tenha um determinado id

Valor e dado do tipo string
String significa que é do tipo texto

Operadores relacionais
Servem para comparar,
== significa “igual”, compara se um valor é igual ao outro
!= significa “diferente”, compara se um valor é diferente do outro

Método alert()
Exibe um alerta, dispara um pop-up para informar/alertar algo

Listener (Método AddEventListener)
Para trabalhar com eventos, como o de “click”, ele captura esse evento e pode executar uma ação a partir disso

Funções no Javascript (function)
É uma função, aglomerado de regras e comandos que vamos determinar para a nossa aplicação

Variáveis são os locais onde vamos armazenar as informações na memória e quando precisamos conseguimos acessá-las para obter ou alterar alguma informação contida dentro dela. Sempre que você precisar criar uma estrutura padrão de uma variável, terá que declará-la usando o var, dar um nome a ela (geralmente usamos com letra minúscula e maiúscula, no qual chamamos de camelCase) e depois atribuir um valor a essa variável.
Estrutura de uma variável: var nomeDaVariavel = valor

Array é quando precisamos armazenar muitos valores numa única variável. Para isso, utilizamos os colchetes. 
Estrutura de uma variável com array : var nomeDaVariavel = [valor]

O objeto permite que a gente adicione e agrupe informações de forma mais categórica, facilitando a organização dessas informações.
Estrutura de uma variável com objeto: var nomeDaVariavel = {chave:valor}

 Estrutura de repetição

 O for nos permite criar repetições de um determinado ciclo, seja percorrendo uma array ou objeto. 
 for(){}
 É indicado para criarmos iteração em objetos. Dentro do for() atribuímos uma variável que irá receber as informações referentes aos objetos que iremos percorrer.

 Estrutura de um laço de repetição com in : for(var item in obj){...} EX.:

  Uma variável camiseta no qual armazenará um objeto(modelos) e a partir dessa variável acessá-la usando o for(), que percorrerá por esse objeto, verificando todas as informações e retornando elas para a nossa tela trazendo as informações da variável camiseta como manga, estampa, tamanho.
  
  var camiseta = {manga:"curta", estampa: "lisa", tamanho:"grande"};
  for( item in camiseta){
   console.log(item += camiseta[item]);
  }

  Para colocar uma informação do html dentro do document no javaScript : 
  document.getElementById("id").innerHTMl="<etiqueta></etiqueta> ou seja tag html"
  Informa o documento que quer pegar o id dentro do arquivo html e dentro desse id quero inserir o html

  O innerHTML é uma propriedade que define ou retorna o conteúdo HTML de um elemento.
  propriedade geralmente é escrita no DOM (Document Object Model), por meio do JavaScript.
  Desse modo, é usada para adiciona e modificar trechos de código HTML via JavaScript.

  Principais comandos Git

  git init

   git clone <remote-repo-address>

   git add <file.txt>

   git commit –m “Message”

   git status

   git push <remote-name> <branch-name>

   git checkout -b <branch-name>

   git pull

   git remote

   git status

   git reset 

   git merge <branch-name>

   
   
