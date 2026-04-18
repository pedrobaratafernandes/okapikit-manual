# Singleton

[:material-code-tags: Ver Código Fonte C#](https://github.com/VideojogosLusofona/OkapiKit/blob/main/Assets/OkapiKit/Scripts/Systems/Singleton.cs){ .md-button }



Garante que apenas existe uma instância de um objeto no jogo, mantendo-o entre cenas.

![Singleton](../../assets/images/other/Singleton.png)

## Configurações do Inspector

| Campo | Função | Detalhes |
| :--- | :--- | :--- |
| **Active** | Ativação | Define se o componente está ligado e pronto para funcionar. |
| **Tags** | Etiquetas | Etiquetas inteligentes (Hypertags) usadas para identificação e filtros. |
| **Conditions** | Condições | Lista de requisitos (ex: variáveis ou tokens) que têm de ser verdadeiros para a execução. |
| **Singleton Tag** | Identificador. | A tag que identifica este Singleton (ex: "GameManager", "SoundManager"). |

## Como configurar

1. **Use**: isto para objetos que devem manter o estado entre níveis, como o `SoundManager`, o `QuestManager` ou o próprio jogador.

2. **Importante**: Um objeto Singleton não pode ter um "pai" no Unity (deve estar na raiz da hierarquia).

3. **Se**: o objeto tiver esta componente, ele aparecerá em todos os níveis assim que for criado no primeiro, sem precisar de ser colocado manualmente em todas as cenas.

