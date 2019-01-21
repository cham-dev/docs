# #{Build.BuildNumber}#

## Default Csv Format ##

*Metadata.csv* contains the original fields from metadata.json file in csv format.
 
## Custom Csv Format ##

File *metadata-custom.csv* contains following fields:

### Fields ###

* **Guid** - guid, unique identifier for a particular version of the document.
* **Name** - the file name of current version, 200 chars.
* **DocumentExtension** - string, file extension including preceding ".".
* **DocumentId** - integer, unique identifier for a document (all versions of this document would have the same document id), link to source system.
* **Version** - integer, starting at 1, sequential.
* **Client** - string, unique identifier for a client, 50 chars.
* **DocumentDate** - date for this document, see *Date Format* section.
* **Comments** - string, 100 chars, optional.
* **DocumentTypeName** - string, 100 chars.
* **AssignmentName** - string, 255 chars, optional.
* **AssignmentCode** - string, 61 chars, optional.
* **AssignmentNameRight** - string, 50 chars, optional.
* **AssignmentCodeRight** - string, 10 chars, optional.
* **AssignmentTypeDescription** - string, 50 chars, optional.
* **AssignmentCentreCode** - string, 10 chars, optional.
* **AssignmentNominalCode** - string, 10 chars, optional.
* **ScheduleName** - string, filing/category within the assignment, 50 chars, optional.
* **ScheduleStartDate** - date, optional, see *Date Format* section.
* **ScheduleEndDate** - date, optional, see *Date Format* section.

### Rules ###

* **Name** is derived from original VersionFileName and Name fields. 
* **DocumentDate** is derived from original DateCreated field.

### Date Format ###

Day/Month/Year Hour:Minute   
**dd/MM/yyyy HH:mm**

* **dd** - 01 to 31 date of the month.
* **MM** - 01 to 12 month number with leading zero.
* **yyyy** - four digits year.
* **HH** - 00 to 23 24-hour clock hour with leading zero.
* **mm** - 00 to 59 minutes with leading zero.

## Archived Metadata Files ##

Each individual metadata files that contain properties of single document are moved from docs directory into "archived" sub-directory.

