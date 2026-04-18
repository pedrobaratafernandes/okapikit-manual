# Probe

[:material-code-tags: Ver Código Fonte C#](https://github.com/VideojogosLusofona/OkapiKit/blob/main/Assets/OkapiKit/Scripts/Systems/Probe.cs){ .md-button }



Deteta objetos numa direção específica sem usar o sistema de colisão física.

![Probe](../../assets/images/other/Probe.png)

## Configurações do Inspector

| Campo | Função | Detalhes |
| :--- | :--- | :--- |
| **Active** | Ativação | Define se o componente está ligado e pronto para funcionar. |
| **Tags** | Etiquetas | Etiquetas inteligentes (Hypertags) usadas para identificação e filtros. |
| **Conditions** | Condições | Lista de requisitos (ex: variáveis ou tokens) que têm de ser verdadeiros para a execução. |
| **Type** | Tipo. | **Raycast** (linha), **Circlecast** (círculo), **Colliders**. |
| **Direction** | Direção. | Para onde a sonda "aponta" (Relative, Absolute, Target). |
| **Distance** | Alcance. | Quão longe a sonda deteta objetos. |
| **Tags** | Filtro. | Quais Hypertags a sonda deve detetar. |

## Como configurar

1. **Útil**: para criar uma IA que "vê" se há um buraco à frente (sonda para baixo) ou se o jogador está na linha de visão.

2. **Pode**: ser usado para lasers: a sonda deteta o hit e o `Target Transform` move o sprite da faísca para esse ponto.

3. **Combine**: com um `Trigger On Condition` para verificar se `GetIntersectionState()` é verdadeiro e executar ações.

