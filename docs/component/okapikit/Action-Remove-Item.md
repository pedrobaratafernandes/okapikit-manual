# Action-Remove-Item

[:material-code-tags: Ver Código Fonte C#](https://github.com/VideojogosLusofona/OkapiKit/blob/main/Assets/OkapiKit/Scripts/Actions/ActionRemoveItem.cs){ .md-button }



Ação para remover um item ou quantidade específica de um inventário.

![Action Remove Item](../../assets/images/okapikit/Action-Remove-Item.png)

## Configurações do Inspector

| Campo | Função | Detalhes |
| :--- | :--- | :--- |
| **Active** | Ativação | Define se o componente está ligado e pronto para funcionar. |
| **Tags** | Etiquetas | Etiquetas inteligentes (Hypertags) usadas para identificação e filtros. |
| **Conditions** | Condições | Lista de requisitos (ex: variáveis ou tokens) que têm de ser verdadeiros para a execução. |
| **Item** | Item | O asset de **Item** (Scriptable-Object) que será removido. |
| **Quantity** | Quantidade | Número de unidades do item a retirar do inventário. |
| **Inventory** | Inventário | O inventário onde o item será procurado (via Hyper-Tag ou Objeto). |

## Como configurar

1. **Definir o Item**: Arraste o asset do item que deseja remover para o slot **Item**.

2. **Quantidade**: Defina quantas unidades devem ser removidas (ex: 10 moedas).

3. **Alvo**: Configure o campo **Inventory** para apontar para o inventário do jogador (geralmente usando uma Hyper-Tag "Player").

4. **Segurança**: É recomendado usar esta ação num Trigger que tenha uma condição **Has-Item** ou **Check-Value** anterior, para garantir que o jogador tem o que vai ser removido.

