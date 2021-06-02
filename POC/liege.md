# Matching the Liege RDF export with BENAP DCAT


Liege URL [https://opendata.liege.be/api/v2/catalog/exports/rdf?refine=title%3AParkings%20taxis](https://opendata.liege.be/api/v2/catalog/exports/rdf?refine=title%3AParkings%20taxis)



        <?xml version="1.0" encoding="UTF-8"?>
        <rdf:RDF
           xmlns:dcat="http://www.w3.org/ns/dcat#"
           xmlns:dct="http://purl.org/dc/terms/"
           xmlns:foaf="http://xmlns.com/foaf/0.1/"
           xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#"
           xmlns:rdfs="http://www.w3.org/2000/01/rdf-schema#"
           xmlns:skos="http://www.w3.org/2004/02/skos/core#"
        >
            <rdf:Description rdf:about="https://opendata.liege.be/api/v2/catalog/datasets/parkings-taxis">
                <rdf:type rdf:resource="http://www.w3.org/ns/dcat#Dataset"/>
                <dcat:distribution rdf:resource="https://opendata.liege.be/api/v2/catalog/datasets/parkings-taxis-json"/>
                <dcat:keyword>mobilité</dcat:keyword>
                <dcat:distribution rdf:resource="https://opendata.liege.be/api/v2/catalog/datasets/parkings-taxis-geojson"/>
                <dcat:distribution rdf:resource="https://opendata.liege.be/api/v2/catalog/datasets/parkings-taxis-csv"/>
                <dct:description>&lt;p&gt;Le jeu de données reprend les géolocalisations des lieux de stationnement des taxis sur le territoire de la Ville de Liège.&lt;/p&gt;
                &lt;hr/&gt;
                &lt;p&gt;&lt;em&gt;Les informations sont régulièrement vérifiées par nos services sur le terrain. Cependant, il est possible qu'un décalage existe entre le moment de collecte des données, de leurs modifications et la publication de mise à jour de la base de données sur la plateforme.&lt;/em&gt;&lt;/p&gt;
                &lt;p&gt;&lt;em&gt;Vous avez une question ou une remarque à formuler ? &lt;a href="https://opendata.liege.be/pages/contact/"&gt;Contactez-nous&lt;/a&gt;.&lt;/em&gt;&lt;/p&gt;
                </dct:description>
                <dcat:keyword>taxi</dcat:keyword>
                <dct:identifier>parkings-taxis</dct:identifier>
                <dcat:theme rdf:resource="https://opendata.liege.be/id/theme/Mobilit%C3%A9%2C%20Espace%20public"/>
                <dct:title>Parkings taxis</dct:title>
                <dcat:keyword>déplacement</dcat:keyword>
                <dct:language rdf:resource="http://id.loc.gov/vocabulary/iso639-1/fr"/>
                <dcat:distribution rdf:resource="https://opendata.liege.be/api/v2/catalog/datasets/parkings-taxis-shp"/>
                <dct:publisher rdf:nodeID="N2262f9de862c411d895436dcab70f062"/>
            </rdf:Description>
            <rdf:Description rdf:about="http://www.opendatasoft.com">
                <rdf:type rdf:resource="http://xmlns.com/foaf/0.1/Agent"/>
                <foaf:name>Opendatasoft</foaf:name>
            </rdf:Description>
            <rdf:Description rdf:about="https://opendata.liege.be/api/v2/catalog/datasets/parkings-taxis-json">
                <rdf:type rdf:resource="http://www.w3.org/ns/dcat#Distribution"/>
                <dcat:mediaType>application/json</dcat:mediaType>
                <dct:license>CC BY</dct:license>
                <dcat:accessURL rdf:resource="https://opendata.liege.be/api/v2/catalog/datasets/parkings-taxis/exports/json"/>
                <dct:format>json</dct:format>
                <dct:description>json export of https://opendata.liege.be/api/v2/catalog/datasets/parkings-taxis</dct:description>
            </rdf:Description>
            <rdf:Description rdf:about="https://opendata.liege.be/api/v2/catalog/exports/rdf?refine=title%3AParkings%20taxis">
                <dct:title>Liege's catalog</dct:title>
                <foaf:homepage rdf:resource="https://opendata.liege.be"/>
                <dcat:themeTaxonomy rdf:resource="https://opendata.liege.be/concept-scheme/themes"/>
                <dct:Language rdf:resource="http://id.loc.gov/vocabulary/iso639-1/fr"/>
                <dct:publisher rdf:resource="http://www.opendatasoft.com"/>
                <dcat:dataset rdf:resource="https://opendata.liege.be/api/v2/catalog/datasets/parkings-taxis"/>
                <dct:description>Liege Catalog</dct:description>
                <rdf:type rdf:resource="http://www.w3.org/ns/dcat#Catalog"/>
            </rdf:Description>
            <rdf:Description rdf:about="https://opendata.liege.be/concept-scheme/themes">
                <dct:title>Themes</dct:title>
                <rdf:type rdf:resource="http://www.w3.org/2004/02/skos/core#ConceptScheme"/>
                <skos:prefLabel>A Set of data themes</skos:prefLabel>
                <skos:topConceptOf rdf:resource="https://opendata.liege.be/id/theme/Mobilit%C3%A9%2C%20Espace%20public"/>
            </rdf:Description>
            <rdf:Description rdf:nodeID="N2262f9de862c411d895436dcab70f062">
                <rdf:type rdf:resource="http://xmlns.com/foaf/0.1/Agent"/>
                <rdfs:label>Ville de Liège</rdfs:label>
            </rdf:Description>
            <rdf:Description rdf:about="https://opendata.liege.be/id/theme/Mobilit%C3%A9%2C%20Espace%20public">
                <skos:prefLabel>Mobilité, Espace public</skos:prefLabel>
                <rdf:type rdf:resource="http://www.w3.org/2004/02/skos/core#Concept"/>
                <dct:title>Mobilité, Espace public</dct:title>
                <skos:inScheme rdf:resource="https://opendata.liege.be/concept-scheme/themes"/>
            </rdf:Description>
            <rdf:Description rdf:about="https://opendata.liege.be/api/v2/catalog/datasets/parkings-taxis-geojson">
                <dct:description>geojson export of https://opendata.liege.be/api/v2/catalog/datasets/parkings-taxis</dct:description>
                <dcat:accessURL rdf:resource="https://opendata.liege.be/api/v2/catalog/datasets/parkings-taxis/exports/geojson"/>
                <dct:license>CC BY</dct:license>
                <dcat:mediaType>application/json</dcat:mediaType>
                <rdf:type rdf:resource="http://www.w3.org/ns/dcat#Distribution"/>
                <dct:format>geojson</dct:format>
            </rdf:Description>
            <rdf:Description rdf:about="https://opendata.liege.be/api/v2/catalog/datasets/parkings-taxis-csv">
                <dcat:mediaType>text/csv</dcat:mediaType>
                <dcat:accessURL rdf:resource="https://opendata.liege.be/api/v2/catalog/datasets/parkings-taxis/exports/csv"/>
                <rdf:type rdf:resource="http://www.w3.org/ns/dcat#Distribution"/>
                <dct:description>csv export of https://opendata.liege.be/api/v2/catalog/datasets/parkings-taxis</dct:description>
                <dct:format>csv</dct:format>
                <dct:license>CC BY</dct:license>
            </rdf:Description>
            <rdf:Description rdf:about="https://opendata.liege.be/api/v2/catalog/datasets/parkings-taxis-shp">
                <rdf:type rdf:resource="http://www.w3.org/ns/dcat#Distribution"/>
                <dct:format>shp</dct:format>
                <dct:license>CC BY</dct:license>
                <dcat:mediaType>application/zip</dcat:mediaType>
                <dct:description>shp export of https://opendata.liege.be/api/v2/catalog/datasets/parkings-taxis</dct:description>
                <dcat:accessURL rdf:resource="https://opendata.liege.be/api/v2/catalog/datasets/parkings-taxis/exports/shp"/>
            </rdf:Description>
        </rdf:RDF>


### metadata

&nbsp;&nbsp;

| Property | Desciption  | Mandatory  | Vocabulary | ok/nok Liege | location | remarks |
| ---------| ----------- |:----------:| --------- | --------- | --------- | ------- |
| language| Describes the language(s) in which you will fill in the metadata in this form. | true | [metadata language](https://github.com/belgium-its-steering-committee/benap-dcat-ext/blob/main/vocabularies.md#metadata-language)| nok | dct:language | not following vocabulary
| title| Describes the dataset in generic terms or gives a short description. The author is encouraged to write a meaningful description in one of the selected metadata language. | true | | ok | dct:title|
| description | Gives the user more information about the content of the dataset or service. This MUST be filled in all selected metadata languages. | true | | ok | dct:description|
| resource type | Dataset or Service | true | | nok | |
| organisation name | The \"contact point\", describes an organisation, if applicable a person, which is responsible for the creation and maintenance of the metadata. This person or organization is the single point of contact for the present metadata set.  | true | | ok | | auto filled by harvester|
| name contact point | Name contact point | true | | nok | |
| organisation name publisher | The \"publisher\" describes an entity (company and person) that publishes the datasets (we are not refering to the metadata here, but rather to the data themselves). He or she is responsible for the given information and must be contacted by data consumers if a contract needs to be concluded.| true | | nok | |
| name publisher | Name publisher | true | | ok | dct:publisher -> rdfs:label|
| address publisher | Address publisher | true | | nok | |
| e-mail publisher | E-mail publisher | true | | nok | |
| website publisher | The website address must start with \"http://\", or \"https:// | false | | ok | |
| telephone number publisher | The telephone number must start with the country prefix (e.g. \",+32\" for Belgium) and may only contain numbers from 0 to 9 besides the \"+\" sign. | true | | nok | |
| start data of publication + time | Describes from which date and time on the data delivery is applicable.| true | | nok | |
| end data of publication + time | Describes the date when data delivery to this publication terminates.| false | | ok | |
| countries covered | Describes the countries covered by the data set (Belgium is mandatory) | true | [countries](https://github.com/belgium-its-steering-committee/benap-dcat-ext/blob/main/vocabularies.md#nap-countries)| nok | |
| regions covered | Describes the geographic area covered by the data set, based on the Nomenclature of Territorial Units for Statistics (NUTS). | true | [regions](https://github.com/belgium-its-steering-committee/benap-dcat-ext/blob/main/vocabularies.md#nap-regions)|
| spatial| The extent of the dataset| false | | nok | |
| transportation modes| Describes the transportation mode(s) covered by the data set.| true | | nok | |
| license | Describes the conditions of use of the data set. | true | [license](https://github.com/belgium-its-steering-committee/benap-dcat-ext/blob/main/vocabularies.md#data-license)| nok | |
| license type | Describes the conditions of use of the data set. | true | | nok | dct:license | Is on the resources, not on the dataset
| frequency | Describes the update rate of the data set. | true | [data update frequency](https://github.com/belgium-its-steering-committee/benap-dcat-ext/blob/main/vocabularies.md#data-update-frequency)| nok | |
| theme | Dataset theme | true | [theme](https://github.com/belgium-its-steering-committee/benap-dcat-ext/blob/main/vocabularies.md#data-theme)| nok | dcat:theme | not following vocabulary

&nbsp;&nbsp;

### resource

&nbsp;&nbsp;

| Property | Desciption  | Mandatory  | Vocabulary | ok/nok Liege | location |  remarks |
| ---------| ----------- |:----------:| --------- | :---------: | --------- |  ------- |
| url | Resource URL, links must start with \"http://\", or \"https://\"| true | | ok | dcat:accessURL |
| name | Describes the resource you linked or uploaded in generic terms or gives a short description. The author is encouraged to write a meaningful description.| true | | ok | dct:description|
| data format encoding | This describes the atomic element of the transfer syntax description.| false | [data format encoding](https://github.com/belgium-its-steering-committee/benap-dcat-ext/blob/main/vocabularies.md#data-format-encoding)| ok | |
| data format syntax | This describes the base standard that specifies syntactically correct documents.| true | [data format syntax](https://github.com/belgium-its-steering-committee/benap-dcat-ext/blob/main/vocabularies.md#data-format-syntax)| ok |  dct:format |
| data format grammar | This describes standards on top of the elementary syntax that describe data structures in the dataset.| false | [data format grammar](https://github.com/belgium-its-steering-committee/benap-dcat-ext/blob/main/vocabularies.md#data-format-grammar)| ok | |
| data format data model | This describes the specific data model used in the data.| true | [data format datamodel](https://github.com/belgium-its-steering-committee/benap-dcat-ext/blob/main/vocabularies.md#data-format-datamodel)| nok |  | 
| data format data description | Can be optionally used to provide additional information on the data format.| false | | ok | |
| access interface application layer protocol| Describes the IT protocol of the data interface that will be used to transfer data.| true | [data protocol](https://github.com/belgium-its-steering-committee/benap-dcat-ext/blob/main/vocabularies.md#data-protocol) | nok | |
| communication method| Describes the transmitting procedure from data provider to data receiver.| true | [communication method](https://github.com/belgium-its-steering-committee/benap-dcat-ext/blob/main/vocabularies.md#communication-method) | nok | |
| resource language| Describes the language of the data contents (text fields, addresses etc.)| true | [data language](https://github.com/belgium-its-steering-committee/benap-dcat-ext/blob/main/vocabularies.md#data-language)| nok | |

        
        


