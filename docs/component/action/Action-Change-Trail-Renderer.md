# Action-Change-Trail-Renderer

[:material-code-tags: Ver Código Fonte C#](https://github.com/VideojogosLusofona/OkapiKit/blob/main/Assets/OkapiKit/Scripts/Actions/ActionChangeTrailRenderer.cs){ .md-button }



Ativa ou desativa a emissão de rasto (trail).

![Action Change Trail Renderer](../../assets/images/action/Action-Change-Trail-Renderer.png)

## Configurações do Inspector

| Campo | Função | Detalhes |
| :--- | :--- | :--- |
| **Active** | Ativação | Define se o componente está ligado e pronto para funcionar. |
| **Tags** | Etiquetas | Etiquetas inteligentes (Hypertags) usadas para identificação e filtros. |
| **Conditions** | Condições | Lista de requisitos (ex: variáveis ou tokens) que têm de ser verdadeiros para a execução. |
| **Target** | Trail Renderer. | O componente de rasto alvo. |
| **Emitter** | Emissão. | **Enable**, **Disable** ou **Toggle**. |

## Como configurar

1. **Útil**: para ativar um rasto de luz quando o jogador usa um "dash" ou desativá-lo quando ele está parado.

2. **Arraste**: o componente `Trail Renderer` para o campo **Target**.

