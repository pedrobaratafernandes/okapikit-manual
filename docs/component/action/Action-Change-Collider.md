# Action-Change-Collider 

[:material-code-tags: Ver Código Fonte C#](https://github.com/VideojogosLusofona/OkapiKit/blob/main/Assets/OkapiKit/Scripts/Actions/ActionChangeCollider.cs){ .md-button }



Modifica o estado do colisor, permitindo ligar ou desligar o modo "Trigger".

![Action Change Collider](../../assets/images/action/Action-Change-Collider.png)

## Configurações do Inspector

| Campo | Função | Detalhes |
| :--- | :--- | :--- |
| **Active** | Ativação | Define se o componente está ligado e pronto para funcionar. |
| **Tags** | Etiquetas | Etiquetas inteligentes (Hypertags) usadas para identificação e filtros. |
| **Conditions** | Condições | Lista de requisitos (ex: variáveis ou tokens) que têm de ser verdadeiros para a execução. |
| **Target** | Alvo. | O componente `Collider2D` que deseja modificar. |
| **State** | Propriedade. | O que alterar (ex: `Is Trigger`, `Enabled`). |
| **Change State** | Operação. | Como alterar: **Enable**, **Disable** ou **Toggle**. |

## Como configurar

1. **Útil**: para criar portas que se tornam atravessáveis após um evento, ou pontes que deixam de ser sólidas.

2. **Arraste**: o colisor alvo para o campo **Target**.

3. **Exemplo de Funcionamento**:

    * Se **State** estiver em `Is Trigger` e **Change State** em `Enable`, o objeto deixará de ser sólido (atravessável).
    * Se **State** estiver em `Is Trigger` e **Change State** em `Disable`, o objeto passará a ser sólido.
    * Se usar `Toggle`, o objeto alternará entre sólido e atravessável cada vez que a ação for disparada.
