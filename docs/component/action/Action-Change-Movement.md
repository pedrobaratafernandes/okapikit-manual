# Action-Change-Movement 

[:material-code-tags: Ver Código Fonte C#](https://github.com/VideojogosLusofona/OkapiKit/blob/main/Assets/OkapiKit/Scripts/Actions/ActionChangeMovement.cs){ .md-button }



Modifica as propriedades de movimento de um objeto em tempo real. **Atenção**: Esta ação altera os parâmetros do movimento, não apenas a velocidade momentânea.

![Action Change Movement](../../assets/images/action/Action-Change-Movement.png)

## Configurações do Inspector

| Campo | Função | Detalhes |
| :--- | :--- | :--- |
| **Active** | Ativação | Define se o componente está ligado e pronto para funcionar. |
| **Tags** | Etiquetas | Etiquetas inteligentes (Hypertags) usadas para identificação e filtros. |
| **Conditions** | Condições | Lista de requisitos (ex: variáveis ou tokens) que têm de ser verdadeiros para a execução. |
| **Movement Comp.** | Movimento. | Componente de movimento (Platformer, XY) a alterar. |
| **Rigidbody Comp.** | Física. | Componente Rigidbody2D a alterar. |
| **Change Type** | Tipo. | Atualmente focado em **Velocity** (parâmetros de base). |
| **Operation** | Operação. | **Set** (fixo), **Add** (somar), **Subtract** (subtrair). |
| **Use Rotation** | Rotação. | Se ativo, as direções são relativas ao objeto. |
| **Angular random** | Aleatório. | Aplica variação angular aleatória na velocidade. |
| **Min Velocity** | Vel. Mínima. | Valor mínimo (X, Y) para a nova velocidade. |
| **Max Velocity** | Vel. Máxima. | Valor máximo (X, Y). O resultado será entre Mín e Máx. |

## Como configurar

1. **Use**: esta ação para criar efeitos de "impulso" (boost), zonas de baixa gravidade ou para teleportar um objeto dando-lhe uma velocidade inicial.

2. **Note**: que esta ação altera os **parâmetros** do movimento, não apenas a velocidade momentânea. Para impulsos físicos puros, veja a `Action Change Rigid Body`.

