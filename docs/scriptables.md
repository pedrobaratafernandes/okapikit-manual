# Scriptables

Os **Scriptables** são ficheiros de dados permanentes que vivem no teu projeto (não na cena) e guardam informações partilhadas.

---

### [Dialogue Data](component/scriptables/DialogueData.md)
Asset que armazena conversas, ramificações e escolhas.


| Campo | Função | Detalhes |
| :--- | :--- | :--- |
| **Speaker** | Falante. | Asset de **Speaker** (nome e som) que está a falar. |
| **Text** | Texto. | A frase que será exibida no ecrã. |
| **Options** | Opções. | Escolhas que o jogador pode tomar. |
| **Actions** | Ações. | Ações executadas no início ou fim daquela fala. |

### [Hypertag](component/scriptables/Hypertag.md)
As Hypertags são assets que funcionam como etiquetas inteligentes, permitindo identificar e agrupar objetos de forma dinâmica.

![Hypertag](assets/images/hypertag/hypertag.png)

### [Item](component/scriptables/Item.md)
Asset que define as propriedades de um objeto recolhível ou equipável.

| Campo | Função | Detalhes |
| :--- | :--- | :--- |
| **Name** | Nome de Jogo.| O nome que aparece na UI. |
| **Icon** | Ícone. | A imagem que representa o item no inventário. |
| **Stackable** | Acumulável. | Se o jogador pode carregar várias unidades no mesmo slot. |
| **Tags** | Categorias. | Hypertags que definem que tipo de item é. |

### [Okapi Config](component/scriptables/OkapiConfig.md)
Asset central que controla o comportamento.

### [Palette](component/scriptables/Palette.md)
Asset que define conjuntos de cores consistentes para o projeto.

*Permite organizar cores por matiz/brilho e exportar como textura.*

### [Quest](component/scriptables/Quest.md)
Asset que define os objetivos, requisitos e recompensas de uma missão.

| Campo | Função | Detalhes |
| :--- | :--- | :--- |
| **Name** | Título. | O nome que aparece no log de missões. |
| **Description** | Descrição. | Explicação dos objetivos para o jogador. |
| **Objectives** | Objetivos. | Lista de itens (Assets) ou Tokens (Hypertags) necessários. |
| **Required Quests**| Pré-requisitos. | Outras missões que devem estar completas antes desta. |

### [Speaker](component/scriptables/Speaker.md)
Asset que define a identidade visual e sonora de um personagem no sistema de diálogos.

| Campo | Função | Detalhes |
| :--- | :--- | :--- |
| **Name** | Nome. | O nome que aparecerá na caixa de texto. |
| **Portrait** | Retrato. | Sprite que aparece ao lado do texto. |
| **Voice Sound** | Voz. | Som curto que toca a cada letra escrita. |

### [Tile Set](component/scriptables/TileSet.md)
Asset que agrupa múltiplos Tiles do Unity sob um único nome para facilitar a deteção de terrenos.

| Campo | Função | Detalhes |
| :--- | :--- | :--- |
| **Tiles** | Lista. | Arraste todos os assets de Tile que fazem parte deste grupo. |

### [Variable](component/scriptables/Variable.md)
Asset que armazena dados persistentes acessíveis por qualquer objeto em qualquer cena.

| Campo | Função | Detalhes |
| :--- | :--- | :--- |
| **Type** | Tipo. | **Integer** (inteiros) ou **Float** (decimais). |
| **Default Value** | Inicial. | Valor de reset quando o jogo recomeça. |
| **Has Limits** | Limites. | Define valores mínimos e máximos permitidos. |
