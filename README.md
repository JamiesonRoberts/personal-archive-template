# Digital Archive Template

The purpose of this is to provide a template for whomever needs a structured digital archive of projects. The idea for 
this came about when I realized that I had quite a few historical projects (paid and not) sitting around on CD's from 
before I started using git to house my projects and data. This could be used for past freelance projects, legacy 
code and ideas that have been mothballed, organizing school projects etc. 

**Note:** Please submit issues with details if you would like to see a change in structure or additional project types with 
specific folder structures.

## Data Structure

The archive has the following data structure for small sized files. Any files above 25mb will be handled by large file 
format storage. If large files are present, a README file will exist in the root of the project documenting what files 
are stored externally.

```
.
├── {year}
│   ├── {entity-name} [^1]
│   │   └── {project-name}
│   │       └── **/* 
│   └── README.md # [^2]
├── project-types.md
└── README.md 
```

## Application Requirements

The projects in this contain some proprietary file formats that can only used by specific applications. The following 
is a non-exhaustive list of applications required to actually run all projects

- Name the applications used to open files in this archive

## To Do:

- [ ] Historical Invoice Log for paid projects
- [ ] Large File Format Project Storage

---

[^1] The entity name level is optional and depends on whether you need to classify your projects based on their 
association with a specific entity.   
[^2] The readme in the year folder contains details about the entities and/or projects. You may include the type of 
project if it is relevant
