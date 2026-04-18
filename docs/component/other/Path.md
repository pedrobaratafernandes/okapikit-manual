# Path

[:material-code-tags: Ver Código Fonte C#](https://github.com/VideojogosLusofona/OkapiKit/blob/main/Assets/OkapiKit/Scripts/Systems/Path.cs){ .md-button }



Define uma trajetória (linha ou curva) para ser seguida por movimentos.

![Path](../../assets/images/other/Path.png)

## Configurações do Inspector

| Campo | Função | Detalhes |
| :--- | :--- | :--- |
| **Active** | Ativação | Define se o componente está ligado e pronto para funcionar. |
| **Tags** | Etiquetas | Etiquetas inteligentes (Hypertags) usadas para identificação e filtros. |
| **Conditions** | Condições | Lista de requisitos (ex: variáveis ou tokens) que têm de ser verdadeiros para a execução. |
| **Type** | Formato. | **Linear**, **Smooth** (curvas), **Circle**, **Arc**, **Polygon**. |
| **Closed** | Ciclo. | Se o último ponto se liga ao primeiro. |
| **Edit Mode** | Editar. | Ative para arrastar os pontos diretamente na janela **Scene**. |

## Como configurar

1. **Ative**: o **Edit Mode**.

2. **Na**: janela **Scene**, use os manipuladores para mover os pontos do caminho.

3. **Use**: os botões no Inspector para adicionar ou remover pontos.

4. **Use**: componentes como `Movement Path` ou `Movement Grid Path` para fazer um objeto seguir esta linha.

