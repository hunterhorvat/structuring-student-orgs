# **Understand the file-organization system**

[Return to the documentation home](/README.md) | [Continue to the procedure](procedure.md)

## **Why the system is necessary** 

A file name functions as a compact technical description. It should give collaborators enough information to recognize a file without opening it. A folder system provides a second level of description by grouping files according to their role in day-to-day functions of the student organization. 

*The Cool Student Org* Executive Board addresses three recurring problems: 

| Problem | Design Response |
| ------- | --------------- |
| Members cannot identify a file's contents | Every name includes a controlled document type code and short content description |
| Files appear in an unpredictable order | Every name begins with the date |
| Files appear cluttered and difficult to search through | Each file is sorted into a labeled folder and subfolder as needed | 

## **Folder structure**

The system separates files based on executive board functions. 

```text
Cool-Student-Org_2026-27
├── 01_events
├── 02_meetings
├── 03_financials
├── 04_marketing
├── 05_membership
└── 06_archive
```

The numeric prefixes maintain the same order across computers and cloud platforms. 

| Folder | Store here | Do not store here |
| ------ | -----------| ------------------|
| `01_events` | event plans, vendor lists, event task spreadsheets | budget planning | 
| `02_meetings` | attendance records, meeting minutes | transition documents | 
| `03_financials` | dues tracking spreadsheets, budget planning, expense reports | meeting attendance |
| `04_marketing` | logos, branding guidelines | event plans |
| `05_membership` | bylaws, handbooks, transition documents | branding guidelines |
| `06_archive` | retained material from previous academic years | active working files |

## **File-name pattern** 

Use this sequence: 

```text
YYYY-YY_TYPE-IDENTIFIER.ext 
```

Each segment has one purpose. 

| Segment | Meaning | Example |
| ------- | ------- | ------- |
| `YYYY-YY` | academic year | `2026-27` | 
| `TYPE` | document type code | `FINS` |
| `IDENTIFIER` | short content description | `dues-tracking` |

### Controlled document-type codes
- `EVTS`: events 
- `MTGS`: meetings
- `FINS`: financials
- `MKTG`: marketing
- `MEMB`: membership

> Note: Archived files do not need to be renamed individually and thus do not need a controlled document-type code. 
