# Spawner

[:material-code-tags: Ver Código Fonte C#](https://github.com/VideojogosLusofona/OkapiKit/blob/main/Assets/OkapiKit/Scripts/Systems/Spawner.cs){ .md-button }



Gere a criação (spawn) de múltiplos objetos com base em padrões ou áreas.

![Spawner](../../assets/images/other/Spawner.png)

## Configurações do Inspector

| Campo | Função | Detalhes |
| :--- | :--- | :--- |
| **Active** | Ativação | Define se o componente está ligado e pronto para funcionar. |
| **Tags** | Etiquetas | Etiquetas inteligentes (Hypertags) usadas para identificação e filtros. |
| **Conditions** | Condições | Lista de requisitos (ex: variáveis ou tokens) que têm de ser verdadeiros para a execução. |
| **Prefabs** | Moldes. | Lista de objetos que podem ser criados aleatoriamente. |
| **Spawn Points** | Locais. | Lista de pontos (objeto ou tag) onde os objetos aparecem. |
| **Point Type** | Direção. | **Random** (ponto aleatório), **Sequence** (ordem da lista), **All** (em todos os pontos ao mesmo tempo). |
| **Pulse Pattern** | Ritmo. | Padrão de texto para vagas (ex: "xoxo" onde x=spawn e o=pausa). |
| **Force Count** | Quantidade. | Mantém sempre X objetos ativos na cena (respawn automático). |

## Como configurar

1. **Se**: adicionar um `Box Collider 2D` ao mesmo objeto que o Spawner, ele usará a área do colisor como zona de nascimento aleatória.

2. **Se**: houver um componente `Path` no objeto, pode configurar o Spawner para criar objetos ao longo desse caminho.

3. **Ótimo**: para sistemas de "Respawn" ou para criar sistemas de partículas personalizados.

