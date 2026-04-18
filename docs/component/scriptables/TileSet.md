# Tile Set

[:material-code-tags: Ver Código Fonte C#](https://github.com/VideojogosLusofona/OkapiKit/blob/main/Assets/OkapiKit/Scripts/Variables/TileSet.cs){ .md-button }



Asset que agrupa múltiplos Tiles do Unity sob um único nome para facilitar a deteção de terrenos.

## Função

Em vez de verificares cada tile individualmente (ex: Grama_1, Grama_2), crias um **Tile Set** chamado "Chão" e adicionas todos esses tiles à lista.

## Configurações do Inspector

| Campo | Função | Detalhes |
| :--- | :--- | :--- |
| **Active** | Ativação | Define se o componente está ligado e pronto para funcionar. |
| **Tags** | Etiquetas | Etiquetas inteligentes (Hypertags) usadas para identificação e filtros. |
| **Conditions** | Condições | Lista de requisitos (ex: variáveis ou tokens) que têm de ser verdadeiros para a execução. |
| **Tiles** | Lista. | Arraste todos os assets de Tile (da tua palete de Tilemap) que fazem parte deste grupo. |

## Como configurar

1. **Cria**: o asset em `Create` -> `Okapi Kit` -> `Tile Set`.

2. **Adiciona**: os tiles desejados à lista no Inspector.

3. **Use**: este Tile Set em componentes como o `Movement Platformer` para definir rapidamente o que é considerado "Chão".

