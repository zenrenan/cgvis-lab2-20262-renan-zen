# Relatório - Coelinhos do Brasil

> [!CAUTION]
> - Lembre-se que você <ins>**não pode utilizar ferramentas de IA para
>   escrever este relatório**</ins>

## Dados do aluno

- **Cartão UFRGS**: <mark>`00579490`</mark>
- **Nome**: <mark>`Renan Augusto da Silva Zen`</mark>

## Passos que eu segui para resolver o problema especificado (em formato de *"prompt"*)

> [!IMPORTANT]
> - Coloque aqui todas as informações necessárias para que alguém
>   (pessoa ou ferramenta de IA) possa reproduzir os seus passos para
>   solucionar o problema
> - Escreva em formato imperativo, como se fosse um *prompt* com as
>   instruções a serem seguidas na solução do problema
> - Seja objetivo e conciso: quanto *menos palavras* você utilizar,
>   melhor
> - Seja técnico e use terminologia adequada: assuma que quem irá ler
>   os seus passos possui conhecimento de Ciência da Computação e
>   Computação Gráfica
> - Caso você queira incluir informações "longas" (como algum *prompt*
>   grande usado com alguma ferramenta de IA), crie arquivos à parte e
>   adicione links no texto (por exemplo, crie o arquivo `PROMPTS.md`
>   e adicione um link markdown `[os prompts detalhados estão
>   aqui](PROMPTS.md)`)
> - Novamente, lembre-se que você *não pode utilizar ferramentas
>   de IA para escrever este relatório*

<mark>`Esse seria o prompt que eu utilizei mandando a main.cpp original e uma foto do resultado esperado: "A partir desse código base (main.cpp) em que existem uma esfera e 3 coelhos, um dourado, um azul e um verde, mude o programa para que tenha uma câmera com uma vista de 60 graus olhando para o centro de uma figura. Essa figura é composta por um retângulo no formato 8:4:8:4 composto por 24 coelhos verdes, dentro desse retângulo faça um losango no formato 4:2:4:2 composto por 14 coelhos dourados e, por último, dentro do losango faça os coelhos azuis em um círculo composto por 8 coelhos. Faça a escala do chão para que caiba todos os coelhos com folga e no centro. Faça todos os coelhos andarem em fila indiana em sentido horário, de lado para o centro da figura e que eles fiquem pulando em direção para frente deles. Atente-se para alterar o 'farplane' de forma que a camêra enxergue a figura. Por último, faça com que os coelhos tenham a esfera do código original na cabeça, logo a frente de suas orelhas." A partir do resultado, eu alterei as distâncias entre os coelhos e a velocidade deles para que ficasse o mais próximo do resultado esperado.`</mark>

## Principais dificuldades encontradas durante o desenvolvimento (formato livre)

<mark>`Demorei para perceber que, para a distância da câmera, a variável 'farplane' estava pequena e os coelhos não estavam aparecendo na tela por conta disso. Depois que aumentei essa distância, percebi que meu código já estava funcionando.`</mark>

## Você acha que conseguiu resolver o problema de forma adequada?

<mark>`Acredito que grande parte do resultado esperado sim, consegui que os coelhos estivessem se movendo do jeito certo, mas não consegui implementar de forma idêntica a esse pulo que os coelhos estão fazendo pela falta de rotação dos coelhos a cada pulo.`</mark>

## Se você quiser compartilhar mais alguma coisa, coloque aqui:

<mark>`Meu prompt foi bem parecido com esse indicado acima, porém eu não havia percebido o 'farplane' original e fiquei, em vão, mudando outras coisas do código, para só depois de um tempo perceber que meu código já estava funcionando. Então adicionei essa colocação no prompt para evitar esse problema.`</mark>

## Se você possui alguma sugestão para o professor sobre esta atividade, coloque aqui:

<mark>`<preencher>`</mark>
