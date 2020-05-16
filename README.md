# conversor-moeda-html5
Conversor de moeda em HTML5 usando exchangeratesapi.io

## Onde publicar esta aplicação
Esta aplicação foi feita usando a SAP Web IDE FullStack e por isso pode facilmente ser hospedada no SAP Cloud Platform.

## Instruções de uso
Para chamada do web service, é necessário criar uma "destination" no SAP Cloud Platform.

Tal destination pode ser importada no SAP Cloud Platform Cockpit (Neo environment) usando o arquivo "ExchangeRates" presente no projeto.

No cockpit, use a opção "Connectivity >> Destinations", importe o arquivo e salva a destination.

É necessário recarregar a Web IDE caso ela esteja aberta.

O mapeamento da chamada da API para a destination é encontrado no arquivo `neo-app.json`