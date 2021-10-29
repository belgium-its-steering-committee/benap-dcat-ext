# benap-dcat-ext (DRAFT)

!! __this is a working document__ !! 
  
## Profile description
&nbsp;&nbsp;


### metadata

&nbsp;&nbsp;

| Property | Desciption  | Mandatory  | URI| Type | Vocabulary |
| ---------| ----------- |:----------:| ---| ------| --------- |
| language| Describes the language(s) in which you will fill in the metadata in this form. | true | dct:language | | [metadata language](https://github.com/belgium-its-steering-committee/benap-dcat-ext/blob/main/vocabularies.md#metadata-language)|
| title (name of the dataset)| Describes the dataset in generic terms or gives a short description. The author is encouraged to write a meaningful description in one of the selected metadata language.  Can be added in multiple languages using @language. See [here](https://github.com/belgium-its-steering-committee/benap-dcat-ext/blob/main/examples/multilanguage.xml) or [here](https://github.com/belgium-its-steering-committee/benap-dcat-ext/blob/main/examples/multilanguage.ttl)| true | dct:title | | |
| description | Gives the user more information about the content of the dataset or service. This MUST be filled in all selected metadata languages. Can be added in multiple languages using @language. See [here](https://github.com/belgium-its-steering-committee/benap-dcat-ext/blob/main/examples/multilanguage.xml) or [here](https://github.com/belgium-its-steering-committee/benap-dcat-ext/blob/main/examples/multilanguage.ttl)| true | dct:description | | |
| resource type | Dataset or Service | true | dct:type | | [resource type](https://github.com/belgium-its-steering-committee/benap-dcat-ext/blob/main/vocabularies.md#resource-type) |
| organisation name | The \"contact point\", describes an organisation, if applicable a person, which is responsible for the creation and maintenance of the metadata. This person or organization is the single point of contact for the present metadata set.  | true | dcat:contactPoint | [vcard](https://www.w3.org/TR/vocab-dcat/#bib-vcard-rdf") | |
| name contact point | Name contact point | true | dc:creator | | |
| organisation name publisher | The \"publisher\" describes an entity (company and person) that publishes the datasets (we are not refering to the metadata here, but rather to the data themselves). He or she is responsible for the given information and must be contacted by data consumers if a contract needs to be concluded.| true | | | |
| name publisher | Name publisher | true | dct:publisher | | |
| address publisher | Address publisher | true | | | |
| e-mail publisher | E-mail publisher | true | | | |
| website publisher | The website address must start with \"http://\", or \"https:// | false | | | |
| telephone number publisher | The telephone number must start with the country prefix (e.g. \",+32\" for Belgium) and may only contain numbers from 0 to 9 besides the \"+\" sign. | true | | | |
| start date of publication + time | Describes from which date and time on the data delivery is applicable.| true | dc:issued | | |
| end date of publication + time | Describes the date when data delivery to this publication terminates.| false | | | |
| countries covered | Describes the countries covered by the data set (Belgium is mandatory) | true | dct:spatial  | | [countries](https://github.com/belgium-its-steering-committee/benap-dcat-ext/blob/main/vocabularies.md#nap-countries)|
| regions covered | Describes the geographic area covered by the data set, based on the Nomenclature of Territorial Units for Statistics (NUTS). | true | dct:spatial  | | [regions](https://github.com/belgium-its-steering-committee/benap-dcat-ext/blob/main/vocabularies.md#nap-regions)|
| spatial| The extent of the dataset| false | dct:spatial | locn:geometry | |
| transportation modes| Describes the transportation mode(s) covered by the data set.| true | | | [transportation modes](https://github.com/belgium-its-steering-committee/benap-dcat-ext/blob/main/vocabularies.md#transportation-modes) |
| license | Describes the conditions of use of the data set. | true |  | | [license or contract](https://github.com/belgium-its-steering-committee/benap-dcat-ext/blob/main/vocabularies.md#data-contract-or-license)|
| license type | Describes the conditions of use of the data set. | true | dc:license | | [license](https://github.com/belgium-its-steering-committee/benap-dcat-ext/blob/main/vocabularies.md#data-license) |
| frequency | Describes the update rate of the data set. | true | dct:accrualPeriodicity | | [data update frequency](https://github.com/belgium-its-steering-committee/benap-dcat-ext/blob/main/vocabularies.md#data-update-frequency)|
| theme | Dataset theme | true | dcat:theme | | [theme](https://github.com/belgium-its-steering-committee/benap-dcat-ext/blob/main/vocabularies.md#data-theme)|

&nbsp;&nbsp;

### resource

&nbsp;&nbsp;

| Property | Desciption  | Mandatory  | URI| Type | Vocabulary |
| ---------| ----------- |:----------:| ---| ------| --------- |
| url | Resource URL, links must start with \"http://\", or \"https://\"| true | dcat:accessURL | | |
| name | Describes the resource you linked or uploaded in generic terms or gives a short description. The author is encouraged to write a meaningful description.| true | dct:title | | |
| data format encoding | This describes the atomic element of the transfer syntax description.| false | | | [data format encoding](https://github.com/belgium-its-steering-committee/benap-dcat-ext/blob/main/vocabularies.md#data-format-encoding)|
| data format syntax | This describes the base standard that specifies syntactically correct documents.| true | | | [data format syntax](https://github.com/belgium-its-steering-committee/benap-dcat-ext/blob/main/vocabularies.md#data-format-syntax)|
| data format grammar | This describes standards on top of the elementary syntax that describe data structures in the dataset.| false | | | [data format grammar](https://github.com/belgium-its-steering-committee/benap-dcat-ext/blob/main/vocabularies.md#data-format-grammar)|
| data format data model | This describes the specific data model used in the data.| true | | | [data format datamodel](https://github.com/belgium-its-steering-committee/benap-dcat-ext/blob/main/vocabularies.md#data-format-datamodel)|
| data format data description | Can be optionally used to provide additional information on the data format.| false | dc:description | | |
| access interface application layer protocol| Describes the IT protocol of the data interface that will be used to transfer data.| true | | | [data protocol](https://github.com/belgium-its-steering-committee/benap-dcat-ext/blob/main/vocabularies.md#data-protocol) |
| communication method| Describes the transmitting procedure from data provider to data receiver.| true | | | [communication method](https://github.com/belgium-its-steering-committee/benap-dcat-ext/blob/main/vocabularies.md#communication-method) |
| resource language| Describes the language of the data contents (text fields, addresses etc.)| true | dc:language | | [data language](https://github.com/belgium-its-steering-committee/benap-dcat-ext/blob/main/vocabularies.md#data-language)|

        
        


