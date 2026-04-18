# Action-Change-Tile

[:material-code-tags: Ver Código Fonte C#](https://github.com/VideojogosLusofona/OkapiKit/blob/main/Assets/OkapiKit/Scripts/Actions/ActionChangeTile.cs){ .md-button }



Substitui tiles (quadrados) num Tilemap. Ideal para cenários destrutíveis.

![Action Change Tile](../../assets/images/action/Action-Change-Tile.png)

## Configurações do Inspector

| Campo | Função | Detalhes |
| :--- | :--- | :--- |
| **Active** | Ativação | Define se o componente está ligado e pronto para funcionar. |
| **Tags** | Etiquetas | Etiquetas inteligentes (Hypertags) usadas para identificação e filtros. |
| **Conditions** | Condições | Lista de requisitos (ex: variáveis ou tokens) que têm de ser verdadeiros para a execução. |
| **Tilemap** | Mapa de Tiles. | O componente Tilemap a modificar. |
| **Vicinity Type** | Área Afetada. | **Single**: Apenas um tile.<br>**FourWay / EightWay**: Tiles adjacentes.<br>**Circle**: Todos os tiles num raio. |
| **Radius** | Raio. | Tamanho da área afetada (para o modo Circle). |
| **Rules** | Regras de Troca. | Lista de "Trocar Tile A por Tile B". |

## Como configurar

1. **Requer**: que o objeto tenha um componente `Grid Object`.

2. **Configure**: as regras na lista **Rules**. Cada regra diz: "se encontrares o Tile A, muda para o Tile B".

3. **Ideal**: para mecânicas de mineração, rasto de fogo ou construção de caminhos.

