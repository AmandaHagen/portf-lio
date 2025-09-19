link para o projeto no figma.
https://www.figma.com/design/4EKKCbr5rS93RWP7kRjXIz/Portfolio---Curso-1?node-id=0-1&p=f&t=hRwkUPd9aAf17yo6-0




projeto 3 figma mobile:https://www.figma.com/design/NrzJacC887svMVfF9oC2jM/Portfolio-Projeto-2?node-id=8-2&p=f&t=8MSFJS7wZOgJTpgT-0

https://www.figma.com/design/NrzJacC887svMVfF9oC2jM/Portfolio-Projeto-2?node-id=1-47&t=XvC0bxs0Oj1UIOs0-0

Amanda Hagen é desenvolvedora front-end, empresária e barbeira — uma mulher que une criatividade, técnica e estilo em tudo o que faz. No universo do código, domina HTML, CSS e JavaScript com precisão, criando interfaces modernas, acessíveis e cheias de personalidade. Como empresária, lidera com visão e coragem, transformando ideias em negócios que inspiram. E na barbearia, sua arte vai além da tesoura: ela cria experiências, conecta pessoas e eleva a autoestima de quem passa por sua cadeira. Amanda é movida por desafios e pela vontade de aprender sempre mais. Seu portfólio reflete sua essência: ousado, elegante e funcional. Ela acredita que tecnologia e beleza podem andar juntas, e prova isso todos os dias com seu trabalho. Seja no teclado ou na navalha, Amanda entrega excelência. Sua trajetória é marcada por dedicação, inovação e autenticidade. Uma mulher que não cabe em rótulos, mas que redefine cada espaço que ocupa com talento e paixão.

Projeto figma 


<!-- DICAS!!!!! -->

Antes de rodar:
Certifique-se de estar dentro da pasta do projeto no terminal:
cd caminho/para/sua/pasta/portf-lio

simplesmente atualizar os arquivos com o comando:
git pull origin main
Explicando o comando:
git pull: busca as alterações mais recentes do repositório remoto.

origin: é o nome padrão do repositório remoto.

main: é o nome da branch principal (no seu caso, é mesmo main).

Se você tiver feito alterações locais e ainda não comitou, o Git pode pedir que você resolva conflitos ou salve seu progresso antes de puxar as atualizações. Quer ajuda com isso também?

Posso te mostrar como verificar o status do seu repositório ou como fazer um commit antes de puxar.


<!-- --------------------------------------->

Unidade de medida:
medidas absolutas: 
medid as relativas: Existem diversas medidas relativas: em, ex, ch, rem, vw, vh, vmin, vmx e % (porcentagem).
O MAIS INDICADO É O REM: é uma medida relativa que vai usar o root-element, que é o elemento raiz, ou seja, a página HTML. É o que a pessoa que está utilizando a página definiu no navegador.
Nessa escala utiliza-se o valor mais recomendado pelos navegadores, que é de 16, então 16px equivale a 1rem e 32px equivale a 2rem.
EXEMPLO:
No código está marcado o tamanho da fonte como 36px, precisamos alterar para rem. E para converter os 36px, nós dividimos esse valor por 16px. Ao dividirmos 36 por 16, temos como resultado 2,25. Então 36px equivale a 2,25rem. Número quebrado, mas até o 0,25 é válido usar. Caso fosse um número como 2,1752, poderíamos arredondar.

.apresentacao__conteudo__titulo {
    font-size: 2.25rem;
    font-family: var(--fonte-primaria);
}

Usando o crlt + f e digitando: Ex: font-size (assim fica mais fácil trocar as informações)

Artigo sobre medidas (LER): https://www.alura.com.br/artigos/guia-de-unidades-no-css
Ver a documentação: https://www.w3schools.com/cssref/css_units.php


<!-- RESPONSIVIDADE: -->
<!-- MEDIA QUERIES --> documentação: https://developer.mozilla.org/pt-BR/docs/Web/CSS/CSS_media_queries/Using_media_queries

