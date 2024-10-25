## Projeto Screenmatch

O **Projeto Screenmatch** é uma aplicação desenvolvida em Java que permite a consulta e gerenciamento de informações sobre séries de TV. Através de uma interface de linha de comando, o usuário pode buscar por séries, explorar suas temporadas e episódios, e obter detalhes como avaliações e datas de lançamento.

### Principais Funcionalidades:

- **Busca de Séries**: O usuário pode pesquisar por uma série usando seu nome, obtendo informações gerais.
- **Exploração de Temporadas**: A aplicação recupera e exibe todas as temporadas da série selecionada.
- **Lista de Episódios**: O usuário pode visualizar todos os episódios de cada temporada, com títulos e avaliações.
- **Filtragem de Episódios**: Possibilidade de buscar um episódio específico através de um trecho do título.
- **Análise de Avaliações**: O sistema calcula a média de avaliações por temporada e fornece estatísticas como o melhor e o pior episódio.
- **Relatórios Detalhados**: Informações sobre lançamentos de episódios a partir de um ano específico podem ser consultadas, proporcionando uma visão clara do histórico da série.

### Estrutura do Projeto

- **Pacotes**:
  - `br.com.limeira.screenmatch.principal`: Contém a classe `Principal`, que gerencia a interação com o usuário e a lógica central da aplicação.
  - `br.com.limeira.screenmatch.model`: Define as classes de modelo, como `DadosEpisodio`, `DadosSerie`, `Episodio`, e `DadosTemporada`.
  - `br.com.limeira.screenmatch.service`: Contém serviços como `ConsumoApi`, responsável por realizar chamadas à API do OMDB, e `ConverteDados`, que converte os dados recebidos.

O **Projeto Screenmatch** é uma ferramenta valiosa para os amantes de séries, permitindo que usuários acompanhem suas produções favoritas de maneira organizada e informativa.
