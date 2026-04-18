# Trigger-On-Input

[:material-code-tags: Ver Código Fonte C#](https://github.com/VideojogosLusofona/OkapiKit/blob/main/Assets/OkapiKit/Scripts/Triggers/TriggerOnInput.cs){ .md-button }



Permite ligar comandos do jogador (teclado, rato, joystick) a ações.

![Trigger On Input](../../assets/images/trigger/Trigger-On-Input.png)

## Configurações do Inspector

| Campo | Função | Detalhes |
| :--- | :--- | :--- |
| **Active** | Ativação | Define se o componente está ligado e pronto para funcionar. |
| **Tags** | Etiquetas | Etiquetas inteligentes (Hypertags) usadas para identificação e filtros. |
| **Conditions** | Condições | Lista de requisitos (ex: variáveis ou tokens) que têm de ser verdadeiros para a execução. |
| **Input Type** | Fonte. | **Button** (Unity Input), **Key** (Tecla direta), **Axis**, **Any Key**. |
| **Key** | Tecla. | Escolha a tecla específica (apenas no modo Key). |
| **Continuous** | Pressão. | **Sim**: Dispara enquanto mantém premido. **Não**: Dispara uma vez ao carregar. |
| **Use Cooldown** | Cadência. | Limita a velocidade com que o trigger pode disparar novamente (ex: tempo entre tiros). |
| **Else Actions** | Negativo. | Ações para quando a tecla **NÃO** está a ser premida. |

## Como configurar

1. **Escolha**: **Key** e selecione a tecla (ex: `Space` para saltar).

2. **Se**: quiser que o jogador dispare apenas uma vez por clique, desligue o **Continuous**.

3. **Use**: o **Cooldown** (ex: 0.5s) para limitar a velocidade de ataque.

4. **Adicione**: as ações que devem acontecer (ex: `Action Play Sound` ou `Action Spawn`) na lista **Actions**.

