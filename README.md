# 🌟 Redes Neurais Convolucionais 🌟

Implementação do modelo de Redes Neurais Convolucionais (Convolutional Neural Networks - CNN). As CNN são um tipo de modelo de ML comum em tarefas de reconhecimento de padrões e imagens. Elas aplicam diferentes transformações e filtros nas imagens de entrada que tornam sua 'compreensão' dos elementos mais complexa, auxiliando no reconhecimento de padrões.

<!-- omit in toc -->
## 🔍 Índice
- [🌟 Códigos e Arquivos:](#-códigos-e-arquivos)
- [⚙️ Instalação](#️-instalação)
- [☑️ Dependências](#️-dependências)
- [📚 Bibliografia](#-bibliografia)

## 🌟 Códigos e Arquivos:
Este repositório conta com:

## ⚙️ Instalação
Para clonar este repositório localmente, siga os passos abaixo:

1. Abra o terminal na pasta em que deseja guardar esse projeto.

2. Utilize o comando abaixo para clonar o repositório:
```bash
git clone https://github.com/Od4ir/ML-Convolutional_Neural_Network.git
```
3. Após a clonagem, para rodar os JN e os arquivos em Python, é necessário a instalação da [Miniconda - Download e instalação](https://conda.io/en/latest/miniconda.html). Após instalar a **Miniconda** rode:

```bash
~/miniconda3/bin/conda init
```
4. E crie um ambiente virtual chamado **d2l** para rodar os programas e instalar as bibliotecas sem afetar seu ambiente global:
```bash
conda create --name d2l python=3.9 -y   # *Lembre-se de alterar a versão do Python
```
5. Ativando e desativando o ambiente virtual:
```bash
conda activate d2l     # Ativa o ambiente
conda deactivate       # Desativa o ambiente
```

Após isso, é necessário instalar as bibliotecas do Python: **[d2l](https://pypi.org/project/d2l/)**, **[pytorch](https://pypi.org/project/torch/)**, **[torchvision](https://pypi.org/project/torchvision/)** e **[matplotlib](https://pypi.org/project/matplotlib/)**:

```bash
conda activate d2l

# Instalar a biblioteca d2l
pip install d2l

# Instalar o PyTorch e torchvision
pip install torch torchvision

# Instalar matplotlib
pip install matplotlib
```

Caso falte alguma durante as execuções, basta instalar com o:
```bash
pip install <nome_da_biblioteca>
```


## ☑️ Dependências e Ferramentas:
Verifique a seguir as bibliotecas e outras dependências utilizadas nesse projeto. Certifique-se de ter as essas dependências instaladas no seu ambiente:

- [Python 3.12.2](https://www.python.org/) - Linguagem de programação utilizada;
- [Pytorch 2.4.0+cu121](https://pytorch.org/get-started/locally/) - Biblioteca do Python criada para facilitar o trabalho com Machine Learning;
- [Jupyter Notebook](https://jupyter.org/install) - Aplicação web que permite escrever documentos com texto e código;
- [Matplotlib](https://matplotlib.org/) - Biblioteca do Python com funções para visualização de dados;
- [NumPy](https://numpy.org/) - Biblioteca do Python com funções para realizar várias funções numéricas;
- [d2l](https://pypi.org/project/d2l/) - Biblioteca para acompanhar o livro *Dive into Deep Learning*;
- [torchvision](https://pypi.org/project/torchvision/) - Biblioteca para visões computacionais em PyTorch.

## 📚 Bibliografia
- [Dive Into Deep Learning - Livro](https://pt.d2l.ai/chapter_linear-networks/index.html);
- [Convolutional Neural Networks: A Brief History of their Evolution - Artigo - Medium](https://medium.com/appyhigh-technology-blog/convolutional-neural-networks-a-brief-history-of-their-evolution-ee3405568597);
- [Inception Module Definition - Artigo - DeepAi](https://deepai.org/machine-learning-glossary-and-terms/inception-module);
- [ResNet Architeture Explaned - Artigo - Medium](https://medium.com/@siddheshb008/resnet-architecture-explained-47309ea9283d);
- [What are Convolucional Neural Networks (CNNs)? - Vídeo - IBM Technology](https://www.youtube.com/watch?v=QzY57FaENXg);
- [Convolutional Neural Networkds (CNNs) explained - Vídeo - deeplizard](https://www.youtube.com/watch?v=YRhxdVk_sIs&t=19s);
