# Action-Change-Value-V2

[:material-code-tags: Ver Código Fonte C#](https://github.com/VideojogosLusofona/OkapiKit/blob/main/Assets/OkapiKit/Scripts/Actions/ActionChangeValueV2.cs){ .md-button }



Manipula valores de variáveis (Integer ou Float). Esta é a ação mais versátil para lógicas de jogo.

![Action Change Value](../../assets/images/action/Action-Change-Value-V2.png)

## Configurações do Inspector

| Campo | Função | Detalhes |
| :--- | :--- | :--- |
| **Active** | Ativação | Define se o componente está ligado e pronto para funcionar. |
| **Tags** | Etiquetas | Etiquetas inteligentes (Hypertags) usadas para identificação e filtros. |
| **Conditions** | Condições | Lista de requisitos (ex: variáveis ou tokens) que têm de ser verdadeiros para a execução. |
| **Value** | Variável. | A variável local ou global a alterar. |
| **Operation** | Operação. | **Set**, **Add**, **Subtract**, **Multiply**, **Divide**. |
| **Change Value** | Valor. | O número, valor aleatório ou outra variável a aplicar. |

## Como configurar

1. **Use**: `Add` para aumentar a pontuação quando o jogador apanha um objeto.

2. **Use**: `Set` para reiniciar um temporizador.

3. **Esta**: ação é muito versátil porque permite que o valor de uma variável afete outra (ex: `Vida = Vida + Bonus`).

