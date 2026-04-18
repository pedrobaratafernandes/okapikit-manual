# Item

[:material-code-tags: Ver Código Fonte C#](https://github.com/VideojogosLusofona/OkapiKit/blob/main/Assets/OkapiKit/Scripts/Variables/Item.cs){ .md-button }



Asset que define as propriedades de um objeto recolhível ou equipável.

## Configurações do Inspector

| Campo | Função | Detalhes |
| :--- | :--- | :--- |
| **Active** | Ativação | Define se o componente está ligado e pronto para funcionar. |
| **Tags** | Etiquetas | Etiquetas inteligentes (Hypertags) usadas para identificação e filtros. |
| **Conditions** | Condições | Lista de requisitos (ex: variáveis ou tokens) que têm de ser verdadeiros para a execução. |
| **Name** | Nome de Jogo.| O nome que aparece na UI. |
| **Icon** | Ícone. | A imagem que representa o item no inventário. |
| **Stackable** | Acumulável. | Se o jogador pode carregar várias unidades no mesmo slot. |
| **Tags** | Categorias. | Hypertags que definem que tipo de item é (ex: "Consumível", "Arma"). |

## Como Criar

1. No Project View, clique com o botão direito.
2. Selecione `Create` -> `Okapi Kit` -> `Item`.
3. Configure o ícone e se o item é acumulável.
