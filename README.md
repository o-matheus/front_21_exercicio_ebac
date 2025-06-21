Exercício Final – Módulo 21: Criando uma Nova Landing Page
🎯 Objetivos da Aula
Consolidar os conhecimentos adquiridos ao longo do módulo de criação de landing pages;

Praticar a construção de um site responsivo e estilizado do zero, utilizando HTML, CSS (com SASS) e JavaScript;

Realizar o deploy da página na Vercel.

📚 Introdução ao Projeto
Neste exercício final, a proposta foi desenvolver uma landing page com um tema de livre escolha, inspirado em filmes, séries, jogos ou outras mídias.

Enquanto o professor sugeriu exemplos como filmes, eu preferi escolher um tema que gosto bastante: o manhwa (mangá coreano) Omniscient Reader's Viewpoint (ORV).

🎨 Tema Escolhido: Omniscient Reader's Viewpoint (ORV)
Descrição da Obra:

Omniscient Reader's Viewpoint é uma obra de ação, fantasia e suspense que acompanha Kim Dokja, um homem comum que vê o mundo ao seu redor se transformar no cenário de uma web novel que ele era o único leitor fiel.
A história traz batalhas intensas, estratégias, dilemas morais e muito desenvolvimento de personagens, sempre com o foco na sobrevivência e na manipulação inteligente dos eventos.

🖥️ Estrutura e Funcionalidades do Site
O site foi organizado com as seguintes seções:

Header:
Inclui o logo do projeto e um botão de chamada para ação (“Começar a Ler”), aplicando responsividade e estilizações adaptadas para diferentes tamanhos de tela.

Hero (Seção de Abertura):
Uma imagem horizontal representando a obra acompanhada de um texto introdutório sobre a história.

Seção de Personagens:
Sistema de abas com os principais personagens da obra. Cada aba exibe uma imagem e uma breve descrição sobre o personagem.

Seção de Leitura (Cards):
Três cards com links direcionando para diferentes formas de acesso à obra:

Leitura gratuita na Webtoon (em inglês);

Compra da versão física na Amazon;

Leitura no site oficial coreano.

FAQ:
Seção com perguntas frequentes sobre o ORV e o universo dos manhwas.

Footer:
Inclui meu nome, uma nota de que é um projeto acadêmico, e ícones com links para minhas redes sociais (LinkedIn, GitHub, Discord e TikTok).

🛠️ Tecnologias Utilizadas
HTML5

CSS3 com SASS

JavaScript

Gulp: Para automação de tarefas como compilação do SASS e minificação de arquivos JS;

Vercel: Para hospedagem e deploy.

💡 Principais Desafios e Aprendizados
JavaScript:
Minha principal dificuldade foi relembrar os comandos de JavaScript, especialmente na manipulação de classes e interatividade de abas e FAQ. A lógica estava clara na cabeça, mas a execução exigiu pesquisa e revisão.

Gulp e Estrutura de Pastas:
No começo, deixei o index.html dentro da pasta /src, o que causou erro na Vercel durante o deploy. Precisei mover os arquivos para a raiz do projeto e ajustar as configurações do Gulp.

CSS e Responsividade:
Um dos aprendizados foi o uso do filter: invert() no CSS para inverter a cor dos ícones das redes sociais.
Também enfrentei pequenos problemas com espaçamentos, tamanhos de botão na versão mobile e alinhamentos de texto no Hero.

Ajustes Pendentes:
Deixei de fazer alguns ajustes como:

Melhorar o layout dos botões na versão mobile;

Padronizar o corte e tamanho das imagens dos personagens;

Corrigir pequenos detalhes de espaçamento lateral na seção Hero.

Acessibilidade e Interatividade:
Diferente de projetos anteriores, neste eu adicionei efeitos de hover e transições nos botões, seguindo feedbacks de colegas de turma.

✅ Conclusão
O resultado final ficou visualmente bonito e dentro das expectativas do módulo.
Ainda tenho vários pontos para melhorar, mas fiquei satisfeito com o processo de aprendizado.
Mais do que entregar um site pronto, esse exercício serviu para consolidar vários conceitos que vinham sendo apresentados ao longo do módulo.