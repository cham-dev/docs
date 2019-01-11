# Documents #

## Concepts ##

All documents are versioned. Each version of the file is preserved in the it’s original form. Each version of the document has a set of metadata properties. Document has at least one version and would be assigned either against client or contact, optionally marked against combination of assignment code and assignment job and would have author and date created. Additional metadata properties can be included on request.

## Document Properties ##

* **Guid** - guid, unique identifier for a particular version of the document.
* **DocumentId** - integer, unique identifier for a document (all versions of this document would have the same document id), link to source system.
* **Version** - integer, starting at 1, sequential.
* **Name** - string, the name of the document, 200 chars.
* **ClientCode** - string, unique identifier for a client, 50 chars.
* **ContactLastName** - string, optional last name of contact, 60 chars, optional.
* **AuthorFirstName** - string, 50 chars, optional.
* **AuthorSurname** - string, 60 chars, optional.
* **AuthorUniqueId** - string, unique username of the author in source system, 80 chars, optional.
* **DateCreated** - date created for this document.
* **CompanyName** - string, 100 chars, optional.
* **DepartmentName** - string, 50 chars, optional.
* **OfficeName** - string, 50 chars, optional.
* **Description** - string, 200 chars, optional.
* **Comments** - string, 100 chars, optional.
* **DocumentDate** - date, optional.
* **VersionFileName** - the file name of current version, 200 chars, optional.
* **VersionFileExtension** - string, file extension including preceding ".", derived from VersionFileName.
* **DocumentLibraryName** - string, 100 chars.
* **DocumentSourceDescription** - string, 100 chars.
* **DocumentTypeName** - string, 100 chars.
* **AssignmentName** - string, 255 chars, optional.
* **AssignmentCode** - string, 61 chars, optional.
* **AssignmentNameRight** - string, 50 chars, optional.
* **AssignmentCodeRight** - string, 10 chars, optional.
* **AssignmentTypeDescription** - string, 50 chars, optional.
* **AssignmentCentreCode** - string, 10 chars, optional.
* **AssignmentNominalCode** - string, 10 chars, optional.
* **ScheduleName** - string, filing/category within the assignment, 50 chars, optional.
* **ScheduleStartDate** - date, optional.
* **ScheduleEndDate** - date, optional.