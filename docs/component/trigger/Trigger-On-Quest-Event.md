# Trigger-On-Quest-Event

[:material-code-tags: Ver Código Fonte C#](https://github.com/VideojogosLusofona/OkapiKit/blob/main/Assets/OkapiKit/Scripts/Triggers/TriggerOnQuestEvent.cs){ .md-button }



Dispara ações quando o estado de uma missão muda (início, fim ou falha).

![Trigger On Quest Event](../../assets/images/trigger/Trigger-On-Quest-Event.png)

## Configurações do Inspector

| Campo | Função | Detalhes |
| :--- | :--- | :--- |
| **Active** | Ativação | Define se o componente está ligado e pronto para funcionar. |
| **Tags** | Etiquetas | Etiquetas inteligentes (Hypertags) usadas para identificação e filtros. |
| **Conditions** | Condições | Lista de requisitos (ex: variáveis ou tokens) que têm de ser verdadeiros para a execução. |
| **Event Type** | Momento. | **Started** (começou), **Failed** (falhou), **Complete** (concluída). |
| **Quest** | Missão. | A missão específica a vigiar. Se vazio, vigia **qualquer** missão. |
| **Quest Manager** | Gestor. | O componente central de missões. |

## Como configurar

1. **Útil**: para mostrar uma mensagem de celebração na interface (`Action Change Object State`) quando uma missão termina.

2. **Pode**: ser usado para spawn de novos inimigos quando uma fase da história começa.

