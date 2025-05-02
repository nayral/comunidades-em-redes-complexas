

# Comunidades em Redes Complexas

Este repositório contém um estudo aplicado sobre redes complexas, com foco na detecção de comunidades utilizando grafos. A análise é feita com Python e utiliza bibliotecas como `networkx`, `community` (Louvain), `matplotlib` e `pandas`.

## 📘 Descrição

O notebook realiza as seguintes etapas:

1. **Leitura e visualização de grafos**: Um grafo é lido a partir de arquivos `.gml` ou gerado artificialmente.
2. **Cálculo de métricas**: São calculadas propriedades como grau médio, distribuição de grau e centralidade.
3. **Detecção de comunidades**: Utiliza o algoritmo de Louvain para identificar comunidades dentro do grafo.
4. **Visualização**: Comunidades e estrutura da rede são visualizadas com diferentes esquemas de cores e layouts.

## 🛠️ Tecnologias e Bibliotecas

- Python 3.x
- networkx
- community (python-louvain)
- matplotlib
- pandas

## 📦 Instalação

Clone o repositório e instale as dependências com:

```bash
git clone https://github.com/seu-usuario/comunidades-em-redes-complexas.git
cd comunidades-em-redes-complexas
pip install -r requirements.txt
