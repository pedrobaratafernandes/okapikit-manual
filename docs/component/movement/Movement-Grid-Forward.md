# Movement-Grid-Forward

[:material-code-tags: Ver Código Fonte C#](https://github.com/VideojogosLusofona/OkapiKit/blob/main/Assets/OkapiKit/Scripts/Movement/MovementGridForward.cs){ .md-button }



Move o objeto continuamente na sua direção "frente" através da grelha.

![Movement Grid Forward](../../assets/images/movement/Movement-Grid-Forward.png)

## Configurações do Inspector

| Campo | Função | Detalhes |
| :--- | :--- | :--- |
| **Active** | Ativação | Define se o componente está ligado e pronto para funcionar. |
| **Tags** | Etiquetas | Etiquetas inteligentes (Hypertags) usadas para identificação e filtros. |
| **Conditions** | Condições | Lista de requisitos (ex: variáveis ou tokens) que têm de ser verdadeiros para a execução. |
| **Speed** | Velocidade. | Rapidez de deslocação entre células. |
| **Cooldown** | Cooldown. | Tempo de espera entre cada salto de casa. |
| **Align Axis** | Eixo Frontal. | Define qual o eixo é a frente (**Right** ou **Up**). |

## Como configurar

1. **Requer**: um `Grid Object` e um `Grid System`.

2. **Ideal**: para projéteis que se movem em grelha ou personagens que andam sempre em linha reta.

