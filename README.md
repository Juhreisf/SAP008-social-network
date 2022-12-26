# Criando uma Rede Social

## Índice

* [1. Resumo do projeto](#1-resumo-do-projeto)
* [2. Planejamento](#2-planejamento)
* [3. Histórias de Usuário](#3-histórias-de-usuário)
* [4. Protótipo](#4-protótipo)
* [5. Deploy](#5-deploy)
* [6. Desenvolvedoras](#6-desenvolvedoras)

***

## 1. Resumo do projeto

O desafio deste projeto é construir uma Rede Social sobre o qualquer tema.

A Rede Social terá que permitir à qualquer usuário criar uma conta de acesso,
logar-se com ela, criar, editar, deletar e dar _likes_ em publicações.

O objetivo principal de aprendizagem deste projeto é construir uma [Single-page
Application
(SPA)](https://pt.wikipedia.org/wiki/Aplicativo_de_p%C3%A1gina_%C3%BAnica)
[_responsiva_](https://curriculum.laboratoria.la/pt/topics/css/02-responsive) (com mais de uma tela/ página) na
qual seja possível **ler e escrever dados**.

***

## 2. Planejamento

Utilizamos as metodologias ágeis Scrum e Kanban para um planejamento mais eficaz. Dividimos o projeto em pequenas tasks e distribuimos entre a equipe por meio da ferramenta Notion, ao inicio de cada dia faziamos uma Daily para falar sobre a nossa evolução no projeto no dia anterior, faziamos também uma retro ao final de cada sprint para identificar pontos a serem melhorados e planos de ação para a próxima sprint.

***

## 3. Histórias de Usuário

Na escolha do tema nós chegamos a uma necessidade que é bastante delicada, mas também bastante urgente.

O Brasil é 5 colocado no ranking mundial de violência contra a mulher. Os números são alarmantes e os casos de violência doméstica aumentaram durante a pandemia devido ao isolamento social e muitas vezes essas mulheres não têm como denunciar.

Pensando nisso resolvemos criar uma rede social **De Mulheres Para Mulheres**. Assim nasceu a **Cookie**, é uma rede para dar apoio, informações de denúncia e apoio psicológico para mulheres que sofrem ou sofreram com relacionamentos abusivos e violência doméstica e, assim, evitar que casos como esses levem ao feminicídio.

O nome cookie vem da nossa **primeira história de usuário** em que a nossa usuária pede por uma rede discreta que o marido não percebesse que ela estava se comunicando com outras pessoas.

Na **segunda história de usuária**, pede-se que se possa encontrar nela com facilidade informações sobre números e lugares onde pode denunciar e obter ajuda.

E a **terceira história de usuária** ela pede que possa pesquisar e se conectar com outras mulheres que passaram pela mesma situação para obter apoio e se fortalecerem.

***

## 4. Protótipo

Desenvolvemos nosso protótipo de alta fidelidade por meio da ferramento figma. Pensamos em um design clean, intuitivo e responsivo.

***

## 5. Deploy
Aqui está o link do nosso deploy para que possa navegar:



***

## 8. Desenvolvedoras



### Mobile first

O conceito de [_mobile
first_](https://tableless.com.br/mobile-first-a-arte-de-pensar-com-foco/) faz
referência a um processo de desenho e desenvolvimento que parte de como se vê e
como funciona uma aplicação primeiro em um dispositivo móvel e mais adiante se
analisa como adaptar a aplicação à telas progressivamente maiores. Esta é uma
contraposição ao modelo tradicional, no qual primeiro se desenha os websites (ou
webapps) para desktops e depois os adaptam para telas menores.

A motivação aqui é se assegurar que desde o começo sejam desenhadas telas
_responsivas_. Dessa forma, começamos com a aparência e o comportamento do
aplicativo em uma tela e ambiente móvel.

### Múltiplas telas

Em projetos anteriores, nossas aplicações eram compostas de apenas uma tela
_principal_ (uma só _página_). Neste projeto, precisaremos dividir nossa
interface em várias _views_ ou _pages_ e oferecer uma maneira de navegar entre
essas telas. Esse problema pode ser resolvido de várias maneiras: com arquivos
HTML independentes (cada um com seu próprio URL) e links tradicionais; mantendo
na memória e renderizando condicionalmente (sem atualizar a página);
[manipulando o histórico do
navegador](https://developer.mozilla.org/es/docs/DOM/Manipulando_el_historial_del_na_gador)
com
[`window.history`](https://developer.mozilla.org/es/docs/Web/API/Window/history).
Neste projeto, convidamos você a explorar opções e decidir sobre uma opção de
implementação.

### Gravação de dados

Nos projetos anteriores, consumimos dados, mas ainda não tínhamos escrito dados
(salvar alterações, criar dados, excluir, etc). Neste projeto, você precisará
criar (salvar) novos dados, além de ler, atualizar e modificar os dados
existentes. Esses dados podem ser salvos remotamente usando o
[Firebase](https://firebase.google.com/).

Outras:

* [Mobile
  First](https://tableless.com.br/mobile-first-a-arte-de-pensar-com-foco/)
* [Mobile First Is NOT Mobile Only - Nielsen Norman
  Group](https://www.nngroup.com/articles/mobile-first-not-mobile-only/)
* [Flexbox - CSS
  Tricks](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
* [Módulos:
  Export](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Statements/export)
* [Módulos:
  Import](https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Sentencias/import)
