# Code2Spec - Artifacts Extracts with AI

In this repository you will find the artifacts extracts with AI for the Code2Spec project.
The artifacts are extracted from the source code of the project using the Code2Spec tool.

## About the Artifacts

1. **Folders:** each folder represents a git repository
2. **Files:** inside of the repository folders you will find:
    - An HTML file. Download it and open it in your browser to see the code graph generated.
    - A Mardown file showing the extracted components and features of the git repository

# Sample Projects

We are using 3 sample projects:

- **CBDash** project: a Django project.
  - URL: "<private>"
  - CodeGraph: [CBDash Code Graph](cbdash/cbdash_codegraph.html)
  - Documentation: [Components and Features](cbdash/cbdash_components-and-features.md)
- **AWS Mainframe Modernization CardDemo** project: a COBOL project.
  - URL: https://github.com/aws-samples/aws-mainframe-modernization-carddemo
  - CodeGraph: [AWS Mainframe Modernization CardDemo Code Graph](aws-mainframe-modernization-carddemo/aws-mainframe_cobol_codegraph.html)
  - Documentation: [Components and Features](aws-mainframe-modernization-carddemo/aws-mainframe_cobol_-components-and-features.md)
- **Congressy** project: a Django project for Event Management System.
  - URL: https://github.com/hugoseabra/congressy
  - CodeGraph: [Congressy Code Graph](congressy/congressy_codegraph.html)
  - Documentation: [Components and Features](congressy/congressy_components-and-features.md)

# What You Will Find

## The Code Graph

This is an important artifact to find the components and features of the project.
We use the code graph to identify the clusters of components and extract the key features
from the discovered clusters, also known as the [Architecture Building Blocks](https://pubs.opengroup.org/architecture/togaf8-doc/arch/chap32.html).

## The Components and Features

The key features are grouped by Components, which are the identified Building Blocks with a title and
a description.

**Building Blocks** are described under a product perspective, which means that they are the main components
of the system that are visible to the user.