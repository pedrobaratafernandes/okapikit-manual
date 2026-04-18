# Trigger-On-Condition

[:material-code-tags: Ver Código Fonte C#](https://github.com/VideojogosLusofona/OkapiKit/blob/main/Assets/OkapiKit/Scripts/Triggers/TriggerOnCondition.cs){ .md-button }



O **Trigger On Condition** verifica constantemente se um conjunto de regras é verdadeiro para disparar ações.

![Trigger On Condition](../../assets/images/trigger/Trigger-On-Condition.png)

## Configurações do Inspector

| Campo | Função | Detalhes |
| :--- | :--- | :--- |
| **Active** | Ativação | Define se o componente está ligado e pronto para funcionar. |
| **Tags** | Etiquetas | Etiquetas inteligentes (Hypertags) usadas para identificação e filtros. |
| **Conditions** | Condições | Lista de requisitos (ex: variáveis ou tokens) que têm de ser verdadeiros para a execução. |
| **Continuous** | Contínuo. | Se desativo, as ações só correm uma vez quando a condição se torna verdadeira. Se ativo, correm em todos os frames. |
| **Conditions** | Regras. | Lista de condições (ex: "Vida > 0" E "Tem Chave"). Todas devem ser verdadeiras (**AND**). |
| **Actions** | Sucesso. | O que acontece quando as condições são cumpridas. |
| **Else Actions** | Falha. | O que acontece quando as condições **NÃO** são cumpridas. |

## Como configurar

1. **Clique**: no botão "+" em **Conditions** para adicionar uma nova regra.

2. **Defina**: os valores a comparar (variáveis, estados de objetos, etc).

3. **Use**: a secção **Actions** para o caminho de "Sucesso" e **Else Actions** para o caminho de "Falha".

4. **Ideal**: para criar sistemas de portas trancadas, checkpoints ou estados de vitória/derrota.

