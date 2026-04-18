# Action-Play-Sound

[:material-code-tags: Ver Código Fonte C#](https://github.com/VideojogosLusofona/OkapiKit/blob/main/Assets/OkapiKit/Scripts/Actions/ActionPlaySound.cs){ .md-button }



Toca um efeito sonoro (SFX).

![Action Play Sound](../../assets/images/action/Action-Play-Sound.png)

## Configurações do Inspector

| Campo | Função | Detalhes |
| :--- | :--- | :--- |
| **Active** | Ativação | Define se o componente está ligado e pronto para funcionar. |
| **Tags** | Etiquetas | Etiquetas inteligentes (Hypertags) usadas para identificação e filtros. |
| **Conditions** | Condições | Lista de requisitos (ex: variáveis ou tokens) que têm de ser verdadeiros para a execução. |
| **Clip** | Áudio. | O ficheiro de som (AudioClip). |
| **Volume / Pitch** | Ajustes. | Suporta intervalos aleatórios para variar o som. |

## Como configurar

1. **Requer**: um `Sound Manager` na cena.

2. **Arraste**: o ficheiro de som (WAV, MP3, OGG) para o campo **Clip**.

3. **Use**: em quase todos os eventos do jogo para melhorar a experiência do utilizador via triggers.

