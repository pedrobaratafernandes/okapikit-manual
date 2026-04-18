# Action-Change-Trigger-State 

[:material-code-tags: Ver Código Fonte C#](https://github.com/VideojogosLusofona/OkapiKit/blob/main/Assets/OkapiKit/Scripts/Actions/ActionChangeTriggerState.cs){ .md-button }



Esta ação permite ativar, desativar ou inverter o estado de um **Trigger**. É muito útil para ligar armadilhas, ativar portais ou alternar entre comportamentos de IA quando certas condições são atingidas.

![Change Trigger State Action](../../assets/images/action/Action-Change-Trigger-State.png)

## Configurações do Inspector

| Campo | Descrição | Detalhes |
| :--- | :--- | :--- |
| **Active** | Ativação | Define se o componente está ligado e pronto para funcionar. |
| **Tags** | Etiquetas | Etiquetas inteligentes (Hypertags) usadas para identificação e filtros. |
| **Conditions** | Condições | Lista de requisitos (ex: variáveis ou tokens) que têm de ser verdadeiros para a execução. |
| **Active** | Ativa a ação. | Se desativado, esta ação nunca será executada. |
| **Tags** | Ativa o sistema de etiquetas. | Permite identificar esta ação com uma etiqueta para ser chamada por outras ações (ex: `Action Tagged`). |
| **Conditions** | Condições de execução. | Define os requisitos necessários para que esta ação seja executada. |
| **Target** | Trigger Alvo. | O componente Trigger que deseja modificar. |
| **State** | Novo Estado. | **Enable**: Ativa o trigger. **Disable**: Desativa o trigger. **Toggle**: Inverte o estado atual. |
| **Description** | Notas do utilizador. | Campo para anotações internas. |

## Como configurar

1. **Crie**: um objeto com um **Trigger** (ex: um `OnTimerTrigger` que dispara setas).

2. **Noutro**: objeto, adicione a ação **Change Trigger State Action**.

3. **Arraste**: o trigger do primeiro objeto para o campo **Target**.

4. **Defina**: o **State** (ex: **Disable** para desligar a armadilha).

5. **Configure**: um evento (ex: o jogador pisar um botão) para executar esta ação.

