Projeto criado para o desafio do módulo 5 da rocketseat, Aplicativo GoRestaurant Mobile
Para este projeto foi utilizado um JSON server para rodar na porta :3333.

O objetivo desta aplicação é realizar a parte de listagem de produtos e a funcionalidade de
compra consumindo e postando dandos na fake api, tanto quanto utilização de favoritos.
As especificações podem ser encontradas **[aqui](https://github.com/rocketseat-education/bootcamp-gostack-desafios/blob/master/desafio-react-native-delivery/README.md)**

E o layout seguindo as [seguintes regras](https://www.figma.com/file/cHzfYrUBgdzp1XrRuUpggk/GoRestaurant-Mobile?node-id=1603%3A448)

## Scripts disponíveis

Para rodar o projeto basta executar

### `yarn`

Para instalar as dependências da aplicação

### `yarn json-server server.json -p 3333`

Para startar o JSON server (FAKE API)

### `adb -s <device name> reverse tcp:3333 tcp:3333`

Presumindo que a sdk do android já esteja instalada na sua máquina, e que seu dispositivo esteja conectado,
habilitado modo desenvolvedor e depuração usb, e ao rodar adb devices, o dispositivo esteja como "device"

Este comando irá dizer que a porta 3333 encontrada no seu dispositivo android se equivale a porta 3333 do seu localhost

### `npx react-native react-android`

Roda a aplicação no seu emulador ou no seu dispositivo conectado (por padrão, porta 8081)

### `yarn test`

Para executar os testes necessários para a aplicação ser considerada criada com sucesso

## Fundamentos

Neste projeto foram colocados em prática os conhecimentos adquiridos no módulo 5 do Bootcamp,
foi bastante utilizado conceito de hooks, principalmente useCallback e useMemo, bastante semelhante
a forma como ocorre no React JS (pra não dizer idêntica)

- React-Native;
- ContextAPI;
- Typescript;
- Memoization;
