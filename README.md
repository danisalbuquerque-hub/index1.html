# tocaia

Painel de proteção ambiental, dos animais e dos povos originários.

A tocaia monitora projetos de lei e consultas públicas do Congresso Nacional e avisa a tempo de agir.
Projeto independente, gratuito e sem fins lucrativos.

Site: https://tocaia.eco.br

## Objetivo

Ampliar a transparência do processo legislativo e facilitar a participação cívica em defesa do meio ambiente,
dos animais e dos povos originários.

## Como funciona

- **Site** (`index.html`, `perguntas.html`): página estática, hospedada no GitHub Pages. Lê dados publicados de uma planilha.
- **Automação** (pasta `automacao/`): scripts do Google Apps Script que consultam dados oficiais abertos
  (Câmara dos Deputados, Senado Federal, e-Cidadania, Diário Oficial da União e imprensa), classificam os itens
  com apoio de inteligência artificial, leem o placar das consultas e enviam os alertas por e-mail.
- **Chaves e senhas** não ficam no código: são guardadas nas propriedades do projeto no Apps Script.

## Fontes de dados

Dados abertos da Câmara dos Deputados e do Senado Federal, consultas públicas do e-Cidadania e Google Alertas (imprensa).

## Aviso

Resumos e níveis (retrocesso, atenção, neutro, avanço) são gerados por inteligência artificial a partir da ementa
e podem conter erros. Confira sempre a fonte oficial.

## Autoria

Concebido e desenvolvido por Danielle Simões Albuquerque, sem formação em programação, por meio da apropriação de
ferramentas digitais e de dados oficiais abertos, em diálogo com a tradição do hackerismo cívico.
Desdobramento de trabalho acadêmico coletivo (Danielle Simões Albuquerque, Laura Gazzinelli, Luma Lins e Yasmin Junqueira)
na pós-graduação em Mídia, Política e Sociedade da FESPSP.

## Licença

MIT. Veja o arquivo `LICENSE`.

## Contato

tocaiapelomeioambiente@gmail.com
