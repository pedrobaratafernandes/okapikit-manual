# Action-Change-Renderer

[:material-code-tags: Ver Código Fonte C#](https://github.com/VideojogosLusofona/OkapiKit/blob/main/Assets/OkapiKit/Scripts/Actions/ActionChangeRenderer.cs){ .md-button }



Modifica as propriedades visuais de um renderizador (ex: visibilidade).

![Action Change Renderer](../../assets/images/action/Action-Change-Renderer.png)

## Configurações do Inspector

| Campo | Função | Detalhes |
| :--- | :--- | :--- |
| **Active** | Ativação | Define se o componente está ligado e pronto para funcionar. |
| **Tags** | Etiquetas | Etiquetas inteligentes (Hypertags) usadas para identificação e filtros. |
| **Conditions** | Condições | Lista de requisitos (ex: variáveis ou tokens) que têm de ser verdadeiros para a execução. |
| **Renderer** | Renderizador. | O componente visual (Sprite Renderer, etc) a modificar. |
| **Change Type** | Tipo. | Atualmente focado em **Visibility** (Visibilidade). |
| **Visibility** | Estado. | **Enable** (Torna visível), **Disable** (Esconde) ou **Toggle**. |

## Como configurar

1. **Ao**: contrário da `Action Change Object State`, esta ação apenas esconde o objeto visualmente. Os scripts e Triggers continuam a funcionar.

2. **Útil**: para efeitos de "fantasma" ou para esconder elementos visuais temporariamente.

