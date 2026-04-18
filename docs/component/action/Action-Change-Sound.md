# Action-Change-Sound

[:material-code-tags: Ver Código Fonte C#](https://github.com/VideojogosLusofona/OkapiKit/blob/main/Assets/OkapiKit/Scripts/Actions/ActionChangeSound.cs){ .md-button }



Muda o áudio (clip) que está a tocar numa fonte sonora.

![Action Change Sound](../../assets/images/action/Action-Change-Sound.png)

## Configurações do Inspector

| Campo | Função | Detalhes |
| :--- | :--- | :--- |
| **Active** | Ativação | Define se o componente está ligado e pronto para funcionar. |
| **Tags** | Etiquetas | Etiquetas inteligentes (Hypertags) usadas para identificação e filtros. |
| **Conditions** | Condições | Lista de requisitos (ex: variáveis ou tokens) que têm de ser verdadeiros para a execução. |
| **Audio Source** | Fonte de Áudio | O componente `AudioSource` que está a tocar o som. |
| **Clip** | Novo Som | O ficheiro de som (`AudioClip`) a ser carregado. |
| **Volume** | Volume | Define a intensidade do som (0 a 1). |
| **Pitch** | Tom/Velocidade | Define a tonalidade e velocidade de reprodução. |

## Como configurar

1. **Útil**: para mudar a música de fundo quando o jogador entra numa zona de perigo.

2. **Arraste**: o `Audio Source` e o `Audio Clip` desejados para os campos respetivos.

