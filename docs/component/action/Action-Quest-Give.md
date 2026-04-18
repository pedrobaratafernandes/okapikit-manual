# Action-Quest-Give

[:material-code-tags: Ver Código Fonte C#](https://github.com/VideojogosLusofona/OkapiKit/blob/main/Assets/OkapiKit/Scripts/Actions/ActionQuestGive.cs){ .md-button }



Adiciona uma nova missão ao diário do jogador.

![Action Quest Give](../../assets/images/action/Action-Quest-Give.png)

## Configurações do Inspector

| Campo | Função | Detalhes |
| :--- | :--- | :--- |
| **Active** | Ativação | Define se o componente está ligado e pronto para funcionar. |
| **Tags** | Etiquetas | Etiquetas inteligentes (Hypertags) usadas para identificação e filtros. |
| **Conditions** | Condições | Lista de requisitos (ex: variáveis ou tokens) que têm de ser verdadeiros para a execução. |
| **Quest Manager** | Gestor. | O componente que gere as missões (habitualmente um objeto global). |
| **Quest** | Missão. | O recurso da missão (Quest Asset) que deve ser atribuída ao jogador. |

## Como configurar

1. **Habitualmente**: ativada por um Trigger de diálogo ou quando o jogador entra numa determinada área.

2. **Certifique-se**: de que a missão já está criada no projeto antes de a tentar atribuir.

