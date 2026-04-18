# Variable

[:material-code-tags: Ver Código Fonte C#](https://github.com/VideojogosLusofona/OkapiKit/blob/main/Assets/OkapiKit/Scripts/Variables/Variable.cs){ .md-button }



Asset que armazena dados persistentes acessíveis por qualquer objeto em qualquer cena.

## Porquê usar uma Variável Global?

1. **Persistência**: O valor mantém-se ao mudar de cena (ex: Pontuação).
2. **Partilha**: Vários objetos podem ler e alterar a mesma variável.
3. **Organização**: Concentra dados importantes do jogo numa única pasta do projeto.

## Configurações do Inspector

| Campo | Função | Detalhes |
| :--- | :--- | :--- |
| **Active** | Ativação | Define se o componente está ligado e pronto para funcionar. |
| **Tags** | Etiquetas | Etiquetas inteligentes (Hypertags) usadas para identificação e filtros. |
| **Conditions** | Condições | Lista de requisitos (ex: variáveis ou tokens) que têm de ser verdadeiros para a execução. |
| **Type** | Tipo. | **Integer** (inteiros) ou **Float** (decimais). |
| **Default Value** | Inicial. | Valor de reset sempre que o jogo recomeça do zero. |
| **Has Limits** | Limites. | Define valores mínimos e máximos permitidos. |

## Como criar

1. Clica com o botão direito na pasta Project.
2. Seleciona `Create` -> `Okapi Kit` -> `Variable`.
3. Dá um nome ao ficheiro (ex: `PlayerScore`).

## Como configurar

Em ações de alteração de valor ou triggers de condição, arraste o ficheiro da sua variável para o campo correspondente.
