# Order 2D

Gere o Sorting Order de sprites dinamicamente com base na posição Y (profundidade).

![Order 2D](../../assets/images/helpers/Order2d.png)

## Configurações do Inspector

| Campo | Função | Detalhes |
| :--- | :--- | :--- |
| **Active** | Ativação | Define se o componente está ligado e pronto para funcionar. |
| **Tags** | Etiquetas | Etiquetas inteligentes (Hypertags) usadas para identificação e filtros. |
| **Conditions** | Condições | Lista de requisitos (ex: variáveis ou tokens) que têm de ser verdadeiros para a execução. |
| **Mode** | Modo. | **Simple** (único sprite) ou **Group** (ordena vários em conjunto). |
| **Offset** | Ajuste. | Deslocação vertical do ponto de pivô da ordenação. |

## Como configurar

1. **Adicione**: a todos os objetos que se movem "atrás" e "à frente" uns dos outros (ex: jogador, árvores, NPCs).

2. **O**: resultado é que, quando o jogador caminha para cima de uma árvore, ele fica atrás dela, e quando caminha para baixo, fica à frente.

3. **É**: essencial para dar uma sensação de profundidade e 3D a jogos 2D vistos de cima (Top-Down).

