# Multi-Value-Display-Text

[:material-code-tags: Ver Código Fonte C#](https://github.com/VideojogosLusofona/OkapiKit/blob/main/Assets/OkapiKit/Scripts/UI/MultiValueDisplayText.cs){ .md-button }



Permite exibir múltiplas variáveis formatadas (locais ou globais) num único campo de texto (ex: "HP: 10/100" ou "Ouro: 500").

![Multi Value Display Text](../../assets/images/okapikit/MultiValueDisplayText.png)

## Configurações do Inspector

| Campo | Função | Detalhes |
| :--- | :--- | :--- |
| **Active** | Ativação | Define se o componente está ligado e pronto para funcionar. |
| **Tags** | Etiquetas | Etiquetas inteligentes (Hypertags) usadas para identificação e filtros. |
| **Conditions** | Condições | Lista de requisitos (ex: variáveis ou tokens) que têm de ser verdadeiros para a execução. |
| **Values** | Valores | Lista de variáveis que serão injetadas no texto. |
| **Text-Component**| Formato | O campo onde deve escrever o texto base usando marcadores como `{0}`, `{1}`, etc. |
| **Description** | Notas | Campo opcional para descrições internas do desenvolvedor. |

## Como configurar

1. **Requisito**: Adicione este componente a um objeto que já possua um componente **TextMeshPro - Text (UI)**.

2. **Formatação**: No campo de texto do TextMeshPro, escreva a frase que deseja, usando parênteses curvos para os valores (ex: `Munição: {0} / {1}`).

3. **Mapeamento**: Adicione na lista **Values** as variáveis correspondentes (ex: `ammoCurrent` e `ammoMax`). O OkapiKit atualizará o texto em tempo real conforme as variáveis mudam.

