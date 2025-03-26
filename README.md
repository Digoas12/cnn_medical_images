[MADE_WITH_PYTHON_BADGE]:http://ForTheBadge.com/images/badges/made-with-python.svg
[OPEN_IN_COLAB_BADGE]:https://colab.research.google.com/assets/colab-badge.svg
[TENSOR_FLOW_BADGE]:https://img.shields.io/badge/TensorFlow-%23FF6F00.svg
[MAT_PLOT_LIB]:https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black

# Rede CNN para segmentação de imagens médicas cardíacas

![python][MADE_WITH_PYTHON_BADGE]
![colab][OPEN_IN_COLAB_BADGE]
![tensorflow][TENSOR_FLOW_BADGE]
![Matplotlib][MAT_PLOT_LIB]

# Índice

* [Descrição do Projeto](#descrição-do-projeto)
* [Status do Projeto](#status-do-Projeto)
* [Acesso ao Projeto](#acesso-ao-projeto)
* [Tecnologias utilizadas](#tecnologias-utilizadas)
* [Pessoas Contribuidoras](#pessoas-contribuidoras)
* [Desenvolvedor do Projeto](#pessoas-desenvolvedoras)

# Descrição do Projeto

Projeto de Trabalho de Conclusão de Curso com o intuito de segmentar imagens de ressonância magnética cardíacas utilizando uma Rede Neural Convolucional.

O projeto foi construído em Google Colab, utilizando GPU T4 com RAM extendida para treinamento, teste e validação de modelo. 

O projeto completo está disponivel como arquivo .pynb e está dividido da seguinte forma:

### Importações Principais
Onde são realizadas as importações globais para o projeto
### Data Augmentation
Onde é importada a biblioteca Albumentations e é criado um gerador de imagens com possibilidade de até 5 variações para imagens novas
### Construção da Rede Neural
Construção da Rede U-Net, definição das etapas convolucionais, encoders e decoders da Rede
### Treinamento do modelo
Adequação de parâmetros e treinamento da rede.
### Carregamento de Modelos e Resultados
Carregamento dos parâmetros de modelo treinado e primeiros testes
### Avaliação
Avaliação do modelo utilizando as métricas Intersection Over Union (IoU) e Accuracy

Foi utilizado como dataset de imagens o Sunnybrook Cardiac Data, da Cardiac Atlas Project, um dataset de domínio público.

# Status do Projeto

### :checkered_flag: Finalizado :checkered_flag:

# Acesso ao Projeto

O projeto principal, imagens .TIF e alguns gráficos estão disponíveis publicamente, e podem ser acessados via Google Colab através do arquivo .pynb. Para mais detalhes sobre os processos de Pré-Processamento e criação das máscaras, assim como algumas funções de criação, peço que entrem em contato para solicitar o acesso. 

# Tecnologias Utilizadas

## Técnicas

+ Rede U-Net
+ Data Augmentation
+ Embaralhamento de Dados
+ Decaimento de Loss

## Versões

+ TensorFlow - versão 2.15.0
+ Numpy - versão 1.24.4
+ scipy - versão 1.10.0
+ Albumentations - versão 1.4.8
+ Scikit-learn - versão 1.5.0
+ scikit-image - versão 0.23.2
+ imageio - versão 2.34.1

# Pessoas Contribuidoras

| [<img loading="lazy" src="https://avatars.githubusercontent.com/u/141643695?v=4" width=115><br><sub>Beatriz Vitória Pereira Moura</sub>](https://github.com/b232076) |
| :---: |

# Desenvolvedor do Projeto

| [<img loading="lazy" src="https://avatars.githubusercontent.com/u/163450820?v=4" width=115><br><sub>Rodrigo Alves de Souza</sub>](https://github.com/Digoas12) |
| :---: |

## Contato

Você pode me contatar pelo [Email](digoas12@gmail.com) ou pelo [Linkedin](https://www.linkedin.com/in/rodrigo-alves-de-souza-5a34b815b/)

## License

[![Licence](https://img.shields.io/github/license/Digoas12/markdown-badges?style=for-the-badge)](./LICENSE)
<hr>
<hr>
