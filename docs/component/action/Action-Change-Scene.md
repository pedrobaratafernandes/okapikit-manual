# Action-Change-Scene

[:material-code-tags: Ver Código Fonte C#](https://github.com/VideojogosLusofona/OkapiKit/blob/main/Assets/OkapiKit/Scripts/Actions/ActionChangeScene.cs){ .md-button }



Carrega um novo nível ou cena.

![Action Change Scene](../../assets/images/action/Action-Change-Scene.png)

## Configurações do Inspector

| Campo | Função | Detalhes |
| :--- | :--- | :--- |
| **Active** | Ativação | Define se o componente está ligado e pronto para funcionar. |
| **Tags** | Etiquetas | Etiquetas inteligentes (Hypertags) usadas para identificação e filtros. |
| **Conditions** | Condições | Lista de requisitos (ex: variáveis ou tokens) que têm de ser verdadeiros para a execução. |
| **Scene Name** | Nome da Cena. | O nome exato da cena a carregar (deve estar nos Build Settings). |

## Como configurar

1. **Escreva**: o nome da cena exatamente como aparece na pasta do projeto (respeitando maiúsculas).

2. **Importante**: A cena deve estar adicionada nas "Build Settings" do Unity (File -> Build Settings).

3. **Use**: esta ação num `Trigger On Collision` colocado numa porta ou portal.

