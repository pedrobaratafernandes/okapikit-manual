# Action-Change-Particle-System 

[:material-code-tags: Ver Código Fonte C#](https://github.com/VideojogosLusofona/OkapiKit/blob/main/Assets/OkapiKit/Scripts/Actions/ActionChangeParticleSystem.cs){ .md-button }



Controla a emissão de partículas de um sistema.

![Action Change Particle System](../../assets/images/action/Action-Change-Particle-System.png)

## Configurações do Inspector

| Campo | Função | Detalhes |
| :--- | :--- | :--- |
| **Active** | Ativação | Define se o componente está ligado e pronto para funcionar. |
| **Tags** | Etiquetas | Etiquetas inteligentes (Hypertags) usadas para identificação e filtros. |
| **Conditions** | Condições | Lista de requisitos (ex: variáveis ou tokens) que têm de ser verdadeiros para a execução. |
| **Particle System** | Sistema. | O componente `ParticleSystem` alvo. |
| **Change Type** | Tipo. | Atualmente focado em **Emission** (Emissão). |
| **Emission** | Estado. | **Enable**, **Disable** ou **Toggle**. |

## Como configurar

1. **Útil**: para ativar um rasto de fumo quando um motor liga, ou parar faíscas quando um circuito é reparado.

2. **Arraste**: o sistema de partículas para o campo **Particle System**.

