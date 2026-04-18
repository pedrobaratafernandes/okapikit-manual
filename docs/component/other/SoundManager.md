# Sound Manager

[:material-code-tags: Ver Código Fonte C#](https://github.com/VideojogosLusofona/OkapiKit/blob/main/Assets/OkapiKit/Scripts/Systems/SoundManager.cs){ .md-button }



Gere a reprodução de áudio, múltiplas fontes e volumes globais.

![Sound Manager](../../assets/images/other/SoundManager.png)

## Configurações do Inspector

| Campo | Função | Detalhes |
| :--- | :--- | :--- |
| **Active** | Ativação | Define se o componente está ligado e pronto para funcionar. |
| **Tags** | Etiquetas | Etiquetas inteligentes (Hypertags) usadas para identificação e filtros. |
| **Conditions** | Condições | Lista de requisitos (ex: variáveis ou tokens) que têm de ser verdadeiros para a execução. |
| **Mixer Output** | Saída Áudio. | O canal do Unity Audio Mixer (ex: "SFX" ou "Music"). |

## Como configurar

1. **Deve**: haver apenas um `SoundManager` na cena (habitualmente usa-se juntamente com o componente `Singleton`).

2. **Quando**: usa a ação `Action Play Sound`, é este componente que trata de encontrar uma coluna livre para tocar o som.

3. **Se**: não definir um **Mixer Output**, o Unity usará a saída padrão.

