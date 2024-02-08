## Sobre o Projeto:
Neste projeto avançado da disciplina de Visão Computacional do curso de Sistemas de Informação da Universidade Federal de Viçosa à qual sou discente treinamos um algoritmo de classificação de imagens para distinguir entre maçãs, ossos e morcegos. Utilizando Python e uma abordagem meticulosa, aplicamos técnicas avançadas de processamento de imagem e aprendizado de máquina para alcançar resultados precisos e confiáveis.

O processo começou com a extração cuidadosa de características das imagens, identificando padrões distintos que nos permitiriam diferenciar entre as três classes. Em seguida, realizamos a normalização dos dados para garantir uma representação consistente e comparável entre as amostras.

A etapa crítica de validação cruzada foi então empregada para avaliar o desempenho do nosso modelo, garantindo que ele fosse capaz de generalizar eficazmente para novos dados. Este passo foi fundamental para ajustar os hiperparâmetros do algoritmo e evitar overfitting.

Finalmente, implementamos o algoritmo de classificação usando o método dos k-vizinhos mais próximos (KNN), uma técnica poderosa e intuitiva para classificação de dados. Com base na proximidade das características de uma imagem de teste às características das imagens de treinamento, nosso modelo foi capaz de atribuir com precisão a classe correta a cada imagem.

## Execução:
Para a execução desse projeto foi nos fornecido um dataset composto pelas 3 classes que se encontrava localmente em nossas máquinas e que durante a execução do algoritmo os mesmos eram importados para serem trabalhados no *Jupyter Notebook*. Logo para a replicação do projeto é necessário que você possua os mesmos em sua máquina. Após isso configure manualmente a parte do código onde é importado os arquivos para o treinamento e teste.

## Configurando ambiente de desenvolvimento:

- Instalar o Anaconda Distribution

- Criar um ambiente de execução virtual

  $ conda create -n sin393-2022-py38 python=3.8

  $ conda activate sin393-2022-py38

- Instalar as bibliotecas necessárias

  $ conda install numpy scikit-image scikit-learn matplotlib pandas seaborn notebook

  $ pip install opencv-python

- PyTorch.

  Instalação no Ubuntu com GPU.
  Para instalação no Windows ou sem GPU, consultar [pytorch.org](https://pytorch.org).
  
  $ conda install pytorch torchvision torchaudio pytorch-cuda=11.6 -c pytorch -c nvidia

  $ pip install -U albumentations
