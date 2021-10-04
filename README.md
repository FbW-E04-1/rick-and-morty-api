# Rick and Morty search engine

Complete the Rick and Morty search engine by using the Rick and Morty api: https://rickandmortyapi.com/

## Endpoints
- get all characters: https://rickandmortyapi.com/api/character
- filter through characters: same url, but with extra parameters:
  - name: filter by the given name.
  - status: filter by the given status (alive, dead or unknown).
  - species: filter by the given species.
  - type: filter by the given type.
  - gender: filter by the given gender (female, male, genderless or unknown).

Example:

Get the list of characters with name Rick, status alive and gender male:

https://rickandmortyapi.com/api/character/?name=rick&status=alive&gender=male

To add filters to the url you have to add a string that starts with a question mark `?` followed by key/value pairs. Each pair is separated by `&`, like in the example above
