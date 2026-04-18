# Variable Instance

[:material-code-tags: Ver Código Fonte C#](https://github.com/VideojogosLusofona/OkapiKit/blob/main/Assets/OkapiKit/Scripts/Systems/VariableInstance.cs){ .md-button }



Armazena dados locais num objeto (ex: força, velocidade, estado).

![Variable Instance](../../assets/images/other/VariableInstance.png)

## Configurações do Inspector

| Campo | Função | Detalhes |
| :--- | :--- | :--- |
| **Active** | Ativação | Define se o componente está ligado e pronto para funcionar. |
| **Tags** | Etiquetas | Etiquetas inteligentes (Hypertags) usadas para identificação e filtros. |
| **Conditions** | Condições | Lista de requisitos (ex: variáveis ou tokens) que têm de ser verdadeiros para a execução. |
| **Type** | Tipo dado. | **Integer** (inteiros) ou **Float** (decimais). |
| **Default Value** | Inicial. | Valor quando o objeto entra na cena. |
| **Has Limits** | Limites. | Define valores mínimos e máximos (ex: Vida entre 0 e 100). |

## Como configurar

1. **Use**: este componente para dar "propriedades" aos seus objetos (ex: vida ao inimigo, munição à arma).

2. **Outros**: componentes (como `Trigger On Condition` ou `Action Change Value`) podem ler e alterar estes valores.

3. **Se**: quiser que o valor seja persistente (guardado), use variáveis globais em vez de instâncias locais.

