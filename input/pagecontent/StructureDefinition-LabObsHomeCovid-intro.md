The **Covid At Home FHIR Laboratory Observation Profile** is based upon the The [US Core Laboratory Result Observation Profile](http://hl7.org/fhir/us/core/StructureDefinition/us-core-observation-lab). In addition to the requirements set in the US Core Laboratory Result Observation Profile to record, search, and fetch/send laboratory test results associated with a patient, this profile:
* Constrains and binds observationCode to an at home Covid lab tests value set. (a subset of the required US Core LOINC lab codes)
* Observation.value to a value set of SNOMED CT codes appropriate for at hone covid test result values (a subset of the required US Core SNOMED CT lab result values)
* Sets forth some ID requirements in the referenced Device and Sample resources

This profile abides by the same rules and contraints identified in the US Core profile with respect to which core elements, extensions, vocabularies and value sets **SHALL** be present in the resource when using the US Core Laboratory observation profile. 