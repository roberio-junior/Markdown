# Guia de Formatação em Markdown

Este repositório tem como objetivo ensinar a criar e formatar um README para o GitHub utilizando a linguagem Markdown. Um README bem estruturado ajuda a documentar seu projeto, tornando-o mais acessível e compreensível para outros desenvolvedores.

## Títulos

Para criar títulos, utilize `#` no início do texto, conforme o nível desejado:

```markdown
# Título de Nível 1
## Título de Nível 2
### Título de Nível 3
```

## Estilos de Texto

- **Negrito**: Utilize `**texto**` ou `__texto__` → **Exemplo**
- *Itálico*: Utilize `*texto*` ou `_texto_` → *Exemplo*
- ~~Texto Tachado~~: Utilize `~~texto~~` → ~~Exemplo~~
- **_Combinação de Negrito e Itálico_**: Utilize `***texto***` → ***Exemplo***

## Linhas Horizontais

Para adicionar uma linha horizontal, utilize `---` ou `***`:

```markdown
---
```

---

## Listas

### Lista Numerada

Para criar uma lista numerada, utilize números seguidos de um ponto:

```markdown
1. Item 1
2. Item 2
3. Item 3
```

Resultado:

1. Item 1
2. Item 2
3. Item 3

### Lista Demarcada

Utilize `*` ou `-` antes do texto:

```markdown
* Item 1
- Item 2
```

Resultado:

* Item 1
- Item 2

### Lista de Tarefas

Para criar uma lista de tarefas, utilize `- [ ]` antes do texto. Para marcar uma tarefa como concluída, adicione `x` entre os colchetes:

```markdown
- [x] Tarefa concluída
- [ ] Tarefa pendente
```

Resultado:

- [x] Tarefa concluída
- [ ] Tarefa pendente

### Subitens em Listas

Subitens podem ser utilizados em qualquer tipo de lista (numerada, demarcada e de tarefas). Para criar um subitem, utilize três espaços antes do símbolo correspondente:

```markdown
1. Item principal
   1. Subitem 1
   2. Subitem 2

* Item principal
   * Subitem 1
   * Subitem 2

- [ ] Tarefa principal
   - [ ] Subtarefa 1
   - [x] Subtarefa 2 concluída
```

Resultado:

1. Item principal
   1. Subitem 1
   2. Subitem 2

* Item principal
   * Subitem 1
   * Subitem 2

- [ ] Tarefa principal
   - [ ] Subtarefa 1
   - [x] Subtarefa 2 concluída

## Citações

Para adicionar uma citação, utilize `>` antes do texto:

```markdown
> "O único modo de fazer um excelente trabalho é amar o que você faz." – Steve Jobs
```

Resultado:

> "O único modo de fazer um excelente trabalho é amar o que você faz." – Steve Jobs

## Adicionando Código

Para adicionar trechos de código inline, utilize crases (`). Exemplo:

```markdown
Aqui está um comando `git status`.
```

Para adicionar blocos de código, use três crases no início e no fim do trecho:

<pre>
   ```python
   print("Hello, World!")
   ```
</pre>

Resultado:

```python
print("Hello, World!")
```

## Adicionando Imagens

Para adicionar uma imagem, arraste-a para a barra de mídia do GitHub ou utilize o seguinte formato:

```markdown
![Descrição da imagem](https://link-da-imagem.com)
```

Exemplo:

![Imagem de Exemplo](https://github.com/user-attachments/assets/69cc4186-172c-4ef1-8162-0c581b4c3d00)

## Criando Links Clicáveis

Para criar um link clicável, utilize colchetes para o texto do link e parênteses para a URL:

```markdown
[Acesse meu GitHub](https://github.com/roberio-junior)
```

Resultado:

[Acesse meu GitHub](https://github.com/roberio-junior)

## Tabelas

Para criar tabelas, utilize `|` para separar colunas e `-` para criar o cabeçalho:

```markdown
| Nome   | Idade | Cidade       |
|--------|------|-------------|
| Ana    | 25   | São Paulo   |
| Bruno  | 30   | Rio de Janeiro |
```

Resultado:

| Nome   | Idade | Cidade       |
|--------|------|-------------|
| Ana    | 25   | São Paulo   |
| Bruno  | 30   | Rio de Janeiro |

---
