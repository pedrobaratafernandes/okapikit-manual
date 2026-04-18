# Action-Teleport

[:material-code-tags: Ver Código Fonte C#](https://github.com/VideojogosLusofona/OkapiKit/blob/main/Assets/OkapiKit/Scripts/Actions/ActionTeleport.cs){ .md-button }



Move instantaneamente um objeto de uma posição para outra.

![Action Teleport](../../assets/images/action/Action-Teleport.png)

## Configurações do Inspector

| Campo | Função | Detalhes |
| :--- | :--- | :--- |
| **Active** | Ativação | Define se o componente está ligado e pronto para funcionar. |
| **Tags** | Etiquetas | Etiquetas inteligentes (Hypertags) usadas para identificação e filtros. |
| **Conditions** | Condições | Lista de requisitos (ex: variáveis ou tokens) que têm de ser verdadeiros para a execução. |
| **Subject** | Quem Mover. | **Self**, **Target**, **Tag**, **Collider**. |
| **Teleport Target** | Destino. | **Target** ou **Tag**. |
| **Target Transforms** | Pontos Alvo. | Lista de pontos possíveis (escolhe um aleatório se houver vários). |

## Como configurar

1. **Útil**: para criar zonas de "Teletransporte" onde o jogador, ao colidir, é enviado para outra parte do mapa.

2. **Funciona**: perfeitamente com o `Grid System`; se o objeto estiver numa grelha, ele será teletransportado corretamente para as coordenadas da grelha.

3. **Se**: definir vários **Target Transforms**, o jogo escolherá um deles aleatoriamente cada vez que a ação for executada.

