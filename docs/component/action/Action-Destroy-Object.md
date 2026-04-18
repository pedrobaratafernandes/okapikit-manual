# Action-Destroy-Object

[:material-code-tags: Ver Código Fonte C#](https://github.com/VideojogosLusofona/OkapiKit/blob/main/Assets/OkapiKit/Scripts/Actions/ActionDestroyObject.cs){ .md-button }



Remove um objeto da cena permanentemente.

![Action Destroy Object](../../assets/images/action/Action-Destroy-Object.png)

## Configurações do Inspector

| Campo | Função | Detalhes |
| :--- | :--- | :--- |
| **Active** | Ativação | Define se o componente está ligado e pronto para funcionar. |
| **Tags** | Etiquetas | Etiquetas inteligentes (Hypertags) usadas para identificação e filtros. |
| **Conditions** | Condições | Lista de requisitos (ex: variáveis ou tokens) que têm de ser verdadeiros para a execução. |
| **Target** | Quem Destruir. | **Self**, **Parent**, **Topmost**, **Object** (específico), **Tag**, **Collider** (objetivo que colidiu). |

## Como configurar

1. **Se**: quiser que um inimigo desapareça ao morrer, use o Target **Self**.

2. **Se**: quiser que um projétil destrua o que atingiu, use o Target **Collider** dentro de um `Trigger On Collision`.

3. **Cuidado**: Uma vez destruído, o objeto não pode ser recuperado (use a `Action Change Object State` se quiser apenas escondê-lo).

