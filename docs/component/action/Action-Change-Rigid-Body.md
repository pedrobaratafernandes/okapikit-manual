# Action-Change-Rigid-Body

[:material-code-tags: Ver Código Fonte C#](https://github.com/VideojogosLusofona/OkapiKit/blob/main/Assets/OkapiKit/Scripts/Actions/ActionChangeRigidBody.cs){ .md-button }



Manipula propriedades físicas de um Rigidbody2D.

![Action Change Rigid Body](../../assets/images/action/Action-Change-Rigid-Body.png)

## Configurações do Inspector

| Campo | Função | Detalhes |
| :--- | :--- | :--- |
| **Active** | Ativação | Define se o componente está ligado e pronto para funcionar. |
| **Tags** | Etiquetas | Etiquetas inteligentes (Hypertags) usadas para identificação e filtros. |
| **Conditions** | Condições | Lista de requisitos (ex: variáveis ou tokens) que têm de ser verdadeiros para a execução. |
| **Target** | Rigidbody. | O componente físico a modificar. |
| **Change Type** | Tipo. | **Velocity Set**: Define velocidade bruta.<br>**Mass**: Muda o peso.<br>**Linear Drag**: Muda a resistência ao ar.<br>**Body Type**: Alterna entre Dynamic, Static e Kinematic. |
| **Operation** | Operação. | **Set**, **Add**, **Subtract**, **Multiply**, **Divide**. |
| **Value** | Valor. | O valor numérico a aplicar. |
| **Axis** | Direção (Vel.). | Define em que eixo o impulso é aplicado. |

## Como configurar

1. **Use**: esta ação para criar ventos que empurram o jogador (alterando a velocidade) ou para tornar um objeto "imóvel" mudando o seu `Body Type` para `Static`.

2. **Para**: impulsos físicos puros, esta ação é preferível a mexer diretamente no Transform.

