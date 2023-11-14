# Corpus de Lectura fàcil y comunicació clara
Corpus de documents de comunicaciò clara i lectura fàcil de la comunitat valenciana. Aquest corpus segueix en desenvolupament i de moment conté 48.000 tokens de documents.

## Estructura dels fitxers
Cada document aquesta disponible en format JSON, amb la següent estructura:
```
{
  "title":"título del documento",
  "version":"mes y año de la versión del documento",
  "url":"localización en línea del documento",
  "lf":"bool: indica si el documento es una versión en lectura fácil",
  "document":[
    {
      "page":"número de página",
      "text":"texto de la página"
    },
    {
      "page":"número de página",
      "content":"texto de la página"
    },
  ]
}
```
