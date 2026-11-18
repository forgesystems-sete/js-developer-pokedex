# Trilha JS Developer - Pokedex

Lista de Pokémons (1ª geração) consumindo a [PokeAPI](https://pokeapi.co/), com paginação pelo botão "Load More".

## Estrutura

```
index.html
assets/
  css/
    global.css
    pokedex.css
  js/
    pokemon-model.js   # classe Pokemon
    poke-api.js        # chamadas à PokeAPI + conversão para o modelo
    main.js            # renderização da lista e paginação
```

## Como rodar

Basta abrir o `index.html` no navegador (é necessário internet para a PokeAPI e a fonte).
Opcionalmente, use a extensão Live Server do VS Code ou `npx serve`.
