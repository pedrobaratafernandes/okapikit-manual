# Okapi Configuration

[:material-code-tags: Ver Código Fonte C#](https://github.com/VideojogosLusofona/OkapiKit/blob/main/Assets/OkapiKit/Scripts/Variables/OkapiConfig.cs){ .md-button }



Asset central que controla o comportamento do framework no editor e no jogo.

## Configurações Principais

### Scene View (Visualização)
- **Display Conditions**: Mostra as condições de ativação em cima dos objetos no Scene View.
- **Display Hypertags**: Exibe as tags dos objetos diretamente no cenário.

### Sorting (Ordenação)
- **Order Mode**: Escolha entre **Z** (padrão Unity) ou **Y** (top-down).
- **Order Scale Y**: Sensibilidade da ordenação baseada no eixo vertical.

## Como editar

1. Se o teu projeto não tiver um, cria um em `Create` -> `Okapi Kit` -> `Configuration`.
2. Geralmente, este ficheiro é colocado numa pasta chamada `Settings` ou `Core`.
3. Altera as opções e elas serão aplicadas instantaneamente a todos os componentes do OkapiKit no teu projeto.
