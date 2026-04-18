# Value Display Progress

[:material-code-tags: Ver Código Fonte C#](https://github.com/VideojogosLusofona/OkapiKit/blob/main/Assets/OkapiKit/Scripts/UI/ValueDisplayProgress.cs){ .md-button }



Cria barras de vida ou energia que enchem e esvaziam dinamicamente.

![Value Display Progress](../../assets/images/ui/ValueDisplayProgress.png)

## Configurações do Inspector

| Campo | Função | Detalhes |
| :--- | :--- | :--- |
| **Active** | Ativação | Define se o componente está ligado e pronto para funcionar. |
| **Tags** | Etiquetas | Etiquetas inteligentes (Hypertags) usadas para identificação e filtros. |
| **Conditions** | Condições | Lista de requisitos (ex: variáveis ou tokens) que têm de ser verdadeiros para a execução. |
| **Var. Instance / Variable**| Fonte. | Escolha entre uma variável local (no objeto) ou global (asset). |
| **Fill** | Barra. | O objeto `RectTransform` que vai esticar/encolher (a barra). |
| **Set color?** | Mudar Cor. | Se ativo, permite alterar a cor da barra dependendo do valor. |
| **Description** | Descrição. | Campo para notas internas do desenvolvedor. |

## Como configurar

1. **Configure**: a sua variável para ter um **Min Value** (ex: 0) e um **Max Value** (ex: 100).

2. **O**: componente de imagem usado no **Fill** deve ter o seu Pivot definido no lado esquerdo (0, 0.5) para que a barra cresça para a direita.

3. **É**: a forma mais visual de mostrar valores contínuos ao jogador.