Media Queries que garante que se a tela tiver um tamanho máximo ou mínimo terá a aplicação do estilo que determinarmos.
Como fazer: Declarar qual será nossa condição, ou seja, a largura máxima de tela para começarmos a utilizar os estilos que iremos definir, @media (),entre parenteses. Esses parênteses representam uma condição, nós verificamos se o que tem dentro deles é verdadeiro. Então se escrevermos um max-width: 1200px, se a tela tiver uma largura menor que isso, será aplicado o que está dentro das chaves. Abrir e fechar chaves ({}) e tudo que colocarmos dentro delas, sejam as classe ou o h1 só vai mudar quando essa função for verdadeira.

um exemplo de max-width, ou seja, o tamanho máximo:

@media (max-width: 1200px) {
    .apresentacao {
        flex-direction: column-reverse ;
    }
}
No exemplo acima. Se o tamanho máximo for 1200px, que deve ter feito sentido para esse projeto, abriu chaves ({) e começou a adicionar a classe. Informamos que se for até determinado valor, aplicaremos um tipo diferente de estilos, com a apresentação, tamanho da fonte e padding diferentes, podemos mudar até a cor, então podemos informar que se for para Mobile queremos outra cor de fundo.
É possível definir um tamanho de tela para o celular, outro para o tablet e deixar a “padrão” para o desktop.
Exemplo:

Podemos definir uma largura máxima de “480px” para o celular: @media (max-width: 480px), e em outra media query definir uma largura máxima de “800px” para os tablets: @media (max-width: 800px), e então atribuímos os ajustes necessários dentro de cada media query, dessa forma teremos nosso site 100% responsivo.

Podemos também definir intervalos para os tamanhos de telas com um único media query, atribuímos o valor mínimo e depois o valor máximo separando ele pelo atributo and, veja: @media (min-width: 480px ) and (max-width: 800px), nesse caso os estilos serão aplicados em telas de no mínimo “480px” e de no máximo “800px”.

Utilizar width: 100% dentro de um media query para telas menores é uma prática comum e eficaz para garantir que a seção "apresentação conteúdo" ocupe toda a largura disponível na tela, proporcionando uma melhor experiência em dispositivos móveis. Isso garante que o conteúdo se ajuste adequadamente, evitando quebras de layout e facilitando a leitura. Continue praticando e explorando as possibilidades do design responsivo!

<!-- BREAK POINTS --> Pontos de quebra do layout, os famosos Break Points



<!--  !!!!!!!!!FAZER O EXERCÍCIO - MEDIA QUERIES!!!!! --><!--  !!!!!!!!!FAZER O EXERCÍCIO MEDIA QUERIES!!!!! -->
<!-- !!!!!!!!!!!FAZER O EXERCÍCIO - Ajustando a largura!!!!!!!!!! -->




RESPONSIVIDADE E GITHUB
Leituras:
https://github.com/alura-cursos/readme-template ler mais sobre Markdown
https://www.alura.com.br/artigos/como-trabalhar-com-markdown aprender mais sobre o Readme, ver exemplos e criar um do zero,
https://github.com/vanessametonini/aluramidi-curso/blob/master/README.md Readme do projeto Alura Midi do curso de Javascript
https://github.com/alura-cursos/android-com-kotlin-personalizando-ui/blob/master/README.md Readme do projeto android com kotlin do curso de android

lista de referências para você se aprofundar nos estudos, aprimorar seus conhecimentos e adquirir novas habilidades.
https://www.alura.com.br/artigos/guia-de-unidades-no-css oferece um guia completo sobre as unidades de medida no CSS
https://dev.to/lixeletto/entendendo-unidades-css-e-quando-utiliza-las-3ecc oferece uma visão ampla sobre unidades absolutas e relativas no CSS, explicando como elas funcionam e em quais situações devem ser utilizadas para um design responsivo.
https://dev.to/loresgarcia/unidades-de-medida-no-css-escolhendo-a-melhor-opcao-para-cada-caso-3jh9 discute como escolher a unidade de medida mais apropriada para cada situação no CSS, analisando unidades comuns como pixels, porcentagem, em, rem, vh e vw.
https://dev.to/mbthales/pt-br-unidades-relativas-rem-e-em-4d8j  foca nas unidades relativas rem e em, explicando suas diferenças e importância para criar um design responsivo
https://dev.to/gabrlcj/tecnica-para-voce-mudar-de-pixels-px-para-rem-2626 oferece uma explicação prática sobre como mudar de pixels para rem em CSS
https://cursos.alura.com.br/forum/topico-importancia-das-unidades-relativas-em-e-rem-257614  discute a importância do uso de unidades relativas como "em" e "rem" para criar layouts responsivos
https://www.origamid.com/projetos/flexbox-guia-completo/ Flexbox é uma técnica essencial no design responsivo
https://www.casadocodigo.com.br/products/livro-web-mobile?_pos=1&_sid=295b6578a&_ss=r livro da Editora Casa do Código oferece uma visão teórica e prática sobre design responsivo. Abrange a adaptação de imagens, textos e outros elementos para diferentes tamanhos de tela.
https://www.alura.com.br/podcast/tendencias-no-front-end-2022-hipsters-ponto-tech-286-a1368 discute tendências atuais e futuras do CSS e design responsivo, incluindo técnicas para adaptar elementos web a diferentes dispositivos.
https://www.alura.com.br/artigos/css-guia-do-flexbox  fundamentos do CSS Flexbox para alinhamento e posicionamento
https://developer.mozilla.org/pt-BR/docs/Learn_web_development/Core/CSS_layout/Flexbox artigo do MDN detalha como o Flexbox provê ferramentas para a criação de layouts complexos e flexíveis, que eram historicamente desafiadores com o CSS.
https://triangulo.dev/posts/guia-completo-flexbox/ guia explica que o Flexbox é um módulo do CSS criado para facilitar a vida de quem precisa criar layouts na web, controlando tamanho, alinhamento e distribuição de elementos.
https://www.freecodecamp.org/portuguese/news/tutorial-de-media-queries-do-css-resolucoes-padrao-breakpoints-do-css-e-tamanhos-de-telefone/ Este artigo aborda o Design Responsivo na Web e o papel crucial das media queries do CSS neste contexto. 
https://www.alura.com.br/artigos/como-colocar-projeto-no-ar-com-github-pages guia abrangente sobre como hospedar um projeto usando o GitHub Pages. Ele explica os conceitos de hospedagem, o que é o GitHub Pages, e o processo passo a passo para colocar seu projeto no ar, incluindo informações sobre como trabalhar com arquivos HTML, CSS e JavaScript.
https://docs.github.com/pt/get-started/start-your-journey/creating-an-account-on-github Este guia oficial do GitHub explica como criar uma conta pessoal gratuita no GitHub. Ele detalha os passos para se inscrever, verificar seu endereço de e-mail e oferece dicas para começar a explorar os conceitos básicos do GitHub, como repositórios, ramificações, commits e solicitações de pull. Também é recomendado configurar a autenticação de dois fatores (2FA) para segurança adicional.
https://www.alura.com.br/artigos/criando-repositorio-remoto-github explica os fundamentos do GitHub, ensinando como criar e gerenciar repositórios. É uma leitura ideal para quem está começando e quer entender melhor como funcionam os repositórios no GitHub.
https://www.alura.com.br/artigos/escrever-bom-readme Este artigo aborda os conceitos básicos do Markdown, a linguagem de formatação usada no GitHub para criar READMEs esteticamente agradáveis e informativos. É útil para quem deseja melhorar a apresentação dos seus projetos.


<!-- https://portfolio-five-navy-93.vercel.app/ -->



<!-- DEPLOY --> significa publicar seu site na internet, tornando-o acessível para qualquer pessoa através de um link. É o passo final de um projeto web: depois de escrever o código e testar localmente, você o envia para uma plataforma de hospedagem.



