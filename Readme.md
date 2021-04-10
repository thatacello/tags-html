Uma das tags que mais utilizamos em nossos códigos é a <div>, é bem simples explicar o porquê, ela é uma tagde container em que é possível armazenar conteúdos diversos  da  nossa  página.  

Sendo  assim,  sempre  que  quisermos  juntar  e  organizar conteúdos podemos colocá-los dentro de novos containers.Tudo bem usar a <div> como container, mas,às vezes,temos tantas divs em nosso  código  que, na  hora  de  fazer  uma  pequenaalteração, o  desenvolvedor precisará de um tempo para entender como o HTML foi estruturado, praticamente tudo fica dentro de <div>, e muitas vezes, divs dentro de outras divs.

Mas como podemos melhorar o código HTML para que ele possa ter um pouco mais de sentido, ficando,assim,mais fácil de ser entendido? A resposta para essa pergunta é a semântica.      Segundo o dicionário Aulete Digital, http://www.aulete.com.br/, um dos significados para semântica é: “Estudo da relação dos  signos  com  aquilo  que  eles  significam”.  

Esse  conceito  foi  utilizado  pelos desenvolvedores  que  estavam  trabalhando  na  nova  versão  do  HTML,  o  HTML5,  e com isso criaram as chamadas tags semânticas.

A  ideia é  a  mesma  da  tag  <div>,  as  tags  semânticas  são  containers  com  as mesmas características das divs, só que agora elas possuem uma relevância que não existia antes, trazendo,assim,grandes benefícios:

- HTML semântico permiteum significado maior para a página, pois agora as tags têm uma relevância maior.

- HTML   semântico   fornece   mais   acessibilidade,pois permitiráque tecnologias  assistivas possam  ter  um  melhor  acesso  ao  conteúdo  da página.

- HTML semântico melhorará a visibilidade de seu site em uma busca feita por sites como o Google.

- HTML semântico deixará seu código mais claro, facilitando assim as futuras manutenções.

- HTML  semântico  ajuda  os  navegadores  na  renderização  da  página,pois indicam que tipo de conteúdo temos naquela parte do código.

#Header

Define o cabeçalho para a página ou para outros containers, indicando assim o início de um elemento ou seção. É muito usado para a inserção de logotipos, áreas de navegação e campos para busca. Em um mesmo documento,podemos ter vários elementos <header>.

#Main

Define o container que receberá o conteúdo principal da sua página. Essa tag deverá ser única, ou seja, não deveremos ter mais de um elemento <main> no mesmo documento HTML.

#Section

Define uma ou mais seções em nossa página. Uma seção deve abordar algum determinado  conteúdo  ou  assunto,  e  sempre  possuir  um  título.  Em  um  mesmo documento,podemos  ter  vários  elementos  <section>,  mas  tome  cuidado  para  não usar esse elemento como um container mais genérico, para isso,usamos a tag <div>.

#Article

Define um container de conteúdo mais específico, independente,e que pode ser  reutilizável  em  outras  páginas  sem  perder  o  seu  contexto.  Em  um  mesmo documento podemos ter vários elementos <article>.

#Aside

Define um container de conteúdo separado, mas vinculado a um determinado assunto ou conteúdo. Na maioria das vezes,esse elemento é posicionado ao lado do conteúdo ao  qual ele  foi  associado,  como  uma  barra  lateral.  Em  um  mesmo documento podemos ter vários elementos <aside>.

#Nav

Define  um  container  que  deve  agruparos  links  criados  pela  tag  <a>.  Não  é necessário que todos os links estejam dentro de um container <nav>, apenas aqueles que formarem o sistema de navegação de sua aplicação. A tag <nav> é comumente encontrada  em  elementos  <header>,  mas  também  podem  ser  inseridos  em  outros containers  existentes  na  página.  Em  um  mesmo  documento,podemos  ter  vários elementos <nav>.

#Figure / Figcaption

A  tag<figure>  define  um  container  que  deve  agrupar  imagens  existentes  na página. Podemos utilizar a tag <figcaption>,que definirá uma legenda a ser usada por um grupo de imagens. Também é possível utilizar,em cada imagem,um <figcaption> diferente.

#Footer

Define  o rodapé  para  a  página  ou  para  outros  containers, indicando  assim  o final  de  um  elemento  ou  seção.  Em  um  mesmo documento,podemos  ter  vários elementos <footer>.

#Em

A tag<em> é utilizada para darmos uma ênfase maior a uma palavra, ou parte de um texto. Dessa forma, o conteúdo que estiver no seu interior será entendido como mais relevante.

#Strong

A tag <30trong> é utilizada para definir que um texto, ou parte dele, é muito importante. O conteúdo que estiver em seu interior ficará em negrito.

#Time

A  tag  <time>  é  utilizada  para  definir  uma  hora  ou  data.  Seu  uso  é  muito interessante,pois  possibilita  futuros  agendamentos  para  eventos.  Possui  o  atributo datetime,que receberá a data desejada.
<p>
Embarque: <time datetime="2021/12/02">02/12/2021</time>
</p>

#Address

A tag <address> é utilizada para definir as informações de contato. Pode ser usada para: endereço, telefone, e-mail, url etc.