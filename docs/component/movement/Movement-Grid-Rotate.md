# Movement-Grid-Rotate

[:material-code-tags: Ver Código Fonte C#](https://github.com/VideojogosLusofona/OkapiKit/blob/main/Assets/OkapiKit/Scripts/Movement/MovementGridRotate.cs){ .md-button }



Controla a rotação de um objeto em incrementos fixos (ex: 90º), mantendo o alinhamento com a grelha.

![Movement Grid Rotate](../../assets/images/movement/Movement-Grid-Rotate.png)

## Configurações do Inspector

| Campo | Função | Detalhes |
| :--- | :--- | :--- |
| **Active** | Ativação | Define se o componente está ligado e pronto para funcionar. |
| **Tags** | Etiquetas | Etiquetas inteligentes (Hypertags) usadas para identificação e filtros. |
| **Conditions** | Condições | Lista de requisitos (ex: variáveis ou tokens) que têm de ser verdadeiros para a execução. |
| **Speed** | Velocidade. | Rapidez da animação de rotação. |
| **Step Size** | Passo Angular. | O ângulo de cada "salto" (ex: 90 para as 4 direções cardinais). |
| **Mode** | Modo. | **Auto**, **Input**, **Target**, **Movement**. |
| **Cooldown** | Cooldown. | Tempo mínimo entre rotações. |

## Como configurar

1. **Requer**: um `Grid Object` no mesmo objeto.

2. **Defina**: o **Angular Step Size** para 90 se quiser que o objeto apenas aponte para as quatro direções cardinais.

3. **É**: muito útil para personagens que mudam de direção em jogos de grelha.

