# introducao-typescript-dio

O objetivo desse repositório é mostrar exemplos e desafios do Typescript que vão dar uma noção geral suficiente da ferramenta, para que ela seja usada no dia a dia do desenvolvedor.

Para quem é esse repositório:
* *Pessoas que tem vontade de aprender JavaScript aplicando boas práticas desde o início*
* *Pessoas que já usam JavaScript e querem desaprender habitos negativos de linguagem*
* *Quem já teve dor de cabeça com JavaScript e tem um trauma a ser curado*

## O que é Typescript
 É um superset do Typescript que trás tipagem estática para a linguagem, além de outras features, com o propósito de melhorar a qualidade do código escrito e a sua usabilidade. Como é um superset o código compilado e usado em produção ainda é javaScript, porém é um JS mais resiliente e turbinado graças ao uso de TS durante o desenvolvimento.

 ## Do que você vai precisar
 Ferramentas necessárias:
 * *Do Node instalado na sua máquina*
 * *Instalar o Typescript usando o npm (npm install -g Typescript)*
    * *É interessante que ele seja instalado de forma global, para que o usuário possa usar a biblioteca a qualquer momento e em qualquer projeto para fazer testes rápidos com TS*
* *De uma IDE como o visual studio code*

Requisitos técnico:
* *Lógica de programação*
* *Mas é melhor ainda se tiver um conhecimento básico em JavaScript*

## Sobre a estrutu de commits
Os commits foram feitos de tal forma que o usuário pode ler commit e commit em ordem de publicação e acompanhar gradualmente a cria do repositório e a lógica aplicada. É recomendado que o primeiro estudo seja feito dessa forma. Pequenos erros nos comentários ou de gramática podem ser encontrados no caminho (consequências do programador que estuda de madrugada) mas eles já foram devidamente  corrigidos na última versão do main.

## Estrutura do repositório 
* *src*
  * Contém arquivos com exemplos de uso de TS e JS comentados para facilitar o entendimento da ferramenta
* *desafios*
  * Contém vários arquivos JS que podem ser refatorados para solidificar o conhecimento adquirido na aula
* *index.html*
  * É onde está a chamada para o arquivo app.js e pode ser manipulado a vontade para testarem seus scripts
* *tsconfig.json*
  * O coração do TS que configura suas funcionalidades
* *package.json*
  * Nesse arquivo foram colocados alguns scripts com o propósito de facilitar a vida de quem usar esse repositório
* *start*
  * Inicia o *liter-server*, que vai executar modificações no index.html e em seus arquivos importados. É útil caso queira fazer testes no Browser. A porta disposta normalmente é a *localhost:3000*
* *watch*
  * Roda o *tsc --watch* com o propósito de compilar constantemente qualquer coisa que for editada nos arquivos TS para sua contraparte em JS. Esse comando evita que *tsc* tenha que ser digitado constantemente para fazer a compilação.

## Sobre como testar
* *Teste mão livre*
  * Faça suas alterações em src/app.ts
  * Rode *tsc* ou *npm watch* para compilar elas para o arquivo dist/app.js
  * Caso queira fazer um teste interagindo com o DOM, altere o index.html
  * Rode o npm start e acesse o localhost:3000
  * Testar alguns dos arquivos da pasta de exemplos ou desafios
