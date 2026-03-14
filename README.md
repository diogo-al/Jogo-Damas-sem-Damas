# ♟️ Jogo das Damas

Implementação do jogo das Damas em Java, desenvolvida no âmbito da
disciplina de Introdução à Programação (ISCTE-IUL, 2024/2025).

## Funcionalidades

- Tabuleiro configurável (dimensão e número de peças variável)
- Regras completas: movimento diagonal, capturas obrigatórias
- Jogada manual e jogada aleatória
- Interface gráfica com framework Swing
- Gravar e carregar partidas de ficheiro
- Múltiplas janelas em simultâneo

## Tecnologias

- **Java** — programação orientada a objetos
- **Swing** — interface gráfica

## Como executar
```bash
javac *.java
java Main
```

## Estrutura

A lógica do jogo está separada da interface gráfica:
- `Game.java` — lógica (tabuleiro, peças, jogadas possíveis, capturas)
- `GameApp.java` — interface gráfica (visualização e interação)
