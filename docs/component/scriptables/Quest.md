# Quest

[:material-code-tags: Ver Código Fonte C#](https://github.com/VideojogosLusofona/OkapiKit/blob/main/Assets/OkapiKit/Scripts/Variables/Quest.cs){ .md-button }



Asset que define os objetivos, requisitos e recompensas de uma missão.

## Configurações do Inspector

| Campo | Função | Detalhes |
| :--- | :--- | :--- |
| **Active** | Ativação | Define se o componente está ligado e pronto para funcionar. |
| **Tags** | Etiquetas | Etiquetas inteligentes (Hypertags) usadas para identificação e filtros. |
| **Conditions** | Condições | Lista de requisitos (ex: variáveis ou tokens) que têm de ser verdadeiros para a execução. |
| **Name** | Título. | O nome que aparece no log de missões. |
| **Description** | Descrição. | Explicação dos objetivos para o jogador. |
| **Objectives** | Objetivos. | Lista de itens (Assets) ou Tokens (Hypertags) necessários. |
| **Required Quests**| Pré-requisitos. | Outras missões que devem estar completas antes desta. |

## Como Criar

1. No Project View, clique com o botão direito.
2. Selecione `Create` -> `Okapi Kit` -> `Quest`.
3. Adicione objetivos (ex: Coletar 5 "Moedas" ou Obter 1 "Chave Mestra").
4. **Nota**: O progresso é gerido automaticamente pelo `Quest Manager`.
