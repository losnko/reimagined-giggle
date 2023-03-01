---
title: "Pipelines & Procedures"
author: ""
lightgallery: true
date: "2022-01-05"
categories: 
resources:
- name: featured-image
  src: featured-image.png
- name: featured-image-preview
  src: featured-image-preview.png
categories: ["Technical Writing"] 
---
## 1 Solution


{{< admonition success "Unified Documentation" true >}} A maintainable, accessible set of documents developed using information architecture and structured authoring methodology:
1. **Identified** reusable information blocks
1. **Chunked** together similar content for review
1. **Clarified** differences and nuanced syntax with SMEs 
1. **Accessibility** assessment, addressing colour and contrast
{{< /admonition >}}

{{< style "border:1px solid black;" >}}{{< image src="IO-1.png" caption="" width="19%" height="19%" >}}
{{< image src="IO-2.png" caption="" width="19%" height="19%" >}}
{{< image src="IO-3.png" caption="" width="19%" height="19%" >}}
{{< image src="IO-4.png" caption="" width="19%" height="19%" >}}
{{< image src="IO-5.png" caption="" width="19%" height="19%" >}}
{{< /style >}}

{{< style "border:1px solid black;" >}}
{{< image src="ER-1.png" caption="" width="19%" height="19%" >}}
{{< image src="ER-2.png" caption="" width="19%" height="19%" >}}
{{< image src="ER-3.png" caption="" width="19%" height="19%" >}}
{{< image src="ER-4.png" caption="" width="19%" height="19%" >}}
{{< image src="ER-5.png" caption="" width="19%" height="19%" >}}
{{< /style >}}


## 2 Problem

### Planning Phase

{{< mermaid  >}}
graph TD;
    A[Research: Background] --> B(Research: Existing Materials)
    B --> C(Analysis: Compare Versions)
    C -.-> D(Analysis: Identify Differences)
    C -.-> E(Analysis: Chunk Reusable Content) <-.->D 
    B --> F[Analysis: Evaluate Accessibility]
    D --> G(Analysis: Clarify Changes with SME)-.-H
    F --> H{Prototype}
    H --> I[Report: Proposed Solution] 
{{< /mermaid >}}

### Background 

The {{< link href="https://www.cer-rec.gc.ca/en/index.html" content="Canada Energy Regulator (CER)" >}} works to protect the future of the Canadian energy industry by developing projects which engage with Indigenous communities to ensure energy projects operate safely and under the strictest environmental standards.

A key participant in this process is the **Indigenous Monitors (IM)**:

{{< admonition type="quote" >}} Indigenous peoples, the Government of Canada, and the CER worked together to create the Indigenous Advisory and Monitoring Committees, or IAMCs. These IAMCs operate independently to increase Indigenous involvement in the federal monitoring and oversight of energy-related projects. The Committees provide the opportunity for Indigenous peoples to participate meaningfully in oversight activities along the pipeline corridor while companies do work to build and operate the projects. {{< /admonition >}}

Indigenous monitors participate in regulatory work, including:

* :(fas fa-search fa-fw): On-site inspection
* :(fas fa-pencil fa-fw): Evaluation and training
* :(fas fa-ambulance fa-fw): Emergency response
* :(fas fa-check-circle fa-fw): Compliance verification

### Existing Materials

The inspection process consists of 4 phases which correspond to the on-site workflows. Each project has a corresponding pair of inspection and workflow job aid documents to reference during an inspection. <br>

{{< admonition example "Constraints" true >}} The federal regulator's document management system is tightly integrated to their use of Microsoft Office & Teams.

These constraints are the result of that integration:
1. **MS PowerPoint** is the preferred platform due its simplicity, availability, and compatibility with most images and files
1. **No external libraries** including Acrobat, Office 365, and stock images or graphics
1. **Mobile friendly** iPad Mini is primary viewing device. 
{{< /admonition >}}

The CER & IM inspection serves as the primary report for compliance, activities and conditions concerning the four major extraction projects: TMX, NGTL, Line3, and KXL.

## 3 Process

{{< admonition failure "Initial impression" true >}} Materials exists as **nine** separate documents:
1. Resource intensive to maintain
1. Prone to inconsistent revisions
1. Lacks meaningful method for version control
1. Accessibility concerns, specifically contrast and colour
{{< /admonition >}}

{{< image src="ngtlbefore.jpg" caption="Inspection workflow *job aid* reference" width="90%" height="90%" >}}
{{< image src="ngtlbefore1.jpg" caption="Emergency response exercise *job aid* reference" width="90%" height="90%" >}}

{{< image src="process.jpg" caption="Colour-coding to document disparities between versions" width="100%" height="100%" >}}

