# Grid System

[:material-code-tags: Ver Código Fonte C#](https://github.com/VideojogosLusofona/OkapiKit/blob/main/Assets/OkapiKit/Scripts/Systems/GridSystem.cs){ .md-button }



Gestor central de movimentos e colisões em grelha.

![Grid System](../../assets/images/other/GridSystem.png)

## Configurações do Inspector

| Campo | Função | Detalhes |
| :--- | :--- | :--- |
| **Active** | Ativação | Define se o componente está ligado e pronto para funcionar. |
| **Tags** | Etiquetas | Etiquetas inteligentes (Hypertags) usadas para identificação e filtros. |
| **Conditions** | Condições | Lista de requisitos (ex: variáveis ou tokens) que têm de ser verdadeiros para a execução. |
| **Grid Colliders** | Paredes. | Lista de colisores que o sistema lê como "obstáculos" na grelha. |

## Como configurar

1. **No**: Unity, este componente requer um componente padrão `Grid`.

2. **O**: campo **Cell Size** no componente `Grid` define o tamanho (em metros/unidades) de cada quadrado do seu jogo.

3. **Arraste**: para a lista **Grid Colliders** todos os objetos que definem os limites do seu mapa. O sistema transformará automaticamente essas áreas físicas em bloqueios na grelha.

4. **Todos**: os `Grid Objects` do seu jogo devem estar dentro da hierarquia deste objeto ou referenciá-lo.

