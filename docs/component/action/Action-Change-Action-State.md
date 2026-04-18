# Action-Change-Action-State 

[:material-code-tags: Ver Código Fonte C#](https://github.com/VideojogosLusofona/OkapiKit/blob/main/Assets/OkapiKit/Scripts/Actions/ActionChangeActionState.cs){ .md-button }



Ativa ou desativa outro componente de Ação.

![Action Change Action State](../../assets/images/action/Action-Change-Action-State.png)

## Configurações do Inspector

| Campo | Função | Detalhes |
| :--- | :--- | :--- |
| **Active** | Ativação | Define se o componente está ligado e pronto para funcionar. |
| **Tags** | Etiquetas | Etiquetas inteligentes (Hypertags) usadas para identificação e filtros. |
| **Conditions** | Condições | Lista de requisitos (ex: variáveis ou tokens) que têm de ser verdadeiros para a execução. |
| **Target** | Alvo. | O componente `Action` alvo. |
| **State** | Novo Estado. | **Enable**, **Disable** ou **Toggle**. |

## Como configurar

1. **Arraste**: a ação que deseja controlar para o campo **Target**.

2. **Escolha**: se quer ativar ou desativar.

3. **Útil**: para, por exemplo, impedir que o jogador dispare (desativando a ação de tiro) durante uma conversa ou animação.

