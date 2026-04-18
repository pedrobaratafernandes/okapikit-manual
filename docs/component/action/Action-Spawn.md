# Action-Spawn

[:material-code-tags: Ver Código Fonte C#](https://github.com/VideojogosLusofona/OkapiKit/blob/main/Assets/OkapiKit/Scripts/Actions/ActionSpawn.cs){ .md-button }



Cria um novo objeto (Prefab) na cena. Ideal para projéteis ou efeitos.

![Action Spawn](../../assets/images/action/Action-Spawn.png)

## Configurações do Inspector

| Campo | Função | Detalhes |
| :--- | :--- | :--- |
| **Active** | Ativação | Define se o componente está ligado e pronto para funcionar. |
| **Tags** | Etiquetas | Etiquetas inteligentes (Hypertags) usadas para identificação e filtros. |
| **Conditions** | Condições | Lista de requisitos (ex: variáveis ou tokens) que têm de ser verdadeiros para a execução. |
| **Prefab Object** | Molde. | O Prefab do objeto a ser criado. |
| **Spawn Position** | Posição. | **This**: Aqui na ação.<br>**Target**: Num objeto específico.<br>**Tag**: Num objeto com certa tag. |
| **Set Parent** | Parentesco. | Se ativo, o objeto criado torna-se filho da posição onde nasceu. |

## Como configurar

1. **Se**: estiver a usar um sistema de `Spawner` (Invocador) no mesmo objeto, esta ação pode ser usada para o ativar.

2. **É**: a ação principal para criar projéteis num jogo de tiros.

3. **Certifique-se**: de que o **Prefab Object** é um Prefab real da sua pasta de projeto e não um objeto que já está na hierarquia da cena.

