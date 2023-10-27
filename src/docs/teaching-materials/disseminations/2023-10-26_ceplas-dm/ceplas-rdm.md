---
marp: true
theme: marp-theme_dataplant-ceplas-ccby
paginate: true
license: '[CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/)'
title: CEPLAS RDM
author:
- name: Dominik Brilhaus
  github: https://github.com/brilator
  orcid: https://orcid.org/0000-0001-9021-3197
---

<style>

.two-columns {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 4rem;
}

figcaption {
  font-size: 10px;
  font-style: italic;
}

.reference {
  font-size:15px;
  line-height: 1.2em;
  position: fixed;
  left: 50%;
  bottom: 0px;
  transform: translate(-50%, -50%);
  margin: 0 auto;
}

.reference-bgright {
  font-size:15px;
  line-height: 1.2em;
  position: fixed;
  right: 0px;
  bottom: 0px;
  transform: translate(-50%, -50%);
  margin: 0 auto;
}

</style>

# CEPLAS research data management (RDM)

<style scoped>section {background: none; background-color: white}</style>
<!-- _paginate: false -->

<br>

Steering Committee Meeting
October 27th, 2023

Dominik Brilhaus, [CEPLAS Data Science](https://www.ceplas.eu/en/research/data-science-and-data-management/)

---

# Goals of CEPLAS RDM

- share data
- share resources
- collaborate

---

# Avoid Scattered Data Silos

![w:900](././../../../img/data_fragmentation_CEPLAS_MibiNet_TRR.png)

---

# Roadmap

1. Agree on an RDM system
2. Build use-cases and templates
3. Train researchers
4. Start sharing

---

# How to store data &ndash; ARCs

ARC = Annotated Research Context

![width:850](./../../../img/ARC_fillWithData_seq8.png)

---

# Where to share data &ndash; DataHUB

The <a href="https://git.nfdi4plants.org" target="_blank">DataHUB</a> is a federated platform for ARCs

![w:550](./../../../img/tpj16474-fig-0002-m.jpg)

<span class="reference"> Weil, H.L., Schneider, K., et al. (2023), PLANTdataHUB: a collaborative platform for continuous FAIR data sharing in plant research. Plant J. https://doi.org/10.1111/tpj.16474 </span>

---

# ARC ecosystem demo @ *Tag der Forschungsdaten* <!-- fit -->

November 14th, 2023

![w:700](hhu-tdfdm-2023.png)

https://www.fdm.hhu.de/veranstaltungen/tag-der-forschungsdaten-in-nrw-2023

---

# CEPLAS research data policy

<style scoped> section {font-size:25px;} </style>

*To be circulated in SC soon* (> [current version](https://uni-duesseldorf.sciebo.de/apps/onlyoffice/721579600?filePath=%2FCEPLAS-data-policy%2FCEPLAS-data-policy.docx))

- §1 Coverage
- §2 Legal framework conditions
- §3 Handling of research data
- §4 Responsibilities
  - Data delivery
  - Data access
  - Data selection
  - Data use
  - Training
- §5 Validity and governance

![bg right:40% w:400px](./policy-screenshot.png)

---

# ARC entry points

<div class="two-columns">
<div class="two-columns-left">

##### Workshops and lab hackathons

![w:300](../2023-06-28_ARC-Club_HHU/images/ARCClub.drawio.svg)

##### Case studies

![w:400](ceplas-ARCs.drawio.svg)

</div>

<div class="two-columns-right">

##### Core facilities

![w:350](./../../../img/enablingPlatform-FileShare.drawio.png)

##### Resource ARCs

![w:300](resource-ARCs.drawio.svg)

</div>
</div>

---

# What I need from you

1. Lighthouse projects
   1. Mainly CEPLAS-funded
   2. Cross-lab / Cross-RA collaborations
   3. CEPLAS researchers still present, active and willing to polish ARC
2. Appointments for lab Hackathons
   1. Sit together two days to create ARCs
3. Your backing "My boss said..."

---

# Available dates

for lab hackathons

- Nov 15th & 16th (Wed + Thu)
- Nov 22nd & 23rd (Wed + Thu)
- Nov 30th & Dec 1st (Thu + Fri)
- Nov 7th & Dec 8th (Thu + Fri)

---

# Lab Hackathons

- Good internet connection
- Isolated from lab // office // daily duties
- Access to the data to be ARCified
(file share, hard disks)
- Agile, communicative, collaborative, positive
- Technical *ad-hoc* support by DataPLANT

![bg right:40% w:500](../2023-06-28_ARC-Club_HHU/images/ARCClub.drawio.svg)

:bulb: [ARC Club (@HHU Plant Biochemistry)](https://nfdi4plants.org/nfdi4plants.knowledgebase/docs/teaching-materials/disseminations/2023-06-28_ARC-Club_HHU/)

---

# Case studies

- Create ARCs from CEPLAS publications
- Publish CEPLAS data as ARCs

:bulb: [Publication to ARC](https://nfdi4plants.org/nfdi4plants.knowledgebase/docs/guides/publicationToARC.html)

:bulb: [ARC Data Publications](https://nfdi4plants.org/nfdi4plants.knowledgebase/docs/DataHUB-Manual/datahub-data-publications.html)


![bg right w:500](ceplas-ARCs.drawio.svg)

---

# Core facilities / enabling platforms

![bg right w:550](./../../../img/enablingPlatform-FileShare.drawio.png)

- Help with switch towards ARC ecosystem
- Create templates
- Create use-cases


:bulb: [ARCs in Enabling Platforms](https://nfdi4plants.org/nfdi4plants.knowledgebase/docs/guides/ARC-enablingPlatforms.html)

---

# Data of common interest: resources

In addition to ***research data***, which CEPLAS resources do we want to share and catalog?

<br>

<div class="two-columns">
<div class="two-columns-left">

- Identify standards
- Identify / build databases
- Create templates

</div>

<div class="two-columns-right">

![](resource-ARCs.drawio.svg)

</div>
</div>

---

# Network

We're connecting to other consortia using ARCs

- TRR341, https://trr341.uni-koeln.de/ <img style="width:5%" src='https://trr341.uni-koeln.de/sites/crc_trr_341/TRR341_logo.png'/>
- CRC1535, https://www.sfb1535.hhu.de/ <img style="width:6%" src='https://www.sfb1535.hhu.de/fileadmin/redaktion/Fakultaeten/Mathematisch-Naturwissenschaftliche_Fakultaet/Biologie/SFB1535/Bilder/MibiNet.png'/>
- FAIRagro, https://www.fairagro.net/ <img style="width:10%" src='https://fairagro.net/wp-content/uploads/2023/10/Fairagro_Logo_linksbuendig_Verlauf-768x214.png'/>
  -  IPK -> TransCend
- NFDI4BioImage, https://nfdi4bioimage.de/ <img style="width:10%" src='https://nfdi4bioimage.de/fileadmin/_processed_/a/6/csm_1_NDFI_Logo_4c_2ece41ad10.png'/> 

---

# Resources

### <img align="left" style="height:35px" src='https://raw.githubusercontent.com/nfdi4plants/Branding/7e7d442aafeaa767b9c14a63a16e459dadcbdaaf/logos/DataPLANT/DataPLANT_logo_minimal_rounded_bg_darkblue.svg'/> DataPLANT (nfdi4plants)

Website: <a href="https://nfdi4plants.org/" target="_blank">https://nfdi4plants.org/</a>
Knowledge Base: <a href="https://nfdi4plants.org/nfdi4plants.knowledgebase/" target="_blank">https://nfdi4plants.org/nfdi4plants.knowledgebase/</a>
DataHUB: <a href="https://git.nfdi4plants.org" target="_blank">https://git.nfdi4plants.org</a>
GitHub: <a href="https://github.com/nfdi4plants" target="_blank">https://github.com/nfdi4plants</a>
