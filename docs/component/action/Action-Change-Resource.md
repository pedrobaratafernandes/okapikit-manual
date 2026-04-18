# Action-Change-Resource

[:material-code-tags: Ver Código Fonte C#](https://github.com/VideojogosLusofona/OkapiKit/blob/main/Assets/OkapiKit/Scripts/Actions/ActionChangeResource.cs){ .md-button }



Modifica valores de recursos como vida, moedas ou mana.

![Action Change Resource](../../assets/images/action/Action-Change-Resource.png)

## Configurações do Inspector

| Campo | Função | Detalhes |
| :--- | :--- | :--- |
| **Active** | Ativação | Define se o componente está ligado e pronto para funcionar. |
| **Tags** | Etiquetas | Etiquetas inteligentes (Hypertags) usadas para identificação e filtros. |
| **Conditions** | Condições | Lista de requisitos (ex: variáveis ou tokens) que têm de ser verdadeiros para a execução. |
| **Target Resource** | Alvo. | Onde procurar o recurso (via Hypertag ou Objeto). |
| **Type** | Recurso. | O tipo de recurso (ex: Vida, Moedas). |
| **Operation** | Operação. | **Add**, **Subtract**, **Set**, **Reset**, **Multiply**, **Divide**. |
| **Value** | Valor. | Valor a aplicar (pode ser fixo ou de outra variável). |

## Como configurar

1. **Para**: dar dano ao jogador, use `Subtract` no recurso "Vida".

2. **Para**: dar uma moeda, use `Add` no recurso "Moedas".

3. **Certifique-se**: de que o recurso principal está definido no sistema ou no próprio objeto.

