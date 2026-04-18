# Action-Random

[:material-code-tags: Ver Código Fonte C#](https://github.com/VideojogosLusofona/OkapiKit/blob/main/Assets/OkapiKit/Scripts/Actions/ActionRandom.cs){ .md-button }



Executa uma ação aleatória de uma lista, baseada em pesos (probabilidade).

![Action Random](../../assets/images/action/Action-Random.png)

## Configurações do Inspector

| Campo | Função | Detalhes |
| :--- | :--- | :--- |
| **Active** | Ativação | Define se o componente está ligado e pronto para funcionar. |
| **Tags** | Etiquetas | Etiquetas inteligentes (Hypertags) usadas para identificação e filtros. |
| **Conditions** | Condições | Lista de requisitos (ex: variáveis ou tokens) que têm de ser verdadeiros para a execução. |
| **Actions** | Lista de Ações. | Lista de ações possíveis para escolher. |
| **Probability** | Peso. | Probabilidade relativa de cada ação ser escolhida (o sistema calcula a percentagem total). |

## Como configurar

1. **Adicione**: várias componentes de ação ao objeto.

2. **Na**: **Action Random**, clique no "+" para adicionar slots na lista.

3. **Arraste**: as ações que criou para os slots e defina as probabilidades.

4. **Ideal**: para criar "loots" aleatórios ou padrões de ataque de chefes.

