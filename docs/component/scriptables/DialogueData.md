# Dialogue Data

[:material-code-tags: Ver Código Fonte C#](https://github.com/VideojogosLusofona/OkapiKit/blob/main/Assets/OkapiKit/Scripts/Systems/Dialogue/DialogueData.cs){ .md-button }



Asset que armazena conversas, ramificações e escolhas.

## Como Criar

1. No Project View, clique com o botão direito.
2. Selecione `Create` -> `Okapi Kit` -> `Dialogue Data`.

## Estrutura do Diálogo

Cada asset pode conter múltiplas "conversas" identificadas por uma **Key** (Chave).

| Campo | Função | Detalhes |
| :--- | :--- | :--- |
| **Active** | Ativação | Define se o componente está ligado e pronto para funcionar. |
| **Tags** | Etiquetas | Etiquetas inteligentes (Hypertags) usadas para identificação e filtros. |
| **Conditions** | Condições | Lista de requisitos (ex: variáveis ou tokens) que têm de ser verdadeiros para a execução. |
| **Speaker** | Falante. | Asset de **Speaker** (nome e som) que está a falar. |
| **Text** | Texto. | A frase que será exibida no ecrã. |
| **Options** | Opções. | Escolhas que o jogador pode tomar, enviando a conversa para outra Key. |
| **Actions** | Ações. | Ações executadas no início ou fim daquela fala específica. |

## Como usar no jogo

1. Escreva as tuas conversas no asset de **Dialogue Data**.
2. Use uma **Action Talk** num trigger.
3. Nessa ação, arrasta o teu asset de **Dialogue Data** e escolhe a **Key** inicial da conversa.
