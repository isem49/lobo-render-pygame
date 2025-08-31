# 🐺 Desenho de um Lobo com Python, Pygame e OpenGL

![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![Pygame](https://img.shields.io/badge/Pygame-2.1.2-green.svg)
![PyOpenGL](https://img.shields.io/badge/PyOpenGL-3.1.5-orange.svg)


Um projeto simples para demonstrar a renderização 2D de uma figura geométrica estilizada de um lobo, utilizando Pygame para a criação da janela e gerenciamento de eventos, e PyOpenGL para as operações de desenho.

## 📜 Sobre o Projeto

Este projeto implementa a renderização 2D de um lobo estilizado. A figura é construída a partir de um conjunto de vértices (pontos) e arestas (linhas que conectam os pontos). Os olhos são desenhados como polígonos preenchidos para dar contraste à figura.

É um ótimo exemplo para iniciantes que desejam entender como Pygame e PyOpenGL podem ser usados juntos para criar gráficos 2D.

## ✨ Funcionalidades

- Renderização 2D de um lobo estilizado.
- Uso de Pygame para a criação da janela e loop de eventos.
- Uso de PyOpenGL para o desenho de baixo nível (linhas e polígonos).
- Código estruturado para facilitar o entendimento dos conceitos de vértices, arestas e primitivas gráficas.

## 🚀 Tecnologias Utilizadas

- [Python 3](https://www.python.org/)
- [Pygame](https://www.pygame.org/)
- [PyOpenGL](http://pyopengl.sourceforge.net/)

## 📦 Instalação e Execução

Siga os passos abaixo para executar o projeto localmente.

### Pré-requisitos

- Python 3 instalado em seu sistema.

### Passos

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/seu-usuario/lobo-opengl.git](https://github.com/seu-usuario/lobo-opengl.git)
    cd lobo-opengl
    ```

2.  **Crie e ative um ambiente virtual** (opcional, mas altamente recomendado):
    ```bash
    # Criar ambiente
    python -m venv venv

    # Ativar no Linux / macOS
    source venv/bin/activate

    # Ativar no Windows
    venv\Scripts\activate
    ```

3.  **Instale as dependências:**
    ```bash
    pip install pygame PyOpenGL PyOpenGL_accelerate
    ```

## ▶️ Como Executar

Com as dependências instaladas, execute o script principal a partir do terminal:

```bash
python main.py
