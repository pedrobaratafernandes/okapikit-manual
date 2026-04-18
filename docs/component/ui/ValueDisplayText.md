# Value Display Text

[:material-code-tags: Ver Código Fonte C#](https://github.com/VideojogosLusofona/OkapiKit/blob/main/Assets/OkapiKit/Scripts/UI/ValueDisplayText.cs){ .md-button }



Exibe o valor de uma única variável num campo de texto (pontuações, cronómetros).

![Value Display Text](../../assets/images/ui/ValueDisplayText.png)

## Configurações do Inspector

| Campo | Função | Detalhes |
| :--- | :--- | :--- |
| **Active** | Ativação | Define se o componente está ligado e pronto para funcionar. |
| **Tags** | Etiquetas | Etiquetas inteligentes (Hypertags) usadas para identificação e filtros. |
| **Conditions** | Condições | Lista de requisitos (ex: variáveis ou tokens) que têm de ser verdadeiros para a execução. |
| **Var. Instance / Variable**| Fonte. | Escolha entre uma variável local (no objeto) ou global (asset). |
| **Description** | Descrição. | Campo para notas internas do desenvolvedor. |
| **(TextMeshPro)** | Saída. | O valor será escrito no componente de texto presente no objeto. |

## Como configurar

1. **Requer**: um componente `TextMeshPro - Text (UI)` no mesmo objeto.

2. **No**: campo de texto do componente `TextMeshPro`, use `{0}` para indicar onde o número deve aparecer.

3. **Exemplos**: de formatação:

    - `{0}`: Número normal.
    - `{0:000}`: Sempre 3 algarismos (ex: "005").
    - `{0:F2}`: 2 casas decimais (ex: "10.50").
