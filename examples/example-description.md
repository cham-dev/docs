Example of 2 documents (1st has 3 versions, 2nd has 2).

```bash
export-batch-1
|
+-- docs
    |
    +-- 5e9b81f4-dad1-48d2-b4c8-d28c6a9e17e3 - actual "A Scandal in Bohemia Draft.txt" file of document 56698, version 1
    +-- 5e9b81f4-dad1-48d2-b4c8-d28c6a9e17e3.json - metadata of document 56698, version 1
    +-- 14cf08a5-2811-4503-9349-f6e4af132814 - actual "His Last Bow.txt" file of document 56698, version 2
    +-- 14cf08a5-2811-4503-9349-f6e4af132814.json - metadata of document 56698, version 2
    +-- 16f21eaf-2f03-4710-921a-c08f25801ee0 - actual "The Final Problem.txt" file of document 56698, version 3
    +-- 16f21eaf-2f03-4710-921a-c08f25801ee0.json - metadata of document 56698, version 3
    +-- 040b5b05-f9ba-417f-9470-f7e3a02d6cc0 - actual "The Red-headed League.txt" file of document 12003, version 1
    +-- 040b5b05-f9ba-417f-9470-f7e3a02d6cc0.json - metadata of document 12003, version 1
    +-- 349b635d-f0b0-4805-8a4a-880ed28f6be9 - actual "The Man with the Twisted Lip Final.txt" file of document 12003, version 2
    +-- 349b635d-f0b0-4805-8a4a-880ed28f6be9.json - metadata of document 12003, version 2

+-- metadata.json
   
```

metadata for document 56698, version 1:

```
{
  "DocumentId": 56698,
  "ClientCode": "ABC123",
  "AuthorFirstName": "Sherlock",
  "AuthorSurname": "Holmes",
  "AuthorUniqueId": "SH",
  "DateCreated": "2017-05-16T17:25:09.83",
  "AssignmentCode": "ABC123/ADM",
  "Version": 1,
  "Name": "A Scandal in Bohemia",
  "Guid": "5e9b81f4-dad1-48d2-b4c8-d28c6a9e17e3",
  "CompanyName": "Conan Ltd",
  "DepartmentName": "WatsonDept",
  "OfficeName": "BakerStreetOffice",
  "Comments": "First draft",
  "Description": "The Adventures of Sherlock Holmes",
  "ContactLastName": "Lestrade",
  "DocumentDate": "2017-05-16T17:25:09.83",
  "VersionFileName": "A Scandal in Bohemia Draft",
  "VersionFileExtension": ".txt",
  "DocumentLibraryName": "Client",
  "DocumentSourceDescription": "Upload",
  "DocumentTypeName": "Documents & Reports",
  "AssignmentName": "Lestrade/Administration",
  "AssignmentNameRight": "Administration",
  "AssignmentCodeRight": "ADM",
  "AssignmentTypeDescription": "Administration",
  "AssignmentCentreCode": "-unspec-",
  "AssignmentNominalCode": "001",
  "ScheduleName": "Payroll",
  "ScheduleStartDate": "2015-01-02T15:01:43.98",
  "ScheduleEndDate": null
}
```
metadata for document 56698, version 2:

```
{
  "DocumentId": 56698,
  "ClientCode": "ABC123",
  "AuthorFirstName": "John",
  "AuthorSurname": "Watson",
  "AuthorUniqueId": "JW",
  "DateCreated": "2017-06-16T16:26:44.86",
  "AssignmentCode": "ABC123/ADM",
  "Version": 2,
  "Name": "His Last Bow",
  "Guid": "14cf08a5-2811-4503-9349-f6e4af132814",
  "CompanyName": "Conan Ltd",
  "DepartmentName": "WatsonDept",
  "OfficeName": "BakerStreetOffice",
  "Comments": "Manual upload from",
  "Description": "The Adventures of Sherlock Holmes",
  "ContactLastName": "Lestrade",
  "DocumentDate": "2017-05-16T17:25:09.83",
  "VersionFileName": "His Last Bow",
  "VersionFileExtension": ".txt",
  "DocumentLibraryName": "Client",
  "DocumentSourceDescription": "Upload",
  "DocumentTypeName": "Documents & Reports",
  "AssignmentName": "Lestrade/Administration",
  "AssignmentNameRight": "Administration",
  "AssignmentCodeRight": "ADM",
  "AssignmentTypeDescription": "Administration",
  "AssignmentCentreCode": "-unspec-",
  "AssignmentNominalCode": "001",
  "ScheduleName": "Payroll",
  "ScheduleStartDate": "2015-01-02T15:01:43.98",
  "ScheduleEndDate": null
}
```
metadata for document 56698, version 3:

