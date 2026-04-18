# Movement-Rotate

[:material-code-tags: Ver Código Fonte C#](https://github.com/VideojogosLusofona/OkapiKit/blob/main/Assets/OkapiKit/Scripts/Movement/MovementRotate.cs){ .md-button }



Controla a rotação de um objeto, seja de forma automática, por input ou mirando um alvo.

![Movement Rotate](../../assets/images/movement/Movement-Rotate.png)

## Configurações do Inspector

| Campo | Função | Detalhes |
| :--- | :--- | :--- |
| **Active** | Ativação | Define se o componente está ligado e pronto para funcionar. |
| **Tags** | Etiquetas | Etiquetas inteligentes (Hypertags) usadas para identificação e filtros. |
| **Conditions** | Condições | Lista de requisitos (ex: variáveis ou tokens) que têm de ser verdadeiros para a execução. |
| **Speed** | Velocidade. | Rapidez de rotação em graus por segundo. |
| **Mode** | Modo. | **Auto**, **Input Set** (aponta direção), **Input Delta** (esquerda/direita), **Target** (olha alvo), **Movement** (alinha com direção). |
| **Axis to Align** | Eixo. | Qual o eixo do objeto aponta para o destino (**Up** ou **Right**). |
| **Input Type** | Controle. | Como o jogador controla a rotação. |

## Como configurar

1. **Escolha**: o **Mode** adequado. Para um moinho, use `Auto`. Para um personagem que olha para o rato, use `Input Set` com `Mouse`.

2. **Ajuste**: a **Speed** para controlar a suavidade do movimento de rotação.

3. **Se**: o objeto parecer estar a olhar de lado, mude o **Axis to Align**.

