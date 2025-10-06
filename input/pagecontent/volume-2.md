
# Patient Administration (PAM)

See [IHE Patient Administration (PAM)](https://profiles.ihe.net/ITI/TF/Volume1/ch-14.html) for a detailed description of this topic.

## Patient Demographic Query (PDQ)

The England and Wales patient identifier is called NHS Number, Scotland uses CHI Number and Northern Ireland Health and Care Number (HCN). The format of all these identiers is described in [NHS Number](https://en.wikipedia.org/wiki/NHS_number

API's to use with these identifiers are described are:

- NHS England - [Personal Demographics Service - FHIR API](https://digital.nhs.uk/developer/api-catalogue/personal-demographics-service-fhir)

## Patient Identifier Cross-referencing (PIX)

Most secondary care systems will support [IHE PIX](https://profiles.ihe.net/ITI/TF/Volume1/ch-5.html) for cross-referencing patients within the NHS Trust, this will be known as HL7 Admission Discharge and Transfer (ADT). Many other sectors will also support HL7 ADT.

- NHS England [HL7 v2 ADT Message Specification](HL7/HSCIC-ITK-HL7-V2-Message-Specifications.pdf)
- NHS England [HL7 v2 ADT Reference Tables](HL7/HSCIC-ITK-HL7-V2-Reference-Tables.pdf)

## Patient Encounter Management (PEM)

- NHS England [HL7 v2 ADT Message Specification](HL7/HSCIC-ITK-HL7-V2-Message-Specifications.pdf)
- NHS England [HL7 v2 ADT Reference Tables](HL7/HSCIC-ITK-HL7-V2-Reference-Tables.pdf)


# Patient Care Coordination

Is a complex topic which is described in [IHE Patient Care Coordination (PCC)](https://www.ihe.net/resources/technical_frameworks/#pcc). In the UK the most common implementations are below:

## Query for Existing Data (QEDm)

This provides a way for a system to query for existing clinical data, this is often implemented as a RESTful API to a Electronic Health Record (EHR).
Many secondary care systems (especially from US suppliers, this may also be known as US Core) will support [IHE QEDm](https://profiles.ihe.net/ITI/TF/Volume1/ch-10.html) for querying for existing data. Some UK suppliers will support [CareConnectAPI](https://nhsconnect.github.io/CareConnectAPI/).

### Primary Care - IM1

- TODO

### Primary Care - GP Connect

NHS England [GP Connect (Patient Facing) Access Record - FHIR API](https://simplifier.net/guide/gp-connect-patient-facing-access-record)

## Cross Enterprise Document Sharing (XDS and MHD)

### Primary Care - Kettering XML

- [EDT Message Specification](kettering/EDT_Message_Specification_v3.0.7.pdf)
- [Kettering Format Message Specification](kettering/Kettering_Format_Messages_in_Vision.pdf)
- [Kettering Example](kettering/KetteringExample.xml)

# Diagnostic Testing

## Laboratory and Testing Workflow (LTW)

Most secondary care systems (EPR) and laboratory information systems (LIMS) will support [IHE LTW](https://profiles.ihe.net/ITI/TF/Volume1/ch-16.html) for reporting laboratory results, and this is most often implemented as HL7 v2 ORM, OML and ORU messages.

- Department of Health and Care Wales [HL7 v2 ORU](HL7/DHCW-HL7-v2-5-1-ORUR01-Specification.pdf)

### Primary Care - NHS Pathology

This specification details how results are communication between order comms (middleware) and primary care systems.

- [NHS England Pathology FHIR Implementation Guide](https://simplifier.net/guide/pathology-fhir-implementation-guide/home?version=0.2.0)

## Radiology (RAD)

The method of exchanging radiology orders and reports is described in [IHE RAD](https://profiles.ihe.net/ITI/TF/Volume1/ch-17.html) and is often implemented as HL7 ORM, OMG and ORU messages.

- Royal College of Radiologists [Understanding the technical options](https://www.rcr.ac.uk/media/wwtp2mif/rcr-publications_radiology-reporting-networks-understanding-the-technical-options_march-2022.pdf)
