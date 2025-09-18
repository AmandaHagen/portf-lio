link para o projeto no figma.
https://www.figma.com/design/4EKKCbr5rS93RWP7kRjXIz/Portfolio---Curso-1?node-id=0-1&p=f&t=hRwkUPd9aAf17yo6-0




projeto 3 figma:

https://www.figma.com/design/NrzJacC887svMVfF9oC2jM/Portfolio-Projeto-2?node-id=1-47&t=XvC0bxs0Oj1UIOs0-0

Amanda Hagen é desenvolvedora front-end, empresária e barbeira — uma mulher que une criatividade, técnica e estilo em tudo o que faz. No universo do código, domina HTML, CSS e JavaScript com precisão, criando interfaces modernas, acessíveis e cheias de personalidade. Como empresária, lidera com visão e coragem, transformando ideias em negócios que inspiram. E na barbearia, sua arte vai além da tesoura: ela cria experiências, conecta pessoas e eleva a autoestima de quem passa por sua cadeira. Amanda é movida por desafios e pela vontade de aprender sempre mais. Seu portfólio reflete sua essência: ousado, elegante e funcional. Ela acredita que tecnologia e beleza podem andar juntas, e prova isso todos os dias com seu trabalho. Seja no teclado ou na navalha, Amanda entrega excelência. Sua trajetória é marcada por dedicação, inovação e autenticidade. Uma mulher que não cabe em rótulos, mas que redefine cada espaço que ocupa com talento e paixão.


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




<!-- Visualizar o exercício -->
html e css: Cabeçalho, footer e variaveis css:
05.Aplicando Variáveis CSS:
  ° 09 - para saber mais: dicas de projeto
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