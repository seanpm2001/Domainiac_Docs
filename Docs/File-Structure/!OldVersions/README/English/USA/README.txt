
***

# Domainiac Docs

## File structure

This document is a vital piece of documentation for Domainiac. It goes over the file structure used in the project. For the format that database entries are written in, see [`Format`](/Docs/Format/)

### The origin

All entries are located within `/Domainiac/` registrar entries are located within `/Domainiac/Domainia/` and database entries are located within `/Domainiac/Domainiac/DB/`

#### Registrar

There is no planned structure for the registrar at the moment.

#### Database

The database is sorted into a few subcategories:

- `ccTLD` (located here: `/Domainiac/Domainiac/DB/ccTLD/`)
- `eTLD` (located here: `/Domainiac/Domainiac/DB/eTLD/`)
- `gTLD` (located here: `/Domainiac/Domainiac/DB/gTLD/`)
- `sTLD` (located here: `/Domainiac/Domainiac/DB/sTLD/`)

##### ccTLD

This directory holds ccTLD information (about Country Code Top Level Domains) each country has its own folder. In the root of each folder, there are 3 files and sub-directories:

- `/!OldVersions/` - Holds information on old versions of the bottom file
- `/dot/` - A substitute for `.` (see [§ hidden files](#Hidden-files))
- `/README.md` - A README.md file that contains information and jump links to each ccTLD specific to this country.

Each domain has its own folder. For more information on setup, see [`Format`](/Docs/Format/README.md)

##### gTLD

This directory holds gTLD information (about General Top Level Domains) each general domain has its own folder. In the root of each folder, there are 3 files and sub-directories:

- `/!OldVersions/` - Holds information on old versions of the bottom file
- `/dot/` - A substitute for `.` (see [§ hidden files](#Hidden-files))
- `/README.md` - A README.md file that contains information and jump links to each gTLD specific to this entry.

Each domain has its own folder. For more information on setup, see [`Format`](/Docs/Format/README.md)

##### sTLD

This directory holds gTLD information (about Sponsored Top Level Domains) each sponsored domain has its own folder. In the root of each folder, there are 3 files and sub-directories:

- `/!OldVersions/` - Holds information on old versions of the bottom file
- `/dot/` - A substitute for `.` (see [§ hidden files](#Hidden-files))
- `/README.md` - A README.md file that contains information and jump links to each sTLD specific to this entry.

Each domain has its own folder. For more information on setup, see [`Format`](/Docs/Format/README.md)

##### eTLd

This directory holds eTLD information (about Email Top Level Domains) each Email domain has its own folder. In the root of each folder, there are 3 files and sub-directories:

- `/!OldVersions/` - Holds information on old versions of the bottom file
- `/dot/` - A substitute for `.` (see [§ hidden files](#Hidden-files))
- `/README.md` - A README.md file that contains information and jump links to each eTLD specific to this entry.

Each domain has its own folder. For more information on setup, see [`Format`](/Docs/Format/README.md)

### Hidden files

To prevent files from being hidden (and also to prevent a GitHub bug, where files can't be uploaded into a hidden folder) each domain is separated. For example, `/.in/` is actually `/dot/in/` the folder name is always in lowercase.

[Shell script for converting `/dot/domain/` to `/.domain/` (coming soon)](/Scripts/dotTLD/dotTLD.sh)

#### Domain hacks

Domain hacks are documented. For more information, see [`Format`](/Docs/Format/README.md)

#### Non-ASCII domains

Non-ASCII domains are sometimes present. These include domains in Cyrillic, Devanagari, Kanji, Greek, and more. They are most commonly found alongside ccTLDs

***

**File version:** `1 (2023, Monday, May 8th at 6:37 pm PST)`

***
