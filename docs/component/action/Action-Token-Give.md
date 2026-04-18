# Action-Token-Give

[:material-code-tags: Ver Código Fonte C#](https://github.com/VideojogosLusofona/OkapiKit/blob/main/Assets/OkapiKit/Scripts/Actions/ActionTokenGive.cs){ .md-button }



Atribui "Tokens" (indicadores de estado ou itens de progresso) ao jogador.

![Action Token Give](../../assets/images/action/Action-Token-Give.png)

## Configurações do Inspector

| Campo | Função | Detalhes |
| :--- | :--- | :--- |
| **Active** | Ativação | Define se o componente está ligado e pronto para funcionar. |
| **Tags** | Etiquetas | Etiquetas inteligentes (Hypertags) usadas para identificação e filtros. |
| **Conditions** | Condições | Lista de requisitos (ex: variáveis ou tokens) que têm de ser verdadeiros para a execução. |
| **Quest Manager** | Gestor. | O componente `QuestManager` que guarda os tokens. |
| **Token** | Tipo de Token. | A Hypertag que representa o item (ex: "Chave_Azul"). |
| **Quantity** | Quantidade. | Quantos tokens o jogador recebe. |

## Como configurar

1. **Use**: para dar chaves, cristais ou qualquer item de progresso ao jogador.

2. **Os**: tokens podem ser verificados mais tarde nos Triggers para abrir portas ou completar missões.

