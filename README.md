dcomp-abntex2
=========================

Classe que adapta o pacote abntex2 para as normas do Departamento de Computação e o Programa de Pós-Graduação em Ciência da Computação da Universidade Federal de Sergipe. Para quem não conhece, o abntex2 (http://www.abntex.net.br/) é uma classe que implementa as normas da ABNT para os usuários do LaTex.

Estão disponiveis dois arquivos para download:
- dcomp-abntex2.cls         % Pacote com as regras gerais do template
- Graduacao.sty             % Estilo de formatação para os Trabalhos de conslusão de curso
- Mestrado.sty              % Estilo de formatação para as Dissertações de Mestrado
- Modelo-TCC-DCOMP.tex      % Modelo para os Trabalhos de conclusão de curso
- Modelo-Mestrado-PROCC.tex % Modelo para as Dissertações de Mestrado

Sugerimos escrever documentos por cima do arquivo .tex fornecido, com toda sua estrutura de pastas. Pra quem utilizar outro modelo, é preciso colocar a classe adequada:

\documentclass[
	% -- opções das classes --
  % (...)
	]{dcomp-abntex2}


Com relação ao pacote abntex2, foram modificadas as seguintes páginas:
- Fontes -> Times New Roman
- Sumário -> Tradicional, com hierarquia entre capítulos e seções
- Listas -> Ilustrações, Tabelas e Códigos
- Capa -> Imagens do DCOMP/PROCC e UFS adicionadas
- Folha de rosto
- Ficha catalográfica
- Membros da banca


É necessário instalar o pacote abntex2 para que o template funcione. Para maiores informações, ir na página http://www.abntex.net.br/.