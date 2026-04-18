# Speaker

[:material-code-tags: Ver Código Fonte C#](https://github.com/VideojogosLusofona/OkapiKit/blob/main/Assets/OkapiKit/Scripts/Systems/Dialogue/Speaker.cs){ .md-button }



Asset que define a identidade visual e sonora de um personagem no sistema de diálogos.

## Configurações do Inspector

| Campo | Função | Detalhes |
| :--- | :--- | :--- |
| **Active** | Ativação | Define se o componente está ligado e pronto para funcionar. |
| **Tags** | Etiquetas | Etiquetas inteligentes (Hypertags) usadas para identificação e filtros. |
| **Conditions** | Condições | Lista de requisitos (ex: variáveis ou tokens) que têm de ser verdadeiros para a execução. |
| **Name** | Nome. | O nome que aparecerá na caixa de texto. |
| **Name/Text Color**| Cores. | Permite diferenciar personagens via cores de nomes e letras. |
| **Portrait** | Retrato. | Sprite que aparece ao lado do texto. |
| **Voice Sound** | Voz. | Som curto que toca a cada letra escrita. |

## Como Criar

1. No Project View, clica com o botão direito.
2. Vai a `Create` -> `Okapi Kit` -> `Speaker`.
3. Preenche os dados visuais e de áudio.
4. Associa este orador nas tuas Key-frames de **Dialogue Data**.
