## Entidades
- Game
- Ad (Anúncio)
### Game
- id
- title
- bannerUrl

### Ad (Anúncio)
- id
- gameId (relação com game... 1 game - N anuncios)
- name (nickname no jogo)
- yearsPlaying (a quanto tempo a pessoa joga o game do anuncio)
- discord
- weekDays (dias da semana que a pessoa joga)
- hoursStart (hora que inicia a jogar)
- hourEnd (hora que para de jogar)
- useVoiceChannel (bool - costuma usar algum chat de voz?)
- createdAt


## Banco de dados
- SQLite

## Use Cases
- Listar os games e contagem de anuncios (pagina principal)
- Criar novos anuncios
- listar anuncios por game
- buscar discord pelo ID do anuncio
- OBS: Nao haverá rota para criar os games... Serão "pré setados" diretamente no Banco de Dados
