# Hypertag

[:material-code-tags: Ver Código Fonte C#](https://github.com/VideojogosLusofona/OkapiKit/blob/main/Assets/OkapiKit/Scripts/Hypertag/Hypertag.cs){ .md-button }



As Hypertags são assets que funcionam como etiquetas inteligentes, permitindo identificar e agrupar objetos de forma dinâmica.

![Hypertag](../../assets/images/hypertag/hypertag.png)

## O que é uma Hypertag?

Ao contrário das Tags do Unity (onde cada objeto só pode ter uma), as Hypertags são ficheiros:
- Podes ter **múltiplas Hypertags** no mesmo objeto.
- Podes criar quantas quiseres diretamente no teu projeto.
- Facilitam a criação de ações que afetam grupos de objetos (ex: "Destruir todos os inimigos com a tag 'Floresta'").

## Como criar e usar

1. **Criar Asset**: No Project, `Create` -> `Okapi Kit` -> `Hypertag`. Dê um nome (ex: `Player`, `Inimigo`).
2. **Atribuir**: Adicione o componente `Hypertag` ao objeto e arraste o asset para a lista.
3. **Filtrar**: Nos Triggers ou Moivements, use o campo de Tag para procurar objetos com esse asset.

## Boas Práticas

- Use nomes claros e começados por maiúsculas.
- Crie uma pasta `Hypertags` para manter todas as etiquetas organizadas.
