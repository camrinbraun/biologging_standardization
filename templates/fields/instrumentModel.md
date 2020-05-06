# Instrument Model

## Definition 
Name of specific tag model deployed

## Format
string, eg. “Mk10”

## Similar Terms 
* Movebank - "Tag Model" - http://vocab.nerc.ac.uk/collection/MVB/current/MVB000185/
* Tagbase - "Model" - https://github.com/tagbase/tagbase/blob/master/eTagMetadataInventory.csv#L6

## SensorML example
```
<sml:identification>
        <sml:IdentifierList>
            <sml:identifier>
                <sml:Term definition="http://urlToDefinitionOf/instrumentModel"">
                    <sml:label>Instrument Model</sml:label>
                    <sml:value>Mk10</sml:value>
                </sml:Term>
            </sml:identifier>
       </sml:IdentifierList>
 </sml:identification>"
  ```
## Darwin Core example
```
# measurementOrFact.csv
eventId, measurementType, measurementTypeID, measurementValue
institutionId:tagDeployment:XYZ, "instrumentModel", "http://urlToDefinitionOf/InstrumentModel", "Mk10"
