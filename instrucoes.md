# Desafio Técnico - PETREC

Este é um desafio técnico, como etapa do processo seletivo. Responda às questões de forma
clara e objetiva. Além das respostas, é obrigatória a apresentação de uma breve documentação alterando o arquivo README.md de modo a 
instruir o avaliador como instalar as dependências (podendo o ambiente ser Windows ou Linux) e como replicar a solução 
(como é feita a execução de arquivos ou carregamento de ambiente virtual, por exemplo). 

Para a entrega de códigos e/ou outros arquivos, estes devem ser enviados junto ao repositório, se possível. 
Caso sejam muito pesados para o envio via repositório, descreva no README como obtê-lo para replicar sua solução. 

Atenda aos itens a seguir utilizando o conjunto MNIST para reconhecimento de números
manuscritos, utilizando o framework tensorfow. Este dataset pode ser obtido por meio do
próprio tensorflow.

## 1 - Treinamento
* Obtenha os conjuntos de treino e teste;
* implemente uma rede neural com duas camadas escondidas, cada uma com 96 neurônios;
* mostre o número de parâmetros treináveis;
* treine a arquitetura implementada por 10 épocas;
* salve o modelo obtido.

## 2 - Avaliação do modelo
* Carregue o modelo salvo;
* obtenha a matriz de confusão (em valores percentuais) para o conjunto de teste;
* apresente os valores das métricas precision, recall, f1-score e acurácia no conjunto de teste.
