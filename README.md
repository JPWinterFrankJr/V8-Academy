# V8 Academy — Redesign Tailwind CSS

Protótipo frontend responsivo, construído com **HTML5, Tailwind CSS via CDN e JavaScript puro**, sem Bootstrap.

## Como abrir

1. Extraia o ZIP.
2. Abra `index.html` em um navegador com acesso à internet (o Tailwind CSS é carregado pelo CDN).
3. Para uma experiência mais consistente, use a extensão **Live Server** do VS Code.

## Telas

- Home institucional / manifesto da marca
- Catálogo de cursos com pesquisa e filtros
- Página completa de cada programa com ementa, objetivos, módulos e entregas
- Página da metodologia de ensino
- História do Grupo V8 e espaços para perfis institucionais aprovados
- Login demonstrativo com nome/e-mail fictícios
- Matrícula demonstrativa, sem cobrança
- Painel do aluno e sala de aula por módulos
- Questões contextuais com correção automática e registro do progresso
- Certificado demonstrativo ao concluir os quatro módulos
- Alternância claro/escuro armazenada no navegador

## Pastas

`index.html` — shell e CDN Tailwind.
`assets/css/site.css` — identidade visual e componentes especiais.
`assets/js/app.js` — navegação SPA, cursos, atividades e persistência local.
`assets/img/logo.png` — logo presente no material do projeto (reservado como asset; o cabeçalho usa um monograma tipográfico para manter boa legibilidade).

## Limitações importantes

**Protótipo de demonstração, não pronto para produção.** O login não autentica usuários, a matrícula não cobra valores e os dados ficam no `localStorage`. Conteúdos, preço, duração, ementas e avaliações são propostas ilustrativas que dependem de validação pedagógica. Certificados não possuem validade. Faltam backend, banco de dados, gateways, controle de acesso seguro, streaming de vídeo, termos e políticas apropriados.

As fontes corporativas iBrand, New Order e Graphie são referenciadas por nomes locais; os arquivos de fonte licenciados devem ser providenciados pela empresa. Na ausência delas, o navegador usa fontes de fallback.

Para produção, gere o CSS Tailwind compilado com CLI/Vite e elimine a dependência do CDN. Não salve credenciais reais nesse protótipo.
