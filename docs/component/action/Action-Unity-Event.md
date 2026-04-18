# Action-Unity-Event

[:material-code-tags: Ver Código Fonte C#](https://github.com/VideojogosLusofona/OkapiKit/blob/main/Assets/OkapiKit/Scripts/Actions/ActionUnityEvent.cs){ .md-button }



Chama qualquer função ou script externo ao OkapiKit. Funciona como uma "ponte" de integração.

![Action Run Unity Event](../../assets/images/action/Action-Unity-Event.png)

## Configurações do Inspector

| Campo | Função | Detalhes |
| :--- | :--- | :--- |
| **Active** | Ativação | Define se o componente está ligado e pronto para funcionar. |
| **Tags** | Etiquetas | Etiquetas inteligentes (Hypertags) usadas para identificação e filtros. |
| **Conditions** | Condições | Lista de requisitos (ex: variáveis ou tokens) que têm de ser verdadeiros para a execução. |
| **Unity Event** | Evento. | Lista padrão do Unity para arrastar objetos e escolher funções públicas. |

## Como configurar

1. **Arraste**: qualquer objeto da cena para a lista do evento.

2. **No**: menu suspenso, escolha a função que deseja chamar.

3. **Público**: Apenas funções marcadas como `public` nos scripts podem ser chamadas desta forma.

4. **Use**: isto se precisar de ativar um sistema externo (ex: um plugin de anúncios ou um sistema de saves personalizado) através do OkapiKit.

