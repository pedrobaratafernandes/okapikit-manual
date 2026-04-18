# Action-Set-Outline

[:material-code-tags: Ver Código Fonte C#](https://github.com/VideojogosLusofona/OkapiKit/blob/main/Assets/OkapiKit/Scripts/Actions/ActionSetOutline.cs){ .md-button }



Ativa ou altera o efeito de contorno (outline) num componente visual.

![Action Set Outline](../../assets/images/action/Action-Set-Outline.png)

## Configurações do Inspector

| Campo | Função | Detalhes |
| :--- | :--- | :--- |
| **Active** | Ativação | Define se o componente está ligado e pronto para funcionar. |
| **Tags** | Etiquetas | Etiquetas inteligentes (Hypertags) usadas para identificação e filtros. |
| **Conditions** | Condições | Lista de requisitos (ex: variáveis ou tokens) que têm de ser verdadeiros para a execução. |
| **Color** | Cor. | A cor da linha de contorno. |
| **Thickness** | Espessura. | Largura da linha. Definir como 0 remove o contorno. |

## Como configurar

1. **Use**: isto num `Trigger On Mouse Enter` para destacar um objeto quando o rato passa por cima, e num `Trigger On Mouse Exit` com espessura 0 para remover o destaque.

2. **Requer**: que o material do objeto suporte este tipo de efeito (Shader com Outline).

