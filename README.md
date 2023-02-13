# Modelo de capa para trabalhos

Fiz este projeto pensando em ajudar pessoas que estudam no [Instituto Infnet](https://infnet.edu.br) e que utilizam o sistema de formatação de textos LaTeX para produzirem seus documentos.

O resultado final do código contido neste projeto é uma capa de trabalho que está em conformidade com as normas da ABNT e com configuração de usar o idioma português.

Claro, é possível adaptar esse código para criar capas para outras instituições de ensino. Este projeto é apenas um exemplo. Você pode alterar de acordo com a instituição em que estuda.

Sugiro que dê um fork deste projeto para atender às suas necessidades caso estude em outra instituição.

## Como utilizar este projeto

1. Faça uma cópia deste repositório para o seu computador:

`git clone https://github.com/mg-reis/modelo-at-tp.git`

ou 

`git clone https://gitlab.com/mg-reis/modelo-at-tp.git`

2. A partir do arquivo **modelo-at-tp.tex**, você pode fazer uma cópia para cada trabalho que for fazer, e ir adaptando conforme o título da sua graduação, bloco, seu nome, nome do professor, nome da disciplina e do trabalho.

3. Quando o seu trabalho estiver pronto, compile o arquivo 

Existem editores de LaTeX online, como [Overleaf](https://overleaf.com), que possuem um botão de compilar ou compilação automática.

Existem editores de texto especializados de LaTeX como o [TeX Studio](https://www.texstudio.org/), que também tem as mesmas opções mencionadas anteriormente dos editores online, só que de forma offline.

Agora, caso esteja utilizando a linha de comando, digite:

Para compilar o modelo de capa:

`pdflatex modelo-at-tp.tex`

Para compilar um trabalho que fez:

`pdflatex nome_do_trabalho.tex`
