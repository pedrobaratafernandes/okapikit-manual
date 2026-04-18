# Action-Change-Transform

[:material-code-tags: Ver Código Fonte C#](https://github.com/VideojogosLusofona/OkapiKit/blob/main/Assets/OkapiKit/Scripts/Actions/ActionChangeTransform.cs){ .md-button }



Manipula a posição ou escala de um objeto diretamente (sem física).

![Action Change Transform](../../assets/images/action/Action-Change-Transform.png)

## Configurações do Inspector

| Campo | Função | Detalhes |
| :--- | :--- | :--- |
| **Active** | Ativação | Define se o componente está ligado e pronto para funcionar. |
| **Tags** | Etiquetas | Etiquetas inteligentes (Hypertags) usadas para identificação e filtros. |
| **Conditions** | Condições | Lista de requisitos (ex: variáveis ou tokens) que têm de ser verdadeiros para a execução. |
| **Change Type** | Tipo. | **Position** (Posição) ou **Scale** (Tamanho). |
| **X/Y Axis** | Eixos. | Operação para cada eixo (Set, Add, etc). |
| **Position / Delta**| Valores. | Valores para definir ou somar (suporta aleatórios). |
| **ScaleWithTime** | Velocidade? | Se ativo, a alteração é feita por segundo. |

## Como configurar

1. **Use**: para criar objetos que crescem com o tempo ou para empurrar objetos em direções específicas sem usar física.

2. **Ao**: contrário das ações de movimento, isto mexe diretamente nas coordenadas do objeto.

3. **Arraste**: o `Transform` alvo para o campo **Target**.

