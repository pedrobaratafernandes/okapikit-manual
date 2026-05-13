# Manual do OkapiKit

Este repositório contém a documentação técnica do **OkapiKit**, focado em componentes para o **Unity 6**, desenvolvido para facilitar a criação de videojogos 2D sem a necessidade de programação complexa.

O manual é construído utilizando [MkDocs](https://www.mkdocs.org/) com o tema [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/).

---

## Aceder ao Manual Online

O manual está disponível publicamente em:
[https://pedrobaratafernandes.github.io/okapikit-manual/](https://pedrobaratafernandes.github.io/okapikit-manual/)

---

## Conteúdos do Repositório

*   **`docs/`**: Contém todos os ficheiros Markdown (`.md`) que compõem o manual.
*   **`mkdocs.yml`**: Ficheiro de configuração principal (navegação, tema, plugins).
*   **`.github/workflows/`**: Automação para publicação automática no GitHub Pages.

---

## Desenvolvimento Local

Se desejar editar ou pré-visualizar o manual no seu computador:


### Requisitos
1. Ter o [Python](https://www.python.org/) instalado.
2. (Opcional, mas recomendado) Criar um ambiente virtual:
    ```bash
    python -m venv venv
    # Ativar no Windows:
    venv\Scripts\activate
    # Ativar no macOS/Linux:
    source venv/bin/activate
    ```
3. Instalar as dependências do projeto usando o requirements.txt:
    ```bash
    pip install -r requirements.txt
    ```

### Comandos Úteis
*   **Ver em tempo real**: `mkdocs serve` (abre um servidor local em `http://127.0.0.1:8000`)
*   **Construir o site**: `mkdocs build`
*   **Publicar manualmente**: `mkdocs gh-deploy`

---

## Como Contribuir

Para sugerir melhorias ou corrigir erros no manual:

1.  Faça um **Fork** deste repositório.
2.  Crie um novo **Branch** para as suas alterações (`git checkout -b melhoria-manual`).
3.  Edite os ficheiros pretendidos na pasta `docs/`.
4.  Faça **Commit** e **Push** das suas alterações para o seu Fork.
5.  Submeta um **Pull Request** para este repositório para que as alterações possam ser revistas e integradas.

---

## Créditos

Documentação desenvolvida para o [OkapiKit](https://github.com/VideojogosLusofona/OkapiKit) da Universidade Lusófona.

Autor do OkapiKit: **Diogo Andrade**
