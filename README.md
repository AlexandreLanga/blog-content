# Blog Content

Repositorio de conteudo editorial de um blog pessoal. Os textos ficam em
`posts/` e o arquivo `manifest.json` funciona como indice para a aplicacao
consumidora.

## Estrutura

- `manifest.json`: lista os posts publicados e seus metadados.
- `posts/`: armazena o corpo dos artigos em Markdown.
- `slug`: identifica o post e corresponde ao nome do arquivo sem a extensao.
- `title` e `summary`: chaves de traducao, resolvidas pela aplicacao conforme o idioma selecionado.
- `date`: data de publicacao no formato ISO `YYYY-MM-DD`.

## Tags numericas

As tags dos posts sao IDs numericos, e nao textos localizados. Isso mantem o
conteudo independente do idioma e evita que a aplicacao precise comparar
rotulos traduzidos.

O objeto `tag_definitions` no manifesto define o significado de cada ID:

| ID  | pt-BR | en |
| --- | --- | --- |
| 1   |  Projeto | Project |
| 2   |  Aprendizado | Learning |
| 3   |  Evento | Event |
| 4   |  Inovacao | Innovation |
| 5   |  Python | Python |
| 6   |  Inteligencia Artificial | Artificial Intelligence |
| 7   |  PHP | PHP |

Cada post referencia essas definicoes em `tags`, por exemplo:

```json
{
	"slug": "novos_interesses_desbloqueados_python_e_ia",
	"tags": [5, 6, 1]
}
```

Para exibir uma tag, a aplicacao deve:

1. Ler o ID no array `posts[].tags`.
2. Usar esse ID como chave em `tag_definitions`.
3. Selecionar `pt-BR` ou `en` conforme o idioma atual.

Exemplo de resultado em `pt-BR`:

```text
Python, Inteligencia Artificial, Projeto
```

O mesmo post em `en` deve ser exibido como:

```text
Python, Artificial Intelligence, Project
```

Novas tags devem receber um novo ID sem reutilizar IDs antigos, preservando a
compatibilidade com aplicacoes que ja consomem o manifesto.