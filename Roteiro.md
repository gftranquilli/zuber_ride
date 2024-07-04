## Passo 4. Análise exploratória de dados (Python)

Além dos dados recuperados nas tarefas anteriores, você recebeu um segundo arquivo. Agora você tem estes dois CSVs:

- `/datasets/project_sql_result_01.csv`: contém os seguintes dados:
  - `trips_amount`: o número de corridas para cada empresa de táxi de 15 a 16 de novembro de 2017.

- `/datasets/project_sql_result_04.csv`: contém os seguintes dados:
  - `dropoff_location_name`: bairros de Chicago onde as corridas terminaram
  - `average_trips`: o número médio de viagens que terminaram em cada bairro em novembro de 2017.

Para esses dois conjuntos de dados, agora você precisa:
- importar os arquivos
- estudar os dados que eles contêm
- verificar se os tipos de dados estão corretos
- identificar os 10 principais bairros em termos de destinos
- fazer gráficos: empresas de táxi e número de corridas, top 10 bairros por número de corridas em que esse bairro é destino
- tirar conclusões com base em cada gráfico e explicar os resultados

## Passo 5. Testando hipóteses (Python)

- `/datasets/project_sql_result_07.csv`: o resultado da última consulta. Ele contém dados sobre viagens do Loop para o Aeroporto Internacional O'Hare. Lembre-se, estes são os valores dos campos da tabela:
  - `start_ts`: data e hora de coleta
  - `weather_conditions`: condições meteorológicas no momento em que a corrida começou
  - `duration_seconds`: duração da corrida em segundos

Teste a hipótese:

"A duração média dos passeios do Loop para o Aeroporto Internacional O'Hare muda nos sábados chuvosos."

Decida onde definir o nível de significância (alfa) por conta própria.

Explique:

- como você formou as hipóteses nula e alternativa
- qual critério você usou para testar a hipótese e porque

## Como o meu projeto será avaliado?

Aqui estão os critérios de avaliação do projeto. Leia-os cuidadosamente antes de começar a trabalhar.

Aqui está o que o revisor do projeto procurará ao avaliar seu projeto:

- como você recupera dados do site
- como você faz fatias de dados
- como você agrupa dados
- se você usa os vários métodos para combinar dados corretamente
- como você formula hipóteses
- quais critérios você usa para testar as hipóteses e por quê
- a que conclusões você chega
- se você deixa comentários a cada passo

As folhas de conclusões e resumos das lições anteriores têm tudo o que você precisa para completar o projeto.

Boa sorte!
