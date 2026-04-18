# Grid Object

[:material-code-tags: Ver Código Fonte C#](https://github.com/VideojogosLusofona/OkapiKit/blob/main/Assets/OkapiKit/Scripts/Systems/GridObject.cs){ .md-button }



Define um objeto como participante no sistema de grelha.

![Grid Object](../../assets/images/other/GridObject.png)

## Configurações do Inspector

| Campo | Função | Detalhes |
| :--- | :--- | :--- |
| **Active** | Ativação | Define se o componente está ligado e pronto para funcionar. |
| **Tags** | Etiquetas | Etiquetas inteligentes (Hypertags) usadas para identificação e filtros. |
| **Conditions** | Condições | Lista de requisitos (ex: variáveis ou tokens) que têm de ser verdadeiros para a execução. |
| **Pivot** | Pivot. | Ponto de alinhamento com a célula da grelha (Center, TopLeft, etc). |
| **Can Push** | Empurrável. | Se o objeto pode ser movido por outros. |
| **Mass** | Massa. | Define a força necessária para empurrar este objeto. |

## Como configurar

1. **O**: objeto deve ser filho de um objeto que tenha o componente `Grid System`.

2. **O**: **Pivot** deve coincidir com o design do seu sprite para que ele fique bem alinhado nos quadrados.

3. **Se**: quiser que o jogador empurre caixas, as caixas devem ter **Can Push** ativo.

