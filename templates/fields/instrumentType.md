# Instrument Type

## Definition 
Type of tag deployed (eg. archival, satellite, popup, acoustic tag, acoustic receiver)

## Format
categorical, eg. “satellite”
Similar controlled vocabularies: ? (Movebank, eTuff)

## Vocabularies
* Movebank - "sensor type" - http://vocab.nerc.ac.uk/collection/MVB/current/MVB000170/
* TagBase - "instrument_type" - https://github.com/tagbase/tagbase/blob/master/eTagMetadataInventory.csv#L3

## SensorML example
```
<sml:classification>
        <sml:ClassifierList>
            <sml:classifier>
                <sml:Term definition="http://urlToDefinitionOf/InstrumentType">
                    <sml:label>Instrument Type</sml:label>
                    <sml:codeSpace xlink:href=""urn:x-ceos:def:GCMD:sensors""/>
                    <sml:value>satellite</sml:value>
                </sml:Term>
            </sml:classifier>
        </sml:ClassifierList>
  </sml:classification>
  ```
## Darwin Core example
```
# measurementOrFact.csv
eventId, measurementType, measurementTypeID, measurementValue
institutionId:tagDeployment:XYZ, "instrumentType", "http://urlToDefinitionOf/InstrumentType", "satellite"
