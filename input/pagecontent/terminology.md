This page includes the value sets and code systems supported in AU Patient Summary (AU PS).  

AU PS does not define any unique terminology FHIR artefacts. Terminology supported in AU PS are published in [AU Base](https://build.fhir.org/ig/hl7au/au-fhir-base/terminology.html), the base FHIR specification, [HL7 Terminology (THO)](https://terminology.hl7.org/), or the [National Clinical Terminology Service (NCTS)](https://www.healthterminologies.gov.au/).

<div class="stu-note">
Implementers are advised to take note that expansions of value sets visible in this guide may differ from expansions returned with a server using <a href="http://terminology.hl7.org">HL7 Terminology (THO)</a> version 6.0.0 or higher.
</div>

### Value Sets

The following value sets are supported in AU PS, i.e bound as [preferred](https://hl7.org/fhir/R4/terminologies.html#preferred) or stronger to a supported element, element slice, or extension in an AU PS profile.

Column attribute descriptions are as follows:
<ul>
  <li><strong>ValueSet:</strong> The title of the value set.</li>
  <li><strong>Profiles and Extensions where used:</strong> The profiles and extensions that reference the value set.</li>
  <li><strong>Available from:</strong> Where the value set is published.</li>
</ul>  

|ValueSet|Profiles and Extensions where used|Available from|
|---|---|---|
|[ActEncounterCode - AU Extended](https://build.fhir.org/ig/hl7au/au-fhir-base//ValueSet-au-v3-ActEncounterCode-extended.html)|[AU PS Encounter](StructureDefinition-au-ps-encounter.html)|AU Base|
|[AdministrativeGender](https://hl7.org/fhir/R4/valueset-administrative-gender.html)|[AU PS Patient](StructureDefinition-au-ps-patient.html)|FHIR|
|[AddressUse](https://hl7.org/fhir/R4/valueset-address-use.html)|[AU Core Location](https://build.fhir.org/ig/hl7au/au-fhir-core/StructureDefinition-au-core-location.html), [AU PS Organization](StructureDefinition-au-ps-organization.html), [AU PS Patient](StructureDefinition-au-ps-patient.html), [AU PS Practitioner](StructureDefinition-au-ps-practitioner.html), [AU PS RelatedPerson](StructureDefinition-au-ps-relatedperson.html)|FHIR|
|[AddressType](https://hl7.org/fhir/R4/valueset-address-type.html)|[AU Core Location](https://build.fhir.org/ig/hl7au/au-fhir-core/StructureDefinition-au-core-location.html), [AU PS Organization](StructureDefinition-au-ps-organization.html), [AU PS Patient](StructureDefinition-au-ps-patient.html), [AU PS Practitioner](StructureDefinition-au-ps-practitioner.html), [AU PS RelatedPerson](StructureDefinition-au-ps-relatedperson.html)|FHIR|
|[AllergyIntolerance Clinical Status Codes](https://hl7.org/fhir/R4/valueset-allergyintolerance-clinical.html)|[AU PS AllergyIntolerance](StructureDefinition-au-ps-allergyintolerance.html)|FHIR|
|[AllergyIntolerance Verification Status Codes](http://hl7.org/fhir/R4/valueset-allergyintolerance-verification.html)|[AU PS AllergyIntolerance](StructureDefinition-au-ps-allergyintolerance.html)|FHIR|
|[AllergyIntoleranceSeverity](http://hl7.org/fhir/R4/valueset-reaction-event-severity.html)|[AU PS AllergyIntolerance](StructureDefinition-au-ps-allergyintolerance.html)|FHIR|
|[AllergyIntoleranceType](https://hl7.org/fhir/R4/valueset-allergy-intolerance-type.html)|[AU PS AllergyIntolerance](StructureDefinition-au-ps-allergyintolerance.html)|FHIR|
|[AMT Medicinal Product and Substances](https://build.fhir.org/ig/hl7au/au-fhir-base/ValueSet-amt-mp-codes.html)|[AU PS Medication](StructureDefinition-au-ps-medication.html)|AU Base|
|[Australian Immunisation Register Vaccine](https://healthterminologies.gov.au/fhir/ValueSet/australian-immunisation-register-vaccine-1)|[AU PS Immunization](StructureDefinition-au-ps-immunization.html)|NCTS|
|[Australian Indigenous Status](https://healthterminologies.gov.au/fhir/ValueSet/australian-indigenous-status-1)|[AU PS Patient](StructureDefinition-au-ps-patient.html)|NCTS|
|[Australian Medication](https://healthterminologies.gov.au/fhir/ValueSet/australian-medication-1)|[AU PS Medication](StructureDefinition-au-ps-medication.html), [AU PS MedicationRequest](StructureDefinition-au-ps-medicationrequest.html), [AU PS MedicationStatement](StructureDefinition-au-ps-medicationstatement.html)|NCTS|
|[Australian Medicines Terminology Vaccine](https://healthterminologies.gov.au/fhir/ValueSet/amt-vaccine-1)|[AU PS Immunization](StructureDefinition-au-ps-immunization.html)|NCTS|
|[Australian Pronouns](https://healthterminologies.gov.au/fhir/ValueSet/australian-pronouns-1)|[Individual Pronouns](http://hl7.org/fhir/StructureDefinition/individual-pronouns)|NCTS|
|[Australian States and Territories](https://healthterminologies.gov.au/fhir/ValueSet/australian-states-territories-2)|[AU Core Location](https://build.fhir.org/ig/hl7au/au-fhir-core/StructureDefinition-au-core-location.html), [AU PS Organization](https://build.fhir.org/ig/hl7au/au-fhir-ps/StructureDefinition-au-ps-organization.html), [AU PS Patient](https://build.fhir.org/ig/hl7au/au-fhir-ps/StructureDefinition-au-ps-patient.html), [AU PS Practitioner](StructureDefinition-au-ps-practitioner.html), [AU PS RelatedPerson](StructureDefinition-au-ps-relatedperson.html)|NCTS|
|[Clinical Condition](https://healthterminologies.gov.au/fhir/ValueSet/clinical-condition-1)|[AU PS Condition](StructureDefinition-au-ps-condition.html)|NCTS|
|[Clinical Finding](https://healthterminologies.gov.au/fhir/ValueSet/clinical-finding-1)|[AU PS AllergyIntolerance](StructureDefinition-au-ps-allergyintolerance.html), [AU PS MedicationRequest](StructureDefinition-au-ps-medicationrequest.html), [AU PS MedicationStatement](StructureDefinition-au-ps-medicationstatement.html)|NCTS|
|[Clinical Specialty](https://healthterminologies.gov.au/fhir/ValueSet/clinical-specialty-1)|[AU PS PractitionerRole](StructureDefinition-au-ps-practitionerrole.html)|NCTS|
|[Common Languages in Australia](https://healthterminologies.gov.au/fhir/ValueSet/common-languages-australia-2)|[AU PS Patient](StructureDefinition-au-ps-patient.html)|NCTS|
|[CompositionAttestationMode](http://hl7.org/fhir/R4/valueset-composition-attestation-mode.html)|[AU PS Composition](StructureDefinition-au-ps-composition.html)|FHIR|
|[CompositionStatus](http://hl7.org/fhir/ValueSet/composition-status)|[AU PS Composition](StructureDefinition-au-ps-composition.html)|FHIR|
|[Condition/Diagnosis Severity](https://hl7.org/fhir/R4/valueset-condition-severity.html)|[AU PS Condition](StructureDefinition-au-ps-condition.html)|FHIR|
|[Condition Category Codes](https://hl7.org/fhir/R4/valueset-condition-category.html)|[AU PS Condition](StructureDefinition-au-ps-condition.html)|FHIR|
|[Condition Clinical Status Codes](https://hl7.org/fhir/R4/valueset-condition-clinical.html)|[AU PS Condition](StructureDefinition-au-ps-condition.html)|FHIR|
|[ConditionVerificationStatus](https://hl7.org/fhir/R4/valueset-condition-ver-status.html)|[AU PS Condition](StructureDefinition-au-ps-condition.html)|FHIR|
|[ContactPointSystem](https://hl7.org/fhir/R4/valueset-contact-point-system.html)|[AU PS Organization](StructureDefinition-au-ps-organization.html), [AU PS Patient](StructureDefinition-au-ps-patient.html), [AU PS Practitioner](StructureDefinition-au-ps-practitioner.html), [AU PS PractitionerRole](StructureDefinition-au-ps-practitionerrole.html), [AU PS RelatedPerson](StructureDefinition-au-ps-relatedperson.html)|FHIR|
|[ContactPointUse](https://hl7.org/fhir/R4/valueset-contact-point-use.html)|[AU PS Organization](StructureDefinition-au-ps-organization.html), [AU PS Patient](StructureDefinition-au-ps-patient.html), [AU PS Practitioner](StructureDefinition-au-ps-practitioner.html), [AU PS PractitionerRole](StructureDefinition-au-ps-practitionerrole.html), [AU PS RelatedPerson](StructureDefinition-au-ps-relatedperson.html)|FHIR|
|[DataAbsentReason](https://hl7.org/fhir/R4/valueset-data-absent-reason.html)|[AU PS Pathology Result Observation](StructureDefinition-au-ps-diagnosticresult-path.html), [AU PS Smoking Status](StructureDefinition-au-ps-smokingstatus.html)|FHIR|
|[DVA Entitlement](https://build.fhir.org/ig/hl7au/au-fhir-base/ValueSet-dva-entitlement.html)|[AU PS Patient](StructureDefinition-au-ps-patient.html)|AU Base|
|[EncounterStatus](https://hl7.org/fhir/R4/valueset-encounter-status.html)|[AU PS Encounter](StructureDefinition-au-ps-encounter.html)|FHIR|
|[EventStatus](https://hl7.org/fhir/R4/valueset-event-status.html)|[AU PS Procedure](StructureDefinition-au-ps-procedure.html)|FHIR|
|[Gender Identity Response](https://healthterminologies.gov.au/fhir/ValueSet/gender-identity-response-1)|[Individual Gender Identity](http://hl7.org/fhir/StructureDefinition/individual-genderIdentity)|NCTS|
|[Healthcare Organisation Role Type](https://healthterminologies.gov.au/fhir/ValueSet/healthcare-organisation-role-type-1)|[AU PS Organization](StructureDefinition-au-ps-organization.html)|NCTS|
|[hl7VS-identifierType - AU Extended](https://build.fhir.org/ig/hl7au/au-fhir-base//ValueSet-au-v2-0203-extended.html)|[AU PS Organization](StructureDefinition-au-ps-organization.html)|AU Base|
|[IdentifierUse](https://hl7.org/fhir/R4/valueset-identifier-use.html)|[AU PS Patient](StructureDefinition-au-ps-patient.html), [AU PS Practitioner](StructureDefinition-au-ps-practitioner.html), [AU PS PractitionerRole](StructureDefinition-au-ps-practitionerrole.html), [AU PS Organization](StructureDefinition-au-ps-organization.html) |FHIR|
|[Immunization Status Codes](https://hl7.org/fhir/R4/valueset-immunization-status.html)|[AU PS Immunization](StructureDefinition-au-ps-immunization.html)|FHIR|
|[Indicator of Hypersensitivity or Intolerance to Substance](https://healthterminologies.gov.au/fhir/ValueSet/indicator-hypersensitivity-intolerance-to-substance-2)|[AU PS AllergyIntolerance](StructureDefinition-au-ps-allergyintolerance.html)|NCTS|
|[Individual Healthcare Identifier Record Status](https://healthterminologies.gov.au/fhir/ValueSet/ihi-record-status-1)|[AU PS Patient](StructureDefinition-au-ps-patient.html)|NCTS|
|[Individual Healthcare Identifier Status](https://healthterminologies.gov.au/fhir/ValueSet/ihi-status-1)|[AU PS Patient](StructureDefinition-au-ps-patient.html)|NCTS|
|[List Empty Reasons](https://hl7.org/fhir/R4/valueset-list-empty-reason.html)|[AU PS Composition](StructureDefinition-au-ps-composition.html)|FHIR|
|[Location Type (Physical) - AU Extended](https://build.fhir.org/ig/hl7au/au-fhir-base//ValueSet-au-location-physical-type-extended.html)|[AU Core Location](https://build.fhir.org/ig/hl7au/au-fhir-core/StructureDefinition-au-core-location.html)|AU Base|
|[Medication Form](https://healthterminologies.gov.au/fhir/ValueSet/medication-form-1)|[AU PS Medication](StructureDefinition-au-ps-medication.html)|FHIR|
|[Medication Reason Taken](https://healthterminologies.gov.au/fhir/ValueSet/medication-reason-taken-1)|[AU PS MedicationStatement](StructureDefinition-au-ps-medicationstatement.html)|FHIR|
|[Medicationrequest status](https://hl7.org/fhir/R4/valueset-medicationrequest-status.html)|[AU PS MedicationRequest](StructureDefinition-au-ps-medicationrequest.html)|FHIR|
|[Medication request intent](https://hl7.org/fhir/R4/valueset-medicationrequest-intent.html)|[AU PS MedicationRequest](StructureDefinition-au-ps-medicationrequest.html)|FHIR|
|[Medication status codes](https://hl7.org/fhir/R4/valueset-medication-statement-status.html)|[AU PS MedicationStatement](StructureDefinition-au-ps-medicationstatement.html)|FHIR|
|[NameUse](https://hl7.org/fhir/R4/valueset-name-use.html)|[AU PS Patient](StructureDefinition-au-ps-patient.html), [AU PS Practitioner](StructureDefinition-au-ps-practitioner.html), [AU PS RelatedPerson](StructureDefinition-au-ps-relatedperson.html)|FHIR|
|[Observation Category Codes](https://hl7.org/fhir/R4/valueset-observation-category.html)|[AU PS Pathology Result Observation](StructureDefinition-au-ps-diagnosticresult-path.html), [AU PS Smoking Status](StructureDefinition-au-ps-smokingstatus.html)|FHIR|
|[Observation Interpretation Codes](https://hl7.org/fhir/R4/valueset-observation-interpretation.html)|[AU PS Pathology Result Observation](StructureDefinition-au-ps-diagnosticresult-path.html)|FHIR|
|[Observation Reference Range Meaning Codes](https://hl7.org/fhir/R4/valueset-referencerange-meaning.html)|[AU PS Pathology Result Observation](StructureDefinition-au-ps-diagnosticresult-path.html)|FHIR|
|[ObservationStatus](http://hl7.org/fhir/R4/valueset-observation-status.html)|[AU PS Smoking Status](StructureDefinition-au-ps-smokingstatus.html)|FHIR|
|[Participant type](https://hl7.org/fhir/R4/valueset-encounter-participant-type.html)|[AU PS Encounter](StructureDefinition-au-ps-encounter.html)|FHIR|
|[Pathology Diagnostic Service Category](https://healthterminologies.gov.au/fhir/ValueSet/pathology-diagnostic-service-category-1)|[AU PS Pathology Result Observation](StructureDefinition-au-ps-diagnosticresult-path.html)|NCTS|
|[PBS Item Codes](https://build.fhir.org/ig/hl7au/au-fhir-base/ValueSet-pbs-item.html)|[AU PS Medication](StructureDefinition-au-ps-medication.html), [AU PS MedicationRequest](StructureDefinition-au-ps-medicationrequest.html), [AU PS MedicationStatement](StructureDefinition-au-ps-medicationstatement.html)|AU Base|
|[Practitioner Role](https://healthterminologies.gov.au/fhir/ValueSet/practitioner-role-1)|[AU PS PractitionerRole](StructureDefinition-au-ps-practitionerrole.html)|NCTS|
|[Procedure](https://healthterminologies.gov.au/fhir/ValueSet/procedure-1)|[AU PS Procedure](StructureDefinition-au-ps-procedure.html)|NCTS|
|[RCPA SPIA Pathology Reporting](https://healthterminologies.gov.au/fhir/ValueSet/spia-pathology-reporting-1)|[AU PS Pathology Result Observation](StructureDefinition-au-ps-diagnosticresult-path.html)|NCTS|
|[Reason for Encounter](https://healthterminologies.gov.au/fhir/ValueSet/reason-for-encounter-1)|[AU PS Encounter](StructureDefinition-au-ps-encounter.html)|NCTS|
|[Reason for Request](https://healthterminologies.gov.au/fhir/ValueSet/reason-for-request-1)|[AU PS MedicationRequest](StructureDefinition-au-ps-medicationrequest.html)|NCTS|
|[Related Person Relationship Type](https://healthterminologies.gov.au/fhir/ValueSet/related-person-relationship-type-1)|[AU PS RelatedPerson](StructureDefinition-au-ps-relatedperson.html)|NCTS|
|[Results Status Codes - IPS](https://build.fhir.org/ig/HL7/fhir-ips/ValueSet-results-status-uv-ips.html)|[AU PS Pathology Result Observation](StructureDefinition-au-ps-diagnosticresult-path.html)|FHIR|
|[Route of Administration](https://healthterminologies.gov.au/fhir/ValueSet/route-of-administration-1)|[AU PS MedicationRequest](StructureDefinition-au-ps-medicationrequest.html), [AU PS MedicationStatement](StructureDefinition-au-ps-medicationstatement.html)|NCTS|
|[Service Type](https://healthterminologies.gov.au/fhir/ValueSet/service-type-1)|[AU PS Encounter](StructureDefinition-au-ps-encounter.html)|NCTS|
|[ServiceDeliveryLocationRoleType - AU Extended](https://build.fhir.org/ig/hl7au/au-fhir-base//ValueSet-au-v3-ServiceDeliveryLocationRoleType-extended.html)|[AU Core Location](https://build.fhir.org/ig/hl7au/au-fhir-core/StructureDefinition-au-core-location.html)|AU Base|
|[Smoking Status](https://healthterminologies.gov.au/fhir/ValueSet/smoking-status-1)|[AU PS Smoking Status](StructureDefinition-au-ps-smokingstatus.html)|NCTS|
|[SNOMED CT Additional Dosage Instructions](https://hl7.org/fhir/R4/valueset-additional-instruction-codes.html)|[AU PS MedicationRequest](StructureDefinition-au-ps-medicationrequest.html), [AU PS MedicationStatement](StructureDefinition-au-ps-medicationstatement.html)|FHIR|
|[SNOMED CT Administration Method Codes](https://hl7.org/fhir/R4/valueset-administration-method-codes.html)|[AU PS MedicationRequest](StructureDefinition-au-ps-medicationrequest.html), [AU PS MedicationStatement](StructureDefinition-au-ps-medicationstatement.html)|FHIR|
{:.grid}

### Code Systems

See the [FHIR terminology section]({{site.data.fhir.path}}terminologies-systems.html) for a complete discussion on code systems and a list of code system names used in FHIR. 

The following code systems are referenced by the value sets listed above or are the code system for a fixed value in an AU PS profile.

Column attribute descriptions are as follows:
<ul>
  <li><strong>CodeSystem:</strong> The title of a code system.</li>
  <li><strong>ValueSet where used:</strong> The value set(s) that reference the code system or the profile where a fixed value is applied.</li>
  <li><strong>Available from:</strong> Where the code system is published.</li>
  <li><strong>Publisher:</strong> Identifies the organisation responsible for maintaining the code system.</li>
</ul>

|CodeSystem|ValueSet where used|Available from|Publisher|
|---|---|---|---|
|[ActCode AU](https://build.fhir.org/ig/hl7au/au-fhir-base/CodeSystem-au-v3-ActCode.html)|[ActEncounterCode - AU Extended](https://build.fhir.org/ig/hl7au/au-fhir-base/ValueSet-au-v3-ActEncounterCode-extended.html)|AU Base|HL7 Australia|
|[ActCode](https://terminology.hl7.org/5.3.0/CodeSystem-v3-ActCode.html)|[ActEncounterCode](https://terminology.hl7.org/5.5.0/ValueSet-v3-ActEncounterCode.html)|HL7 Terminology (THO)|Health Level Seven International|
|[AddressUse](https://hl7.org/fhir/R4/codesystem-address-use.html)|[AddressUse](https://hl7.org/fhir/R4/valueset-address-use.html)|FHIR|Health Level Seven International|
|[AddressType](https://hl7.org/fhir/R4/codesystem-address-type.html)|[AddressType](https://hl7.org/fhir/R4/valueset-address-type.html)|FHIR|Health Level Seven International|
|[AdministrativeGender](https://hl7.org/fhir/R4/codesystem-administrative-gender.html)|[AdministrativeGender](https://hl7.org/fhir/R4/valueset-administrative-gender.html)|FHIR|Health Level Seven International|
|[AllergyIntolerance Clinical Status Codes](https://hl7.org/fhir/R4/codesystem-allergyintolerance-clinical.html)|[AllergyIntolerance Clinical Status Codes](https://hl7.org/fhir/R4/valueset-allergyintolerance-clinical.html)|FHIR|Health Level Seven International|
|[AllergyIntolerance Verification Status](https://hl7.org/fhir/R4/codesystem-allergyintolerance-verification.html)|[AllergyIntolerance Verification Status Codes](http://hl7.org/fhir/R4/valueset-allergyintolerance-verification.html)|FHIR|Health Level Seven International|
|[AllergyIntoleranceSeverity](https://hl7.org/fhir/R4/codesystem-reaction-event-severity.html)|[AllergyIntoleranceSeverity](https://hl7.org/fhir/R4/valueset-reaction-event-severity.html)|FHIR|Health Level Seven International|
|[AllergyIntoleranceType](https://hl7.org/fhir/R4/codesystem-allergy-intolerance-type.html)|[AllergyIntoleranceType](https://hl7.org/fhir/R4/valueset-allergy-intolerance-type.html)|FHIR|Health Level Seven International|
|[Australian Immunisation Register Vaccine](https://www.servicesaustralia.gov.au/air-vaccine-code-formats?context=20)|[Australian Immunisation Register Vaccine](https://healthterminologies.gov.au/fhir/ValueSet/australian-immunisation-register-vaccine-1)|NCTS|Services Australia|
|[Australian Indigenous Status](https://healthterminologies.gov.au/fhir/CodeSystem/australian-indigenous-status-1)|[Australian Indigenous Status](https://healthterminologies.gov.au/fhir/ValueSet/australian-indigenous-status-1)|NCTS|Australian Digital Health Agency|
|[CompositionAttestationMode](http://hl7.org/fhir/R4/codesystem-composition-attestation-mode.html)|[CompositionAttestationMode](http://hl7.org/fhir/R4/valueset-composition-attestation-mode.html)|FHIR|Health Level Seven International|
|[CompositionStatus](http://hl7.org/fhir/R4/codesystem-composition-status.html)|[CompositionStatus](http://hl7.org/fhir/R4/valueset-composition-status.html)|FHIR|Health Level Seven International|
|[Australian States and Territories](https://healthterminologies.gov.au/fhir/CodeSystem/australian-states-territories-1)|[Australian States and Territories](https://healthterminologies.gov.au/fhir/ValueSet/australian-states-territories-2)|NCTS|Australian Digital Health Agency|
|[Individual Healthcare Identifier Record Status](https://healthterminologies.gov.au/fhir/CodeSystem/ihi-record-status-1)|[Individual Healthcare Identifier Record Status](https://healthterminologies.gov.au/fhir/ValueSet/ihi-record-status-1)|NCTS|Australian Digital Health Agency|
|[Individual Healthcare Identifier Status](https://healthterminologies.gov.au/fhir/CodeSystem/ihi-status-1)|[Individual Healthcare Identifier Status](https://healthterminologies.gov.au/fhir/ValueSet/ihi-status-1)|NCTS|Australian Digital Health Agency|
|[Condition Category Codes](https://hl7.org/fhir/R4/codesystem-condition-category.html)|[Condition Category Codes](https://hl7.org/fhir/R4/valueset-condition-category.html)|FHIR|Health Level Seven International|
|[Condition Clinical Status Codes](https://hl7.org/fhir/R4/codesystem-condition-clinical.html)|[Condition Clinical Status Codes](https://hl7.org/fhir/R4/valueset-condition-clinical.html)|FHIR|Health Level Seven International|
|[ConditionVerificationStatus](https://hl7.org/fhir/R4/codesystem-condition-ver-status.html)|[ConditionVerificationStatus](https://hl7.org/fhir/R4/valueset-condition-ver-status.html)|FHIR|Health Level Seven International|
|[ContactPointSystem](https://hl7.org/fhir/R4/codesystem-contact-point-system.html)|[ContactPointSystem](https://hl7.org/fhir/R4/valueset-contact-point-system.html)|FHIR|Health Level Seven International|
|[ContactPointUse](https://hl7.org/fhir/R4/codesystem-contact-point-use.html)|[ContactPointUse](https://hl7.org/fhir/R4/valueset-contact-point-use.html)|FHIR|Health Level Seven International|
|[DataAbsentReason](http://terminology.hl7.org/CodeSystem/data-absent-reason)|[Australian Pronouns](https://healthterminologies.gov.au/fhir/ValueSet/australian-pronouns-1), [Gender Identity Response](https://healthterminologies.gov.au/fhir/ValueSet/gender-identity-response-1), [DataAbsentReason](https://hl7.org/fhir/R4/valueset-data-absent-reason.html)|HL7 Terminology (THO)|Health Level Seven International|
|[diagnosticServiceSectionId](http://terminology.hl7.org/CodeSystem/v2-0074)|[Pathology Diagnostic Service Category](https://healthterminologies.gov.au/fhir/ValueSet/pathology-diagnostic-service-category-1)|FHIR|Health Level Seven International|
|[EncounterStatus](https://hl7.org/fhir/R4/codesystem-encounter-status.html)|[EncounterStatus](https://hl7.org/fhir/R4/valueset-encounter-status.html)|FHIR|Health Level Seven International|
|[EventStatus](https://hl7.org/fhir/R4/codesystem-event-status.html)|[EventStatus](https://hl7.org/fhir/R4/valueset-event-status.html), [Immunization Status Codes](https://hl7.org/fhir/R4/valueset-immunization-status.html)|FHIR|Health Level Seven International|
|[IdentifierType AU](https://build.fhir.org/ig/hl7au/au-fhir-base//CodeSystem-au-v2-0203.html)|[DVA Entitlement](https://build.fhir.org/ig/hl7au/au-fhir-base/ValueSet-dva-entitlement.html), [hl7VS-identifierType - AU Extended](https://build.fhir.org/ig/hl7au/au-fhir-base/ValueSet-au-v2-0203-extended.html)|AU Base|HL7 Australia|
|[identifierType]( http://terminology.hl7.org/CodeSystem/v2-0203)|[hl7VS-identifierType - AU Extended](https://build.fhir.org/ig/hl7au/au-fhir-base/ValueSet-au-v2-0203-extended.html)|HL7 Terminology (THO)|Health Level Seven International|
|[IdentifierUse](https://hl7.org/fhir/R4/codesystem-identifier-use.html)|[IdentifierUse](https://hl7.org/fhir/R4/valueset-identifier-use.html)|FHIR|Health Level Seven International|
|[List Empty Reasons](https://hl7.org/fhir/R4/codesystem-list-empty-reason.html)|[List Empty Reasons](https://hl7.org/fhir/R4/valueset-list-empty-reason.html)|FHIR|Health Level Seven International|
|[Location Type]( http://terminology.hl7.org/CodeSystem/location-physical-type)|[Location Type (Physical) - AU Extended](https://build.fhir.org/ig/hl7au/au-fhir-base/ValueSet-au-location-physical-type-extended.html)|HL7 Terminology (THO)|Health Level Seven International|
|[Location Type (Physical) AU](https://build.fhir.org/ig/hl7au/au-fhir-base/CodeSystem-au-location-physical-type.html)|[Location Type (Physical) - AU Extended](https://build.fhir.org/ig/hl7au/au-fhir-base/ValueSet-au-location-physical-type-extended.html)|AU Base|HL7 Australia|
|[Location Type AU](https://build.fhir.org/ig/hl7au/au-fhir-base/CodeSystem-au-location-type.html)|[ServiceDeliveryLocationRoleType - AU Extended](https://build.fhir.org/ig/hl7au/au-fhir-base/ValueSet-au-v3-ServiceDeliveryLocationRoleType-extended.html)|AU Base|HL7 Australia|
|[LOINC](https://www.healthterminologies.gov.au/access-clinical-terminology/access-fhir-terminology-resources/code-systems/?ui:filter=loinc)|[Australian Pronouns](https://healthterminologies.gov.au/fhir/ValueSet/australian-pronouns-1), [RCPA SPIA Pathology Reporting](https://healthterminologies.gov.au/fhir/ValueSet/spia-pathology-reporting-1)|NCTS, HL7 Terminology (THO)|Regenstrief Institute, Inc|
|[Medication request intent](https://hl7.org/fhir/R4/codesystem-medicationrequest-intent.html)|[Medication request intent](https://hl7.org/fhir/R4/valueset-medicationrequest-intent.html)|FHIR|Health Level Seven International|
|[Medication status codes](https://hl7.org/fhir/R4/codesystem-medication-statement-status.html)|[Medication status codes](https://hl7.org/fhir/R4/valueset-medication-statement-status.html)|FHIR|Health Level Seven International|
|[Medicationrequest status](https://hl7.org/fhir/R4/codesystem-medicationrequest-status.html)|[Medicationrequest status](https://hl7.org/fhir/R4/valueset-medicationrequest-status.html)|FHIR|Health Level Seven International|
|[NameUse](https://hl7.org/fhir/R4/codesystem-name-use.html)|[NameUse](https://hl7.org/fhir/R4/valueset-name-use.html)|FHIR|Health Level Seven International|
|[Observation Category Codes](https://hl7.org/fhir/R4/codesystem-observation-category.html)|[Observation Category Codes](https://hl7.org/fhir/R4/valueset-observation-category.html)|FHIR|Health Level Seven International|
|[Observation Reference Range Meaning Codes](https://hl7.org/fhir/R4/codesystem-referencerange-meaning.html)|[Observation Reference Range Meaning Codes](https://hl7.org/fhir/R4/valueset-referencerange-meaning.html)|FHIR|Health Level Seven International|
|[ObservationStatus](https://hl7.org/fhir/R4/codesystem-observation-status.html)|[ObservationStatus](http://hl7.org/fhir/R4/valueset-observation-status.html), [Results Status Codes - IPS ](https://build.fhir.org/ig/HL7/fhir-ips/ValueSet-results-status-uv-ips.html)|FHIR|Health Level Seven International|
|[Participant type](https://hl7.org/fhir/R4/codesystem-encounter-participant-type.html)|[Participant type](https://hl7.org/fhir/R4/valueset-encounter-participant-type.html)|FHIR|Health Level Seven International|
|[PBS Item Codes](https://build.fhir.org/ig/hl7au/au-fhir-base/CodeSystem-pbs-item-external.html)|[PBS Item Codes](https://build.fhir.org/ig/hl7au/au-fhir-base/ValueSet-pbs-item.html)|AU Base|Department of Health and Aged Care, Commonwealth of Australia|
|[RoleCode](http://terminology.hl7.org/CodeSystem/v3-RoleCode)|[ServiceDeliveryLocationRoleType - AU Extended](https://build.fhir.org/ig/hl7au/au-fhir-base/ValueSet-au-v3-ServiceDeliveryLocationRoleType-extended.html), [Related Person Relationship Type](https://healthterminologies.gov.au/fhir/ValueSet/related-person-relationship-type-1)|HL7 Terminology (THO)|Health Level Seven International|
|[SNOMED CT (Australian extension)](https://www.healthterminologies.gov.au/access-clinical-terminology/access-fhir-terminology-resources/code-systems/?ui:filter=snomed)|[AMT Medicinal Product and Substances](https://build.fhir.org/ig/hl7au/au-fhir-base/ValueSet-amt-mp-codes.html), [Australian Medication](https://healthterminologies.gov.au/fhir/ValueSet/australian-medication-1), [Australian Medicines Terminology (AMT) Vaccine](https://healthterminologies.gov.au/fhir/ValueSet/amt-vaccine-1), [Clinical Condition](https://healthterminologies.gov.au/fhir/ValueSet/clinical-condition-1), [Clinical Finding](https://healthterminologies.gov.au/fhir/ValueSet/clinical-finding-1), [Clinical Specialty](https://healthterminologies.gov.au/fhir/ValueSet/clinical-specialty-1), [Condition/Diagnosis Severity](https://hl7.org/fhir/R4/valueset-condition-severity.html), [Reason for Encounter](https://healthterminologies.gov.au/fhir/ValueSet/reason-for-encounter-1), [Gender Identity Response](https://healthterminologies.gov.au/fhir/ValueSet/gender-identity-response-1), [Healthcare Organisation Role Type](https://healthterminologies.gov.au/fhir/ValueSet/healthcare-organisation-role-type-1), [Indicator of Hypersensitivity or Intolerance to Substance](https://healthterminologies.gov.au/fhir/ValueSet/indicator-hypersensitivity-intolerance-to-substance-2), [Medication Form](https://healthterminologies.gov.au/fhir/ValueSet/medication-form-1), [Medication Reason Taken](https://healthterminologies.gov.au/fhir/ValueSet/medication-reason-taken-1), [Practitioner Role](https://healthterminologies.gov.au/fhir/ValueSet/practitioner-role-1), [Procedure](https://healthterminologies.gov.au/fhir/ValueSet/procedure-1), [Reason for Request](https://healthterminologies.gov.au/fhir/ValueSet/reason-for-request-1), [Related Person Relationship Type](https://healthterminologies.gov.au/fhir/ValueSet/related-person-relationship-type-1), [Route of Administration](https://healthterminologies.gov.au/fhir/ValueSet/route-of-administration-1), [Service Type](https://healthterminologies.gov.au/fhir/ValueSet/service-type-1), [SNOMED CT Additional Dosage Instructions](https://hl7.org/fhir/R4/valueset-additional-instruction-codes.html), [SNOMED CT Administration Method Codes](https://hl7.org/fhir/R4/valueset-administration-method-codes.html)|NCTS|Australian Digital Health Agency|
|[Tags for the Identification of Languages](https://terminology.hl7.org/CodeSystem-v3-ietf3066.html)|[Common Languages in Australia](https://healthterminologies.gov.au/fhir/ValueSet/common-languages-australia-2)|HL7 Terminology (THO)|Internet Engineering Task Force|
|[v2 Contact Role](https://hl7.org/fhir/R4/v2/0131/index.html)|[Related Person Relationship Type](https://healthterminologies.gov.au/fhir/ValueSet/related-person-relationship-type-1)|FHIR|Health Level Seven International|
|[v3 Code System ObservationInterpretation](https://hl7.org/fhir/R4/v3/ObservationInterpretation/cs.html)|[Observation Interpretation Codes](https://hl7.org/fhir/R4/valueset-observation-interpretation.html)|FHIR|Health Level Seven International|
|[v3 Code System ParticipationType](https://hl7.org/fhir/R4/v3/ParticipationType/cs.html)|[Participant type](https://hl7.org/fhir/R4/valueset-encounter-participant-type.html)|FHIR|Health Level Seven International|
{:.grid}
