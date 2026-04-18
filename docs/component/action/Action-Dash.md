# Action-Dash

[:material-code-tags: Ver Código Fonte C#](https://github.com/VideojogosLusofona/OkapiKit/blob/main/Assets/OkapiKit/Scripts/Actions/ActionDash.cs){ .md-button }



Realiza um movimento rápido de impulso numa direção específica.

![Action Dash](../../assets/images/action/Action-Dash.png)

## Configurações do Inspector

| Campo | Função | Detalhes |
| :--- | :--- | :--- |
| **Active** | Ativação | Define se o componente está ligado e pronto para funcionar. |
| **Tags** | Etiquetas | Etiquetas inteligentes (Hypertags) usadas para identificação e filtros. |
| **Conditions** | Condições | Lista de requisitos (ex: variáveis ou tokens) que têm de ser verdadeiros para a execução. |
| **Speed** | Velocidade. | A rapidez do dash. |
| **Duration** | Duração. | Quanto tempo em segundos o impulso dura. |
| **Direction** | Direção Base. | **Right/Up** (Global) ou **Local Right/Up**. |
| **Angle** | Ângulo. | Rotação extra à direção base. |

## Como configurar

1. **Ao**: contrário de uma simples mudança de velocidade, o Dash move o objeto independentemente do seu sistema de movimento habitual.

2. **Configure**: uma velocidade alta (ex: 500) e uma duração curta (ex: 0.1s).

3. **Use**: um trigger como um botão do comando para ativar o dash.

