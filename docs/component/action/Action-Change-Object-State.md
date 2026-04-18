# Action-Change-Object-State

[:material-code-tags: Ver Código Fonte C#](https://github.com/VideojogosLusofona/OkapiKit/blob/main/Assets/OkapiKit/Scripts/Actions/ActionChangeObjectState.cs){ .md-button }



Ativa ou desativa completamente um objeto da cena (GameObject).

![Action Change Object State](../../assets/images/action/Action-Change-Object-State.png)

## Configurações do Inspector

| Campo | Função | Detalhes |
| :--- | :--- | :--- |
| **Active** | Ativação | Define se o componente está ligado e pronto para funcionar. |
| **Tags** | Etiquetas | Etiquetas inteligentes (Hypertags) usadas para identificação e filtros. |
| **Conditions** | Condições | Lista de requisitos (ex: variáveis ou tokens) que têm de ser verdadeiros para a execução. |
| **Target** | Objeto Alvo. | O Game Object que deseja ligar ou desligar. |
| **State** | Novo Estado. | **Enable**, **Disable** ou **Toggle**. |

## Como configurar

1. **Útil**: para fazer aparecer portais, inimigos escondidos ou para remover objetos da cena sem os destruir permanentemente.

2. **Lembre-se**: que se desativar o objeto onde está o trigger, ele não poderá reativar-se a si próprio (porque parou de funcionar!).

