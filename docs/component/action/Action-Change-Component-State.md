# Action-Change-Component-State

[:material-code-tags: Ver Código Fonte C#](https://github.com/VideojogosLusofona/OkapiKit/blob/main/Assets/OkapiKit/Scripts/Actions/ActionChangeComponentState.cs){ .md-button }



Ativa ou desativa qualquer componente do Unity.

![Action Change Component State](../../assets/images/action/Action-Change-Component-State.png)

## Configurações do Inspector

| Campo | Função | Detalhes |
| :--- | :--- | :--- |
| **Active** | Ativação | Define se o componente está ligado e pronto para funcionar. |
| **Tags** | Etiquetas | Etiquetas inteligentes (Hypertags) usadas para identificação e filtros. |
| **Conditions** | Condições | Lista de requisitos (ex: variáveis ou tokens) que têm de ser verdadeiros para a execução. |
| **Target** | Alvo | O componente (Behaviour) que deseja ligar ou desligar. |
| **State** | Novo Estado | **Enable**: Ativa o componente. <br>**Disable**: Desativa o componente. <br>**Toggle**: Alterna o estado atual. |

## Como configurar

1. **Se**: tiver um script de "IA de Inimigo" ou uma "Luz de Alerta", pode usar esta ação para os ligar ou desligar rapidamente.

2. **Arraste**: o componente específico (não o objeto inteiro) para o campo **Target**.

