# Camera Follow 2D

[:material-code-tags: Ver Código Fonte C#](https://github.com/VideojogosLusofona/OkapiKit/blob/main/Assets/OkapiKit/Scripts/Systems/CameraFollow2d.cs){ .md-button }



Faz com que a câmara siga um alvo (geralmente o jogador) com suavidade e limites.

![Camera Follow 2D](../../assets/images/other/CameraFollow2d.png)

## Configurações do Inspector

| Campo | Função | Detalhes |
| :--- | :--- | :--- |
| **Active** | Ativação | Define se o componente está ligado e pronto para funcionar. |
| **Tags** | Etiquetas | Etiquetas inteligentes (Hypertags) usadas para identificação e filtros. |
| **Conditions** | Condições | Lista de requisitos (ex: variáveis ou tokens) que têm de ser verdadeiros para a execução. |
| **Mode** | Tipo de Mov. | **Simple Feedback Loop** (suave), **Camera Trap** (caixa de atraso), **Exponential Decay**. |
| **Target Tag** | Tag Alvo. | A câmara foca nos objetos com esta tag. |
| **Follow Speed** | Velocidade. | Quão rápido a câmara alcança o alvo. |
| **Camera Limits** | Limites. | Arraste um `Box Collider 2D` para prender a câmara ao mapa. |

## Como configurar

1. **Coloque**: este componente no objeto da **Main Camera**.

2. **Certifique-se**: de que a câmara está em modo **Orthographic**.

3. **Defina**: o **Target Tag** como "Player".

4. **Se**: quiser limites de mapa, crie um objeto vazio com um `Box Collider 2D` (em modo Trigger) que cubra toda a área do nível e arraste-o para **Camera Limits**.

