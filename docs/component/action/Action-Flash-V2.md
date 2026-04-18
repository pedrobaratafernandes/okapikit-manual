# Action-Flash-V2

[:material-code-tags: Ver Código Fonte C#](https://github.com/VideojogosLusofona/OkapiKit/blob/main/Assets/OkapiKit/Scripts/Actions/ActionFlashV2.cs){ .md-button }



Cria um efeito de flash cromático num renderizador.

![Action Flash](../../assets/images/action/Action-Flash-V2.png)

## Configurações do Inspector

| Campo | Função | Detalhes |
| :--- | :--- | :--- |
| **Active** | Ativação | Define se o componente está ligado e pronto para funcionar. |
| **Tags** | Etiquetas | Etiquetas inteligentes (Hypertags) usadas para identificação e filtros. |
| **Conditions** | Condições | Lista de requisitos (ex: variáveis ou tokens) que têm de ser verdadeiros para a execução. |
| **Target** | Alvo. | O componente visual a iluminar (via Hypertag ou Objeto). |
| **Mode** | Tipo. | **Color Flash**, **Invert Color** ou **Smooth Invert**. |
| **Color** | Cor. | A cor usada no flash (suporta gradientes). |
| **Duration** | Duração. | Tempo total do efeito em segundos. |

## Como configurar

1. **Requer**: que o objeto tenha um renderizador (Sprite Renderer).

2. **Configure**: uma duração curta para um efeito de impacto (ex: 0.1s).

3. **Combine**: isto com a `Action Play Sound` para um feedback de dano completo.

