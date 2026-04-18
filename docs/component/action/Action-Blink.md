# Action-Blink 

[:material-code-tags: Ver Código Fonte C#](https://github.com/VideojogosLusofona/OkapiKit/blob/main/Assets/OkapiKit/Scripts/Actions/ActionBlink.cs){ .md-button }



Faz com que o renderizador de um objeto pisque (intermitência visual).

![Action Blink](../../assets/images/action/Action-Blink.png)

## Configurações do Inspector

| Campo | Função | Detalhes |
| :--- | :--- | :--- |
| **Active** | Ativação | Define se o componente está ligado e pronto para funcionar. |
| **Tags** | Etiquetas | Etiquetas inteligentes (Hypertags) usadas para identificação e filtros. |
| **Conditions** | Condições | Lista de requisitos (ex: variáveis ou tokens) que têm de ser verdadeiros para a execução. |
| **Target** | Alvo. | O componente visual (Renderer) que irá piscar. |
| **Include Children?**| Filhos. | Se ativo, renderizadores nos objetos filhos também piscam. |
| **On Duration** | Ligado. | Tempo (segundos) visível em cada ciclo. |
| **Off Duration** | Desligado. | Tempo (segundos) invisível em cada ciclo. |
| **Duration** | Total. | Tempo total em segundos que o efeito dura. |

## Como configurar

1. **Adicione**: o componente a um objeto que tenha um renderizador (ex: Sprite Renderer).

2. **Configure**: a **Duration** (ex: 2 segundos).

3. **Ative**: esta ação através de um trigger, como o `Trigger On Collision` (quando o jogador toca num inimigo).

