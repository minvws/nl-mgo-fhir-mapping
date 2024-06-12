 Model | Path | Mapping 
|----------|----------| ----------|
| MgoMedicationUse    | [MedicationStatement](MedicationStatement/?category=urn:oid:2.16.840.1.[…]0.20.77.5.3%7C6&_include=MedicationStatement:medication) | [packages/fhir-data/src/resource/getMgoMedicationStatements/getMgoMedicationStatements.ts](https://github.com/minvws/nl-mgo-app-web-private/blob/main/packages/fhir-data/src/resource/getMgoMedicationStatements/getMgoMedicationStatements.ts)
| MgoLaboratoryTestResult    | [Observation](Observation/$lastn?category=http://snomed.info/sct%7C275711006&_include=Observation:related-target&_include=Observation:specimen) |  [packages/fhir-data/src/resource/getMgoObservations/getMgoObservations.ts](https://github.com/minvws/nl-mgo-app-web-private/blob/main/packages/fhir-data/src/resource/getMgoObservations/getMgoObservations.ts)
| MgoConcern       | [Condition](Condition?_format=json) | [packages/fhir-data/src/resource/getMgoConditions/getMgoConditions.ts](https://github.com/minvws/nl-mgo-app-web-private/blob/main/packages/fhir-data/src/resource/getMgoConditions/getMgoConditions.ts)


The names of the models are a concatination of Mgo and the [HCIM column from the BGZ document](https://informatiestandaarden.nictiz.nl/wiki/MedMij:V2020.01/FHIR_BGZ_2017)