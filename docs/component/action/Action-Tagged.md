# Action-Tagged

[:material-code-tags: Ver Código Fonte C#](https://github.com/VideojogosLusofona/OkapiKit/blob/main/Assets/OkapiKit/Scripts/Actions/ActionTagged.cs){ .md-button }



Executa ações noutros objetos baseando-se em etiquetas (Hypertags). Funciona como um sistema de "broadcast".

![Action Run Tagged Action](../../assets/images/action/Action-Tagged.png)

## Configurações do Inspector

| Campo | Função | Detalhes |
| :--- | :--- | :--- |
| **Active** | Ativação | Define se o componente está ligado e pronto para funcionar. |
| **Tags** | Etiquetas | Etiquetas inteligentes (Hypertags) usadas para identificação e filtros. |
| **Conditions** | Condições | Lista de requisitos (ex: variáveis ou tokens) que têm de ser verdadeiros para a execução. |
| **Search Type** | Onde Procurar. | **Global**, **Children**, **Tagged** (em objetos com X tag), **Within Collider**, **Collision Object**. |
| **Search Tags** | Tags de Busca. | Tags dos objetos onde as ações estão. |
| **Trigger Type** | Como Ativar. | **All**, **Sequence** (rotativo), **Random**. |
| **Trigger Tags** | Tags da Ação. | Tags das próprias componentes `Action` a ativar. |

## Como configurar

1. **No**: objeto de destino, certifique-se de que o componente Action tem uma etiqueta (Hypertags).

2. **Na**: **Action Run Tagged Action**, defina essa mesma etiqueta em **Trigger Tags**.

3. **Escolha**: o **Search Type** adequado (habitualmente *Global* para eventos simples).

4. **É**: ideal para criar eventos globais sem que os objetos precisem de se conhecer uns aos outros.

