# Classificação de Imagens com Rede Neural Convolucional (CNN)

Projeto acadêmico individual da disciplina de **Deep Learning**, do curso de Tecnologia em Banco de Dados da Faculdade de Tecnologia e Inovação Senac-DF.

[![Abrir no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/DanielNego/cnn-classificacao-imagens/blob/main/notebooks/[ajuste: nome-do-notebook].ipynb)

## 🎯 Objetivo

Implementar em Python uma Rede Neural Convolucional (CNN) simples para [ajuste: classificar imagens de ...], com foco em entender e explicar como o algoritmo funciona.

## 🧠 Como funciona uma CNN (resumo)

Uma CNN é um tipo de rede neural usada principalmente para imagens. Ela funciona em etapas:

1. **Camadas convolucionais:** usam filtros que "passeiam" pela imagem para detectar características, como bordas e formas.
2. **Pooling:** reduz o tamanho da imagem mantendo as informações mais importantes.
3. **Camadas densas:** pegam essas características e decidem a qual classe a imagem pertence.

## 📊 Dados

- **Base de dados:** [ajuste: nome e fonte, por exemplo MNIST ou CIFAR-10]
- **Classes:** [ajuste: quais e quantas]
- **Quantidade de imagens:** [ajuste: treino / teste]
- **Tamanho das imagens:** [ajuste: por exemplo 28x28]

## 🏗️ Modelo

[ajuste: descreva a arquitetura usada, na ordem das camadas. Exemplo:]

```
Conv2D → MaxPooling → Conv2D → MaxPooling → Flatten → Dense → Saída
```

- **Função de perda:** [ajuste]
- **Otimizador:** [ajuste]
- **Épocas:** [ajuste]

## 📈 Resultados

- **Acurácia no teste:** [ajuste]

![Gráfico de acurácia e perda](images/[ajuste: nome-do-grafico].png)

[ajuste: uma ou duas frases sobre o que os resultados mostram, sem exagerar]

## 🛠️ Tecnologias

- Python
- [ajuste: TensorFlow/Keras ou PyTorch]
- [ajuste: NumPy, Matplotlib etc.]
- Google Colab

## ▶️ Como executar

**No Google Colab:** clique no botão "Abrir no Colab" no topo desta página e execute as células em ordem (Ambiente de execução → Executar tudo).

**No computador:**
```bash
git clone https://github.com/DanielNego/cnn-classificacao-imagens.git
cd cnn-classificacao-imagens
pip install -r requirements.txt
```
Depois, abra o notebook em `notebooks/` com o Jupyter ou o VS Code.

## 📁 Estrutura do repositório

```
cnn-classificacao-imagens/
├── README.md
├── requirements.txt
├── notebooks/             ← Notebook da CNN
└── images/                ← Gráficos usados neste README
```

## 👤 Autor

Daniel Reis Rodrigues — [LinkedIn](https://www.linkedin.com/in/daniel-reis-rodrigues/)

## ℹ️ Observações

Projeto com fins acadêmicos e educacionais.
