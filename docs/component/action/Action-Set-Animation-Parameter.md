# Action-Set-Animation-Parameter

[:material-code-tags: Ver Código Fonte C#](https://github.com/VideojogosLusofona/OkapiKit/blob/main/Assets/OkapiKit/Scripts/Actions/ActionSetAnimationParameter.cs){ .md-button }



Comunica estados de lógica ao Animator do Unity.

![Action Set Animation Parameter](../../assets/images/action/Action-Set-Animation-Parameter.png)

## Configurações do Inspector

| Campo | Função | Detalhes |
| :--- | :--- | :--- |
| **Active** | Ativação | Define se o componente está ligado e pronto para funcionar. |
| **Tags** | Etiquetas | Etiquetas inteligentes (Hypertags) usadas para identificação e filtros. |
| **Conditions** | Condições | Lista de requisitos (ex: variáveis ou tokens) que têm de ser verdadeiros para a execução. |
| **Animator** | Animador. | O componente `Animator` alvo. |
| **Parameter** | Parâmetro. | O nome exato do parâmetro (ex: "IsDead", "Speed"). |
| **Value Type** | Tipo. | **Int**, **Float**, **Bool**, **Trigger** (instantâneo), **Velocity X/Y** (usa a velocidade real). |

## Como configurar

1. **Escolha**: o tipo de valor que corresponde ao que definiu no painel "Parameters" do seu Animator no Unity.

2. **Se**: usar **Velocity X/Y**, o OkapiKit calcula automaticamente a velocidade e envia-a para o animador (ideal para criar animações de corrida que dependem da velocidade real).

3. **Use**: o modo **Trigger** para animações de "um disparo", como um ataque ou um salto.