```
{
  "DocumentId": 56698,
  "ClientCode": "ABC123",
  "AuthorFirstName": "Sherlock",
  "AuthorSurname": "Holmes",
  "AuthorUniqueId": "SH",
  "DateCreated": "2018-07-05T13:53:09.8",
  "AssignmentCode": "ABC123/ADM",
  "Version": 3,
  "Name": "The Final Problem",
  "Guid": "16f21eaf-2f03-4710-921a-c08f25801ee0",
  "CompanyName": "Conan Ltd",
  "DepartmentName": "WatsonDept",
  "OfficeName": "BakerStreetOffice",
  "Comments": "Constable's story",
  "Description": "The Adventures of Sherlock Holmes",
  "ContactLastName": "Lestrade",
  "DocumentDate": "2017-05-16T17:25:09.83",
  "VersionFileName": "The Final Problem",
  "VersionFileExtension": ".txt",
  "DocumentLibraryName": "Client",
  "DocumentSourceDescription": "Upload",
  "DocumentTypeName": "Correspondence In",
  "AssignmentName": "Lestrade/Administration",
  "AssignmentNameRight": "Administration",
  "AssignmentCodeRight": "ADM",
  "AssignmentTypeDescription": "Administration",
  "AssignmentCentreCode": "-unspec-",
  "AssignmentNominalCode": "001",
  "ScheduleName": "Payroll",
  "ScheduleStartDate": "2015-01-02T15:01:43.98",
  "ScheduleEndDate": null
}
```
metadata for document 12003, version 1:

```
{
  "DocumentId": 12003,
  "ClientCode": "R777",
  "AuthorFirstName": "John",
  "AuthorSurname": "Watson",
  "AuthorUniqueId": "JD",
  "DateCreated": "2015-04-16T17:50:57.113",
  "AssignmentCode": "R777/ADM",
  "Version": 1,
  "Name": "The Red-headed League",
  "Guid": "040b5b05-f9ba-417f-9470-f7e3a02d6cc0",
  "CompanyName": "Conan Ltd",
  "DepartmentName": "WatsonDept",
  "OfficeName": "BakerStreetOffice",
  "Comments": "the story of",
  "Description": "The Adventures of Sherlock Holmes",
  "ContactLastName": "Lestrade",
  "DocumentDate": "2015-04-16T17:50:57.113",
  "VersionFileName": "The Red-headed League",
  "VersionFileExtension": ".txt",
  "DocumentLibraryName": "Client",
  "DocumentSourceDescription": "Upload",
  "DocumentTypeName": "Correspondence In",
  "AssignmentName": "Lestrade/Administration",
  "AssignmentNameRight": "Administration",
  "AssignmentCodeRight": "ADM",
  "AssignmentTypeDescription": "Administration",
  "AssignmentCentreCode": "-unspec-",
  "AssignmentNominalCode": "711",
  "ScheduleName": "Payroll",
  "ScheduleStartDate": "2015-01-02T15:01:43.98",
  "ScheduleEndDate": null
}
```
metadata for document 12003, version 2:

```
{
  "DocumentId": 12003,
  "ClientCode": "R777",
  "AuthorFirstName": "Martha",
  "AuthorSurname": "Hudson",
  "AuthorUniqueId": "MH",
  "DateCreated": "2018-07-05T13:52:32.063",
  "AssignmentCode": "R777/ADM",
  "Version": 2,
  "Name": "The Man with the Twisted Lip",
  "Guid": "349b635d-f0b0-4805-8a4a-880ed28f6be9",
  "CompanyName": "Conan Ltd",
  "DepartmentName": "WatsonDept",
  "OfficeName": "BakerStreetOffice",
  "Comments": "landlady's story",
  "Description": "The Adventures of Sherlock Holmes",
  "ContactLastName": "Lestrade",
  "DocumentDate": "2015-04-16T17:50:57.113",
  "VersionFileName": "The Man with the Twisted Lip Final",
  "VersionFileExtension": ".txt",
  "DocumentLibraryName": "Client",
  "DocumentSourceDescription": "Upload",
  "DocumentTypeName": "Correspondence In",
  "AssignmentName": "Lestrade/Administration",
  "AssignmentNameRight": "Administration",
  "AssignmentCodeRight": "ADM",
  "AssignmentTypeDescription": "Administration",
  "AssignmentCentreCode": "-unspec-",
  "AssignmentNominalCode": "711",
  "ScheduleName": "Payroll",
  "ScheduleStartDate": "2015-01-02T15:01:43.98",
  "ScheduleEndDate": null
}
```