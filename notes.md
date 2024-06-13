Flexonic templating requirements


Templating engine kiezen

Document creation engine
- Html -> pdf
- Source -> target

Hoe krijgen we data uit een ander system?
- Sidecar idee uitwerken

Sidecar is verantwoordelijk voor:
- Pollen voor veranderingen van de compositie dll’s
- Restarten van de main pod
- Eventueel cachen van data van de compositie dll’s
- Maak een docker image met DLL’s
    - Voeg toe als layer in de service image
- Sidecar kan ook checken op nieuwe image versie
- Wel of niet met sidecar?
    - Als we base image gebruiken kunnen we ook altijd alle services herstarten. Dan hoeven we geen sidecar te hebben.
    - Als de alleen de sidecar de compositie dll’s bevat dan is geen herstart nodig van de main pod
    - Aparte compositie service -> via bijvoorbeeld dapr
        - Call naar deze service mag geen contract zijn (dynamisch)
            - Key/value
        - High available
        - Client /server communicatie via daar
        - 

Versioning
- 

Beheer templates

- Id
- Versie
- Taal i18n
- Placeholders 
    - Required en optioneel
    - Available / validatie of hij bestaat
    - 
- Preview
- Sub templates
- Ingangs datum
- Folder management
- Auditing
    - Beheer
    - Runtime performance metrics
    - Activity log (sendgrid idee)
- 
