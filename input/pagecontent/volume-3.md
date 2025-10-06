Most ofen these types of documents are exchanged using PDF, health has a documentation standard called [Clinical Document Architecture (CDA)](https://en.wikipedia.org/wiki/Clinical_Document_Architecture) was a HL7 XML based standard. The standards listed below all use [HL7 FHIR Documents](https://hl7.org/fhir/R4/documents.html). 
Clinical documents can be used as a html document with a simple transformation and can also be used to supply structured clinical data.

These documents, like PDF are generally used used with document sharing systems such as IHE XDS, MHD and potentially NHS England National Record Locator.
(Note: transfer of care used FHIR Mesaging to exchange these documents)

# Patient Summary

- [Internation Patient Summary](https://international-patient-summary.net/)
  - [International Patient Summary Implementation Guide](https://hl7.org/fhir/uv/ips/)
  
# Clinical Note

- NHS England Transfer of Care (FHIR STU3)
  - [Outpatient Letter](https://developer.nhs.uk/apis/itk3tocoutpatientletter-2-9-0/build_resource_referencing.html)

# Discharge Report

- [HL7 Europe Hospital Discharge Report](https://hl7.eu/fhir/hdr/)
- NHS England Transfer of Care (FHIR STU3)
  - [Inpatient (acute) discharge](https://developer.nhs.uk/apis/itk3tocedischarge-2-9-0/build_resource_referencing.html)
  - [Emergency care discharge](https://developer.nhs.uk/apis/itk3emergencycareedischarge-2-9-0/build_resource_referencing.html)
  - [Mental health discharge](https://developer.nhs.uk/apis/itk3tocmentalhealthedischarge-2-9-0/build_resource_referencing.html)

# Laboratory Report

- [HL7 Europe Laboratory Report](https://hl7.eu/fhir/laboratory/index.html)

# Radiology Report

- [HL7 Europe Imaging Study Report](https://build.fhir.org/ig/hl7-eu/imaging/)
