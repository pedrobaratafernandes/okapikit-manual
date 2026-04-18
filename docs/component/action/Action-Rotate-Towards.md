# Action-Rotate-Towards

[:material-code-tags: Ver Código Fonte C#](https://github.com/VideojogosLusofona/OkapiKit/blob/main/Assets/OkapiKit/Scripts/Actions/ActionRotateTowards.cs){ .md-button }



Roda o objeto para apontar na direção de um alvo.

![Action Rotate Towards](../../assets/images/action/Action-Rotate-Towards.png)

## Configurações do Inspector

| Campo | Função | Detalhes |
| :--- | :--- | :--- |
| **Active** | Ativação | Define se o componente está ligado e pronto para funcionar. |
| **Tags** | Etiquetas | Etiquetas inteligentes (Hypertags) usadas para identificação e filtros. |
| **Conditions** | Condições | Lista de requisitos (ex: variáveis ou tokens) que têm de ser verdadeiros para a execução. |
| **Target Object** | Alvo. | Objeto específico para onde olhar. |
| **Target Tag** | Tag Alvo. | Se definido, aponta para o objeto mais próximo com esta tag. |
| **Axis to Align** | Eixo. | **Up Axis** (Y) ou **Right Axis** (X). |
| **Has Max Speed** | Gradual? | Se ativo, roda suavemente. Se não, é instantâneo. |
| **Speed** | Velocidade. | Graus por segundo (se gradual). |

## Como configurar

1. **Essencial**: para que os inimigos "olhem" para o jogador antes de dispararem.

2. **Se**: estiver a usar sprites 2D que olham para a direita, escolha **Right Axis**. Se olham para cima, escolha **Up Axis**.

