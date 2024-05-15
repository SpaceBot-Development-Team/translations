# CÓMO CONTRIBUIR

Para poder contribuir a este proyecto has de tener conocimiento de JSON (es muy fácil)
y de la estructura de este proyecto.

El archivo, único, que contiene las traducciones es ``translations.json``.

Éste está organizado por idiomas, y tipo de traducción. Es decir:
```json
{
    "es-ES": {  // Esté es el código del idioma, válido por Discord
        "commands": {}, // En estas llaves se guardan los nombres de los comandos o subcomandos del bot
        "groups": {}, // Aquí solo se almacenan las traducciones de LOS GRUPOS "PADRE" de los comandos
        "descriptions": {}, // Aquí se almacenan las descripciones de los comandos
        "parameter_names": {}, //  Aquí se almacenan los nombres de los parámetros de los comandos
        "parameter_descriptions": {}, // Aquí, como en su covariante "descriptions", se almacenan descripciones, pero esta vez solo de parametros
        "responses": {}, // Aquí se guardan las traducciones de las respuestas que da el bot a los comandos
        "choices": {}, // Aquí se guardan las traducciones de las opciones que salen en el autcompletado personalizado de los comandos, por ejemplo, cuando intentas quitar un strike de un usuario que no tiene ninguno y sale, en español, "Este staff no tiene strikes..."
    }
}
```

A medida que transcurre el tiempo se añadirán más llaves, con sus respectivos subgrupos para poder traducir
aún más el bot y hacerlo accesible para todos.
