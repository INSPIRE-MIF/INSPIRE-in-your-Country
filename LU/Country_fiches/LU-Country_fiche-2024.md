# LU - 2024: Country Fiche

## Table of Contents
1. [Introduction](#introduction)
1. [State of Play](#state_of_play)
   1. [Coordination](#Coordination)
   2. [Functioning and coordination of the infrastructure](#functioning)
   3. [Usage of the infrastructure for spatial information](#usage)
   4. [Data Sharing Arrangements](#data)
   5. [Costs and Benefits](#costs)


## Introduction

The INSPIRE Directive sets the minimum conditions for interoperable sharing and exchange of spatial data across Europe as part of a larger European Interoperability Framework and the e-Government Action Plan that contributes to the Digital Single Market Agenda. 
Article 21 of INSPIRE Directive defines the basic principles for monitoring and reporting. 
More detailed implementing rules regarding INSPIRE monitoring and reporting have been adopted as Commission Implementing Decision (EU) 2019/1372 on the 19th August 2019. 

This country fiche highlights the progress in the various areas of INSPIRE implementation. It includes information on monitoring 2023 acquired in December 2023 and Member States update.

## State of Play

A high-level view on the governance, use and impact of the INSPIRE Directive in Luxembourg. More detailed information is available on the INSPIRE knowledge base.

Luxembourg has an INSPIRE law since 2010 and has implemented and maintainted the national INSPIRE node since then.
All Annex I data has been harmonised from the beginning and the harmonisazion of Annex II and III data has been planned in
2017 in a 4 year road map which has been transposed until the End of 2020.

Everything went well and almost all INSPIRE relevant data has been made available in a harmonised way. A 4 year roadmap
was set up in 2021 for the operation of the INSPIRE platform and harmonization of new or updated datasets and some more data has been added / harmonized since.

In order to cope with the new requirements from the HVD Implementing Regulation, the roadmap has been adapted. Starting from 2022, an OGC API Features service has been added for every vector dataset and the entire platform is now being reused in order to serve non-INSPIRE relevant HVD in the same way we already do it for INSPIRE-relevant HVD.

Thus, Luxembourg demonstrates its commitment to advancing data reuse by adopting the latest OGC API Features standards. This forward-thinking approach surpasses the legally compliant and easier-to-setup WFS, ensuring alignment with the most current web standards.

Luxembourg is also dedicated to providing up-to-date and INSPIRE-compliant data. Recently, Lux has implemented an automated update schedule for all datasets and established an automatic validation process to continuously monitor and ensure the conformity of published data, so that several datasets are updated daily, others weekly, monthly or at least yearly, according to their lifecycle.

### Coordination

#### National Contact Point

- Name of Public Authority: Administration du cadastre et de la topographie
- Postal Address: 1, rue Charles Darwin, L-1433 Luxembourg
- Contact Email: inspire@geoportail.lu
- Telephone Number: +352 247 54 401
- Telefax Number: /
- National INSPIRE Website: [https://catalog.inspire.geoportail.lu](https://catalog.inspire.geoportail.lu)
- MIG Contacts: 
  - Contact Person: Bernard Reisch
  - Email: bernard.reisch@act.etat.lu
  - Telephone Number: +352 247 544 00
  - Contact Person: Jeff Konnen
  - Email: jeff.konnen@act.etat.lu
  - Telephone Number: +352 247 544 00
- MIG T Contacts: 
  - Contact Person: Jeff Konnen
  - Email: jeff.konnen@act.etat.lu
  - Contact Person: Nadine Biver
  - Email: nadine.biver@act.etat.lu 

#### Coordination Structure & Progress: 

##### Coordination structure

The coordination structure created by the national [INSPIRE law](https://legilux.public.lu/eli/etat/leg/loi/2010/07/26/n4/consolide/20150101) is called CC-ILDG:
* Comité de Coordination de l’Infrastructure Luxembourgeoise de Données Géographiques CC-ILDG, created in 2009, is an organisation that acts as a steering committee of all the activities concerning the creation, updating, management and distribution of geographic data, either in analogue or in digital form. This group is led by the Administration du Cadastre et de la Topographie (ACT), who is responsible for an important part of the geographic data currently available in the Grand-Duchy.
* Groupe Technique de l'Infrastructure de Données Géographiques GT-ILDG: The members are representatives of their respective public organizations, appointed by their ministers or directors in charge meet 2-4 times a year to discuss projects related to geodata, to discuss challenges and the progress of development of the geoportal tools created by the ILDG / Geoportal team at the ACT.
* Thematic Working Groups: if special interest topics arise during general meetings, working groups are constituted and agree a meeting schedule. The actual WGs are: WG for legislation purposes, WG for points of interest, WG for water data, WG for geodata policies, WG for the management of metadata. Currently there are two active working groups, one for the usage of UAVs and one for creating an online platform about underground data (pipes etc)

##### Progress

The separation of CC-ILDG and GT-ILDG has been decided in 2019 so that the "CC" can focus on the tasks given by law and the GT can focus on technical aspects.
Most if not all geographic data produced by the public sector in Luxembourg is released under Creative Commons 0 license to the public domain and is available on https://data.public.lu. This is a
huge step and it also helps the public actors to collaborate better.
All the data that is being harmonized for INSPIRE is taken from the open data portal, harmonized and put back there under the same license as INSPIRE GML.
The whole harmonizing process has been fully automated, so that GMLs, ATOM Feeds and WMS View Services are created by a process that is fed by mapping rules.

Recently, OGC API Features has been added to the infrastructure to meet the needs of the High Value Dataset Regulation so that all the High Value Datasets that fall under the INSPIRE Directive
do automatically meet the conditions. The GML files are considered as bulk downloads and the OGC API Features represent the API Part.

A very high percentage of the data is harmonized and we continue harmonizing newly available or updated datasets.

### Functioning and coordination of the infrastructure <a name="functioning"></a>

In order to be able to deliver a more complete portfolio of Luxembourg’s INSPIRE-related datasets, ACT has proceeded to a detailed assessment of Luxembourg’s situation in the INSPIRE dossier with the help of external experts. This inventory is now being done once a year and we currently focus on streamlining the process in regard to environmental reporting obligations so that datasets that are officially submitted to the EC through EIONET are also being shown as INSPIRE datasets and services

All the identified datasets have to be published under an open license (CC0 if possible) on the national data portal. The INSPIRE experts will then contact the data producers to define the mapping rules and they will implement a script that can be automatically executed regularly.

Domain experts only have to update their data on the open data portal and the INSPIRE scripts will automatically convert the data to the INSPIRE data models.

The "Groupe Technique" of the ILDG meets 2-4 times a year to discuss different aspects of the ILDG and to coordinate the experts work on INSPIRE.

### Usage of the infrastructure for spatial information <a name="usage"></a>

The showcase of the Luxemburg’s SDI is the Luxembourgish geoportal which opens up an access to the different users.
The LSDI offers a lot of OGC compliant webservices (WMS, WFS, CSW, OGC API Features), open data and a very powerful viewer (http://map.geoportail.lu). 
A lot of efforts are being put into the visualization of 3D data (pointclouds, terrains, meshes, 3D buildings).
Independently of the special geoportal dedicated to INSPIRE, the national geoportal of Luxembourg has great success
and is widely used by the general public. It counts more than 20'000 visitors per day, through its different viewers,
webservices and APIs.

### Data Sharing Arrangements <a name="data"></a>

The LSDI and especially the INSPIRE implementation is based on the principle that all geodata should be released under an open license to the open data portal.
This means that there are no further data sharing arrangments needed anymore as all the data is openly available for all, without any restrictions.

### Costs and Benefits <a name="costs"></a>

The budget for external services of the LSDI in the last years has been the following:

- 2020: 779'220 €
- 2021: 679'770 €
- 2022: 862'290 €
- 2023: 932'490 €
- 2024: 977'352 €

In 2021 the budget was lowered because INSPIRE was supposed to be finished, but in the following years it has been augmented again to cope with the new HVD requirements.

The "ILDG and Geoportal" department employs 6 people.

The existence of the national geoportal, seen independently from the INSPIRE initiative, has brought great benefits to Luxemburg’s public sector bodies, private firms and the citizen in general.
INSPIRE and the geoportal have been integrated on the list of important factors in the national administrative simplification program.
