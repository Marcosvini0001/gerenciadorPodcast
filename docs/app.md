# Podcast Menager

### DESCRIÇÃO

Um app ao estilo netflix, aonde possa centrlizar diferentes podcasts separados por categoria

### DOMINIO

Podcasts feitos em video

### FEATURES

- Listar os episódios em sessões de categorias
- [saúde, fitness, mentalidade, humor]
- Filtrar episódios por nome de podcasts

## Como

### FEATURE:

Listar os episódios podcasts em sessões de categorias

### Como vou implementar:

Vou retornar em uma api rest (json) o nome do podcast, nome do episódio, imagem de capa, link, category

```js
[
{
  podcastName: "flow",
  episode: "CBUM - Flow 319",
  cover: "https://i.ytimg.com/vi/pQSuQmUfS30/hq720.jpg?sqp=-oaymwEnCNAFEJQDSFryq4qpAxkIARUAAIhCGAHYAQHiAQoIGBACGAY4AUAB&rs=AOn4CLCeNGQeHGq3EN9VBoh7CCsKQU0L4Q",
  link: "https://www.youtube.com/watch?v=pQSuQmUfS30",
  category: ["saúde, ""bodybulder"]
},

{
    podcastName: "flow",
  episode: "CBUM - Flow 319",
  cover: "https://i.ytimg.com/vi/pQSuQmUfS30/hq720.jpg?sqp=-oaymwEnCNAFEJQDSFryq4qpAxkIARUAAIhCGAHYAQHiAQoIGBACGAY4AUAB&rs=AOn4CLCeNGQeHGq3EN9VBoh7CCsKQU0L4Q",
  link: "https://www.youtube.com/watch?v=pQSuQmUfS30",
  category: ["saúde, ""bodybulder"]
}
]
```
