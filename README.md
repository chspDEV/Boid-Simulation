# Simulação do Algoritmo Boids com LibGDX

![Linguagem](https://img.shields.io/badge/Java-100%25-orange)
![Framework](https://img.shields.io/badge/Framework-LibGDX-red)
![Status](https://img.shields.io/badge/status-conclu%C3%ADdo-green)

> Uma simulação gráfica do algoritmo "Boids" de Craig Reynolds, que modela o comportamento de bando de pássaros (ou cardumes de peixes).

## 🎯 Objetivo

O projeto demonstra visualmente os princípios do comportamento emergente. Cada "boid" (agente) toma decisões de forma independente, baseando-se apenas em seus vizinhos locais. A interação dessas decisões simples resulta em um comportamento de bando complexo e realista, sem nenhuma coordenação centralizada.

## ✨ As 3 Regras dos Boids

A simulação é baseada nas três regras clássicas que cada agente segue:

1.  **Separação (Separation):** Mover-se para evitar aglomeração e colisão com os agentes vizinhos.
2.  **Alinhamento (Alignment):** Mover-se na mesma direção média que os agentes vizinhos.
3.  **Coesão (Cohesion):** Mover-se em direção à posição média (centro de massa) dos agentes vizinhos.

## 🛠️ Tecnologias Utilizadas

-   **Linguagem:** Java
-   **Framework de Jogo:** LibGDX
-   **Automação de Build:** Gradle

## ⚙️ Como Executar

O projeto utiliza o Gradle Wrapper, então não é necessário ter o Gradle instalado na máquina.

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/chspDEV/simulacao-boids.git](https://github.com/chspDEV/simulacao-boids.git)
    ```
2.  **Acesse a pasta do projeto:**
    ```bash
    cd simulacao-boids
    ```
3.  **Execute o projeto:**
    * No Windows:
        ```bash
        gradlew.bat run
        ```
    * No Linux ou macOS:
        ```bash
        ./gradlew run
        ```
