# Action-Change-Sprite-Renderer

[:material-code-tags: Ver Código Fonte C#](https://github.com/VideojogosLusofona/OkapiKit/blob/main/Assets/OkapiKit/Scripts/Actions/ActionChangeSpriteRenderer.cs){ .md-button }



Modifica dinamicamente a imagem (sprite), cor ou orientação de um sprite.

![Action Change Sprite Renderer](../../assets/images/action/Action-Change-Sprite-Renderer.png)

## Configurações do Inspector

| Campo | Função | Detalhes |
| :--- | :--- | :--- |
| **Active** | Ativação | Define se o componente está ligado e pronto para funcionar. |
| **Tags** | Etiquetas | Etiquetas inteligentes (Hypertags) usadas para identificação e filtros. |
| **Conditions** | Condições | Lista de requisitos (ex: variáveis ou tokens) que têm de ser verdadeiros para a execução. |
| **Target** | Alvo. | O Sprite Renderer a modificar. |
| **Change Type** | Tipo. | **Sprite**, **Color** ou **Flip X/Y**. |
| **Sprite / Color** | Novos Valores. | A imagem ou cor a aplicar conforme o modo. |
| **Bool State** | Estado Flip. | Liga/Desliga o flip (se no modo Flip). |

## Como configurar

1. **Útil**: para mudar o aspeto de um personagem (ex: quando apanha um "power-up").

2. **Arraste**: o `Sprite Renderer` alvo para o campo **Target**.

