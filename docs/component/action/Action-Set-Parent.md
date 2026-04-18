# Action-Set-Parent

[:material-code-tags: Ver Código Fonte C#](https://github.com/VideojogosLusofona/OkapiKit/blob/main/Assets/OkapiKit/Scripts/Actions/ActionSetParent.cs){ .md-button }



Muda a hierarquia de um objeto, definindo um novo "pai".

![Action Set Parent](../../assets/images/action/Action-Set-Parent.png)

## Configurações do Inspector

| Campo | Função | Detalhes |
| :--- | :--- | :--- |
| **Active** | Ativação | Define se o componente está ligado e pronto para funcionar. |
| **Tags** | Etiquetas | Etiquetas inteligentes (Hypertags) usadas para identificação e filtros. |
| **Conditions** | Condições | Lista de requisitos (ex: variáveis ou tokens) que têm de ser verdadeiros para a execução. |
| **Target Object** | Objeto. | O objeto que mudará de pai. |
| **New Parent**| Novo Pai. | Pode ser definido por **Tag** ou por referência direta ao objeto. |

## Como configurar

1. **Útil**: para fazer com que o jogador "monte" num veículo (tornando o jogador filho do veículo) ou para que um objeto apanhado fique "colado" à mão de um personagem.

2. **Quando**: um objeto se torna filho de outro, ele move-se e roda juntamente com o pai.

