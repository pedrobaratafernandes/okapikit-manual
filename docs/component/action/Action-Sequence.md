# Action-Sequence

[:material-code-tags: Ver Código Fonte C#](https://github.com/VideojogosLusofona/OkapiKit/blob/main/Assets/OkapiKit/Scripts/Actions/ActionSequence.cs){ .md-button }



Executa várias ações em série com intervalos de tempo.

![Action Sequence](../../assets/images/action/Action-Sequence.png)

## Configurações do Inspector

| Campo | Função | Detalhes |
| :--- | :--- | :--- |
| **Active** | Ativação | Define se o componente está ligado e pronto para funcionar. |
| **Tags** | Etiquetas | Etiquetas inteligentes (Hypertags) usadas para identificação e filtros. |
| **Conditions** | Condições | Lista de requisitos (ex: variáveis ou tokens) que têm de ser verdadeiros para a execução. |
| **Actions** | Lista de Ações. | Sequência de ações a serem executadas. |
| **Delay** | Atraso. | Tempo de espera (em segundos) antes de cada ação ser disparada. |

## Como configurar

1. **Adicione**: a **Action Sequence** ao objeto.

2. **Adicione**: as ações individuais (ex: `Action Play Sound`, `Action Destroy Object`) ao mesmo objeto ou a outros.

3. **Arraste**: essas ações para a lista na **Action Sequence**.

4. **Defina**: os tempos. Por exemplo:

    - Som: Delay 0s.
    - Partículas: Delay 0s.
    - Destruir: Delay 0.5s (para dar tempo de ouvir o som).
