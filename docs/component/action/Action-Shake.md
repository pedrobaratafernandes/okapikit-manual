# Action-Shake

[:material-code-tags: Ver Código Fonte C#](https://github.com/VideojogosLusofona/OkapiKit/blob/main/Assets/OkapiKit/Scripts/Actions/ActionShake.cs){ .md-button }



Cria um efeito de agitação (shake) num objeto ou na câmara.

![Action Shake](../../assets/images/action/Action-Shake.png)

## Configurações do Inspector

| Campo | Função | Detalhes |
| :--- | :--- | :--- |
| **Active** | Ativação | Define se o componente está ligado e pronto para funcionar. |
| **Tags** | Etiquetas | Etiquetas inteligentes (Hypertags) usadas para identificação e filtros. |
| **Conditions** | Condições | Lista de requisitos (ex: variáveis ou tokens) que têm de ser verdadeiros para a execução. |
| **Object** | Alvo. | O objeto a agitar (pode ser definido por tag, como "MainCamera"). |
| **Strength** | Força. | Intensidade da vibração. |
| **Duration** | Duração. | Tempo do efeito em segundos. |

## Como configurar

1. **Se**: quiser agitar a câmara, arraste a câmara para o **Target Object** ou use a Tag correspondente.

2. **O**: objeto precisa de ter (ou o OkapiKit adicionará automaticamente) um componente `Shaker`.

3. **Combine**: com sons de explosão para um impacto máximo.

