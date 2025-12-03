# Doctors Module
The **Doctors Module**, formerly known as the Practitioners Module, is the specialized clinical workspace where medical officers conduct consultations, make diagnoses, and determine treatment plans for patients. This module grants doctors secure, real-time access to the complete Electronic Patient Record (EPR) to inform their decisions. The interface is primarily structured around two critical workflow sections: **Encounters**, which provides a streamlined list of patients currently admitted or transferred to the doctor's care for immediate review and consultation; and **Appointments**, which manages the doctor's scheduled outpatient visits, enabling seamless handling of the queue, recording of clinical notes, ordering of diagnostics (labs and radiology), and issuance of electronic prescriptions.

## Doctors Activities
* **Encounter**
* **Appointments**

* ## ENCOUNTERS
The Encounters screen serves as the doctor's active patient queue, providing an immediate overview of all patients currently assigned for consultation. Each patient is displayed on a card detailing essential visit information, including their unique Patient ID, the current Status (In Progress), the type of service requested (e.g., Gp Consult), whether the visit is In-patient or Out-patient, the time the encounter Started at, and the patient's Payment Method. This view is the starting point for clinical action; by clicking **"Medical Record,"** the doctor gains full access to the patient's history for review, and by clicking **"Action,"** the doctor can initiate critical workflow steps such as starting the consultation, ordering diagnostic tests (labs/radiology), generating e-prescriptions, and ultimately closing the patient encounter after the diagnosis and treatment plan are finalized.
![encounter](/Docs-images/Encounter.png)

* ### Medical Record 
A **Medical Record** (often digitalized as an Electronic Medical Record or EMR) serves as the primary and most comprehensive legal document detailing a patient's health and care history within a specific healthcare organization. It is a critical tool for ensuring safe, coordinated, and continuous care by providing all authorized clinicians with quick, real-time access to the patient's complete clinical picture.

The record systematically stores essential patient data, which typically includes:

* **Medical History** (past and present conditions, surgeries, and family history).

* **Diagnoses** and **Treatment Plans.**

* **Medications** (current prescriptions, past usage, and known **Allergies**).

* **Lab Results** and **Diagnostic Reports** (imaging, pathology, etc.).

* **Progress Notes** and **Observations** documented by healthcare providers during each visit.

* **Immunization Status.**

In the Yarysa EMR, the **"Medical Record"** option opens this comprehensive, longitudinal view of the patient's data, allowing the doctor to review the complete history needed to make well-informed decisions regarding the current consultation and future care.


* ### Action
The **Action** tab is a critical functional element of the patient interface, designed to consolidate and provide quick access to a range of related tasks and processes. Rather than opening a new, permanent view, the Action tab displays its functionality through a drop-down menu. This menu is the primary access point for initiating, managing, and tracking specific patient-related activities that go beyond simple data viewing. By centralizing these tasks—such as requesting services, ordering medications, or viewing financial summaries—it streamlines the doctor's workflow and allows immediate access to the necessary tools for direct patient management.

#### Doctor's specific

This option likely leads to specialized tools and views designed for the attending physician. It typically includes features that allow the doctor to directly input clinical notes, make diagnoses, order specific tests or procedures that aren't general service requests, and perform tasks related to charting or reviewing the patient's history from a professional medical standpoint. Essentially, it serves as the central workstation for the doctor's direct clinical interaction and decision-making for the patient.

#### Service requests
![](/Docs-images/service%20request.png)
The **Service requests** option opens a dedicated module, typically named **"Encounter Service Requests,"** which is used to **manage and track all requested services** directly related to the patient's current medical episode or hospital stay. This feature is crucial for coordinating **diagnostic procedures** (such as laboratory tests), therapeutic services, or imaging orders. The interface provides a centralized view where staff can monitor the lifecycle of these requests, showing key management details for each ordered service, including its **Category** (e.g., Lab, Imaging), **Priority** (e.g., Routine, Urgent), **Status** (e.g., Active, Completed), and relevant dates and personnel. This ensures efficient execution and follow-up on all clinical services ordered for the patient.


#### Medication requests

**Medication requests** is the dedicated module for managing the patient's pharmacology. Doctors use this to write **new prescriptions** (e.g., e-prescribing), manage the **administration schedule** of existing medications, request **refills**, or discontinue specific drugs. This centralized feature helps track dosage, timing, and potential interactions, ensuring a clear and safe process for ordering and dispensing medicine to the patient.

#### Patient Bill
![](/Docs-images/bill%20patient.png)
Selecting **Patient Bill** directs the user to a dedicated financial tracking module, typically labeled **"Charge Items."** This feature establishes the patient's comprehensive **financial ledger** for the entire medical encounter. It is structured as an itemized table that lists every billable service provided. The interface provides critical financial accountability by displaying:

* The **Service** provided (e.g., consultation, procedure, medication).

* Details of the **Payment** arrangement, including the primary payer (e.g., Corporate, Private) and the responsible entity.

* The **Unit Price**, **Quantity**, and **Total** charge, allowing for transparent cost calculation.

* The **Status** of the charge (e.g., planned, billed, paid), indicating where it is in the billing cycle.

* The **Date** the service was incurred.

This module gives administrative and billing staff the ability to review, reconcile, and manage all financial transactions, including the ability to edit or delete individual charge items as necessary.

#### Patient Invoices

The **Patient Invoices** function allows for the generation and viewing of formal, itemized requests for payment. These documents are usually necessary for submission to the corporate insurer ("Senes Pharmacy" in the displayed card) or a third-party payer to reconcile the charges outlined in the Patient Bill. In a corporate or insurance-based setting, this is the formal document used to claim reimbursement or initiate the payment process from the responsible entity.