Projeto prático da unidade curricular de Desenvolvimento Web, do curso Técnico em Desenvolvimento de Sistemas — SESI/SENAI Itapeva.

|-------------------------------------------|
| NOME  | [Murilo Marques dos Santos] |
| ANO  | [2° ano B] |
| PROFESSOR | Rafael Ribas |
| DATA | [24/08/2026] |
|-------------------------------------------|

|-------------------------------------------------------------------------|
Landing page de apresentação do , um drone agrícola fictício voltado à
pulverização e ao monitoramento de lavouras. O objetivo da página é convencer o
agricultor a agendar uma demonstração do produto.

O layout foi construído a partir de um protótipo no Figma, com HTML semântico e CSS,
sem frameworks.

O que eu fiz nesse projeto e as principais dificuldades!

Neste projeto, desenvolvi uma página para apresentar o drone AgroVant de forma moderna e profissional. Criei o cabeçalho, a apresentação inicial com vídeo, as funções do drone, suas especificações, depoimentos e um formulário para agendamento de demonstração. A parte mais difícil foi trabalhar com os vídeos, responsividade e organização dos elementos no CSS para que a página funcionasse corretamente em diferentes tamanhos de tela.
|-------------------------------------------------------------------------|

<!-- Exemplo: https://seu-usuario.github.io/landing-page-drone/ -->
     https://github.com/murilosantos-dev/projeto-drones.git
```
landing-page-drone/ 
├── index.html    página principal
├── README.md     este arquivo 
├── css/ 
│    └── style.css   estilos do projeto 
└── img/    imagens e vídeos
```
|-------------------------------------------------------------------------|

- [X] Menu (cabeçalho)
- [X] Hero section
- [X] Especificações
- [X] Vídeo do produto
- [X] Cards de benefícios
- [X] Depoimentos
- [X] Formulário de contato

<!-- Marque com um X entre os colchetes as seções que você concluiu: [x] -->


[x]  — `header`, `main`, `section`, `footer`
[] com variáveis em `:root`
[X]  para os layouts
[X]  com abordagem  e media queries
[]  (`rem`, `%`) no lugar de medidas fixas

|-------------------------------------------------------------------------|

A página foi desenvolvida para diferentes tamanhos de tela utilizando media queries. O layout principal foi desenvolvido para desktop e posteriormente adaptado para tablets e celulares usando o responsivo.

A página foi desenvolvida para funcionar em diferentes tamanhos de tela. Foram utilizadas media queries para adaptar o layout para celulares, tablets e computadores.

Tela:	
1 - Celular: O menu principal é ocultado e permanece apenas o botão de agendamento. Os cards ficam empilhados e o formulário passa para baixo do texto.
2 - Tablet: Os cards são organizados em duas colunas e os elementos são redimensionados para ocupar melhor o espaço disponível.
3 - Desktop: O menu aparece normalmente, os cards são organizados em três colunas e o conteúdo é distribuído horizontalmente.

|------------------------------------------------------------------------|

git clone [https://github.com/murilosantos-dev/projeto-drones.git]
cd [projeto-drones]
```

Página publicada
https://projeto-drones.vercel.app

|------------------------------------------------------------------------|

- Protótipo do layout: material da disciplina
- Imagens e vídeos: material fornecido pelo professor
- Fontes: **Arial, Helvetica e sans-serif**, utilizadas diretamente no CSS.

|-----------------------------------------------------------------|

Projeto acadêmico, sem fins comerciais. O drone AGROVANT é fictício.