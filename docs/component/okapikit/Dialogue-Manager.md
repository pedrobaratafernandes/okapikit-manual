# Dialogue-Manager

[:material-code-tags: Ver Código Fonte C#](https://github.com/VideojogosLusofona/OkapiKit/blob/main/Assets/OkapiKit/Scripts/Systems/DialogueManager.cs){ .md-button }



O gestor central que conecta os dados das conversas à interface de utilizador (UI).

![Dialogue Manager](../../assets/images/okapikit/DialogueManager.png)

## Configurações do Inspector

| Campo | Função | Detalhes |
| :--- | :--- | :--- |
| **Active** | Ativação | Define se o componente está ligado e pronto para funcionar. |
| **Tags** | Etiquetas | Etiquetas inteligentes (Hypertags) usadas para identificação e filtros. |
| **Conditions** | Condições | Lista de requisitos (ex: variáveis ou tokens) que têm de ser verdadeiros para a execução. |
| **Dialogue-Data** | Base de Dados | Lista de ficheiros **Dialogue-Data** (Scriptable-Objects) que contêm as falas do jogo. |
| **Display** | Interface | O componente (ex: **Dialogue-Display-JRPG**) que será responsável por desenhar as mensagens no ecrã. |

## Como configurar

1. **Objeto Persistence**: Recomenda-se colocar o **Dialogue-Manager** num objeto que não seja destruído entre cenas (ou usar o prefab GameManager padrão).

2. **Importar Falas**: Crie ativos de **Dialogue-Data** e arraste-os para a lista. No OkapiKit, os diálogos são identificados por uma **Chave (Key)** única dentro destes ficheiros.

3. **Ligar ao Visual**: Arraste um objeto da sua UI que tenha o componente **Dialogue-Display-JRPG** para o campo **Display**.

4. **Acionar**: Para iniciar uma conversa, use a ação **Action-Talk** num NPC ou num evento.

