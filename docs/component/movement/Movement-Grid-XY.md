# Movement-Grid-XY

[:material-code-tags: Ver Código Fonte C#](https://github.com/VideojogosLusofona/OkapiKit/blob/main/Assets/OkapiKit/Scripts/Movement/MovementGridXY.cs){ .md-button }



Permite controlar um objeto na grelha nos eixos X e Y.

![Movement Grid XY](../../assets/images/movement/Movement-Grid-XY.png)

## Configurações do Inspector

| Campo | Função | Detalhes |
| :--- | :--- | :--- |
| **Active** | Ativação | Define se o componente está ligado e pronto para funcionar. |
| **Tags** | Etiquetas | Etiquetas inteligentes (Hypertags) usadas para identificação e filtros. |
| **Conditions** | Condições | Lista de requisitos (ex: variáveis ou tokens) que têm de ser verdadeiros para a execução. |
| **Speed** | Velocidade. | Rapidez de movimento entre células. |
| **Cooldown** | Cooldown. | Intervalo mínimo entre movimentos. |
| **Input Type** | Controle. | Como o jogador controla o objeto (Axis, Button, Key). |
| **Push Strength** | Empurrão. | Permite empurrar outros `Grid Objects`. |

## Como configurar

1. **Utilize**: este componente em conjunto com um `Trigger On Input` para controlo do jogador.

2. **No**: `Trigger On Input`, escolha as teclas e associe-as ao movimento X e Y deste componente.

3. **Garanta**: que o `Grid System` está bem configurado para o tamanho dos seus sprites.

