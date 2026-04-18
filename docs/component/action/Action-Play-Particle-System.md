# Action-Play-Particle-System

[:material-code-tags: Ver Código Fonte C#](https://github.com/VideojogosLusofona/OkapiKit/blob/main/Assets/OkapiKit/Scripts/Actions/ActionPlayParticleSystem.cs){ .md-button }



Inicia a reprodução de um sistema de partículas existente.

![Action Play Particle System](../../assets/images/action/Action-Play-Particle-System.png)

## Configurações do Inspector

| Campo | Função | Detalhes |
| :--- | :--- | :--- |
| **Active** | Ativação | Define se o componente está ligado e pronto para funcionar. |
| **Tags** | Etiquetas | Etiquetas inteligentes (Hypertags) usadas para identificação e filtros. |
| **Conditions** | Condições | Lista de requisitos (ex: variáveis ou tokens) que têm de ser verdadeiros para a execução. |
| **Target** | Sistema. | O `ParticleSystem` a tocar. |

## Como configurar

1. **Diferente**: da `Action Spawn` (que cria algo novo), esta ação apenas ativa algo que já existe mas está parado.

2. **Certifique-se**: de que o sistema de partículas não tem a opção "Play on Awake" ligada se quiser que ele só comece através desta ação.

