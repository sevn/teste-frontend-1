<br>
<br>
<br>

<p align="center">🤓&nbsp;&nbsp;&nbsp;SEVN: Teste Front-end 01 &nbsp;&nbsp;&nbsp;💻</p>

<br>
<br>
<br>

<p align="center">
  <img align="center" width="640" alt="Home" src="https://user-images.githubusercontent.com/1953194/153975888-5584321f-a764-4fd6-89ed-614fa9265870.png">
</p>

<br>
<br>
<br>

<p align="center">
  <a href="https://www.figma.com/file/uCtGlzgDqEvSYvqffM6ARJ/Teste-SEVN?node-id=1%3A2">VER DESIGN COMPLETO (2 TELAS)</a>
</p>

<br>
<br>
<br>

## Objetivo

Bem vindo(a) ao teste front-end da SEVN!

O teste consiste em: Criar um projeto em [**Next.js**](https://nextjs.org/) ou [**SvelteKit**](https://kit.svelte.dev/) com duas telas do **SEVN NEWS**, um portal de notícias hipotético.

Você deve criar as telas com base no design [deste link](https://www.figma.com/file/uCtGlzgDqEvSYvqffM6ARJ/Teste-SEVN?node-id=1%3A2).

### Telas:
- **Home:** Uma página que simula a "homepage" de um portal, contendo as notícias mais importantes.
- **Notícia:** Uma página interna com a notícia completa, que deve ser aberta sempre que você clique em uma notícia da home.

### APIs:

O projeto consome 3 endpoints, sendo 2 para montar a Home, e 1 para a tela de Notícia:

URL BASE: https://apimock.sevn.technology
- [`/news/headlines`](https://apimock.sevn.technology/news/headlines): Três artigos principais da Home.
- [`/news/others`](https://apimock.sevn.technology/news/others): Os artigos restantes que ficam abaixo das headlines.
- [`/news/articles/:id`](https://apimock.sevn.technology/news/articles/1): Detalhes de um artigo específico.

## O que será avaliado

Sua capacidade de construir um layout responsivo, componentizável (ou seja, reaproveitável quando fizer sentido) com código limpo e legível.

## O que esperamos
- Que o layout seja responsivo *(disponibilizamos apenas a versão desktop, queremos ver sua capacidade de evitar que o layout "quebre" em tela menores)*;
- Que o projeto seja feito em **Next.js** ou **SvelteKit**;
- Que o código seja limpo e legível;
- Que você crie componentes reutilizáveis onde convém;
- Que seu repositório tenha commits com mensagens legíveis e que façam sentido;
- Uso de Flexbox ou Grid Layout.


**Lembre-se:** Muitos commits detalhando as atividades são melhores que poucos commits com mensagens genéricas e muito código.

## O que não esperamos
- Que sejam usados frameworks CSS como Bootstrap, Material.css, Tailwind CSS e afins.
- Que o projeto seja feito em qualquer framework que não seja **Next.js** ou **SvelteKit**.
- Que você entregue um repositório apenas com um commit "gigante" com todo o código. Também gostamos de ler commits! :-)

## Como entregar o projeto?
Crie um repositório **antes de começar o desenvolvimento**, realize o teste fazendo seus commits normalmente, e ao final do teste, é só compartilhar o repositório conosco através do email: <a href="mailto:vagas@sevn.technology">vagas@sevn.technology</a>!

## Outras dúvidas

**Posso utilizar SASS?**<br>
R: SASS e PostCSS estão liberados.

**Posso utilizar CSS-in-JS?**<br>
R: Nossos projetos não utilizam CSS-in-JS. Recomendamos que seu teste seja feito utilizando CSS/SASS/PostCSS.

**Por que não posso usar Bootstrap/Tailwind CSS?**<br>
Porque nosso objetivo, dentre outras coisas, é avaliar sua capacidade de construir um layout com seus próprios conhecimentos em CSS. O uso de frameworks pode atrapalhar nisso, e nem todo projeto utiliza esses frameworks.

**Posso usar outro framework?**<br>
Não, apenas SvelteKit ou Next.js.

**Como eu lido com a responsividade se não tem layout mobile?**<br>
Nós buscamos uma responsividade básica, e esse é um layout simples, então estamos curiosos para ver como você faria para tornar as duas telas responsivas! :-)

----

No mais, te desejamos boa sorte e estamos ansiosos para ver como você se saiu! 🥳
