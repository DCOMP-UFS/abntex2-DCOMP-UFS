abntex2-DCOMP-UFS
=========================

Classe que adapta o pacote abntex2 para as normas do Departamento de Computação  (DCOMP) da Universidade Federal de Sergipe (UFS) para trabalho de conclusão de curso (TCC). Para quem não conhece, o abntex2 (http://www.abntex.net.br/) é uma classe que implementa as normas da ABNT para os usuários do LaTex. Eles fizeram o trabalho de normatização e merecem todo o mérito. O que fizemos aqui foi só uma adaptação para as normas do DCOMP-UFS.

Estão disponiveis dois arquivos para download:
- dcomp-abntex2.cls
- Modelo-TCC-DCOMP.tex

Sugerimos escrever o TCC por cima do arquivo .tex fornecido, com toda sua estrutura de pastas. Pra quem utilizar outro modelo, é preciso colocar a classe adequada:

\documentclass[
	% -- opções das classes --
  % (...)
	]{dcomp-abntex2}


Com relação ao pacote abntex2, foram modificadas as seguintes páginas:
- Fontes (em trabalho)
- Sumário (em trabalho)
- Listas (em trabalho)
- Capa (em trabalho)
- Folha de rosto (em trabalho)
- Ficha catalográfica (em trabalho)


É necessário instalar o pacote abntex2 para que funcione. Para informações, basta ir na página fornecida acima para instruções.
