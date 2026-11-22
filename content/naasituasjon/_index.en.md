---
id: e43ca1c8-d579-4f0a-b1e9-832fdff7d21a
title: "Current situation"
linkTitle: "Current situation"
weight: 30
lastmod: 2026-11-22T20:30:40+01:00
last_editor: Erik Hagen

---
How vilbli.no and utdanning.no are owned, run and supplied with data today, how they are used, and who is affected. The description of vilbli.no is based on Novari's description of the current situation as of July 2026, and the visitor figures on a compilation from HK-dir in September 2026.

## vilbli.no

vilbli.no is an information service for applicants to upper secondary education. Its purpose is to give applicants up-to-date and quality-assured information about upper secondary education at all times, as a basis for their choices. The target groups are young people and adults who are going to apply, advisers and parents.

The county authorities are responsible for upper secondary education. They saw a need for a shared, quality-assured information service about the education, the school offerings and national and local rules and deadlines, and chose a joint procurement rather than each solving it separately. vilbli.no has existed for almost 20 years. The service is owned by the county authorities through the county directors' council for competence and education (FKU), and Novari IKS is responsible for procurement, management and operation.

### Operation and editorial work

Operation and the main editorial team were last procured in October 2023. Fagbokforlaget Vigmostad & Bjørke AS won the tender. The contract runs until 2027 with an option to extend (1+1+1 years), and is worth NOK 50 million. As of July 2026, seven people are attached to the agreement, and the main editorial team is estimated at up to six full-time equivalents, depending on the season. Novari has a service owner in an approximately 10 % position.

The editorial work takes place at several levels:

- **The main editorial team** keeps the website up to date: changes in legislation and structure, several hundred articles, occupation descriptions, quizzes and interest tests, addresses of schools and services, translation into Nynorsk, Sami and English and more than 20 other languages, technical operation, universal design, support and posters.
- **The expert group for vilbli.no**, five staff from the county authorities, prioritises further development.
- **Local editors** in each of the 15 county authorities publish local rules, deadlines and information about admission and placement.
- **Subject offering editors** at the upper secondary schools post information about the subjects the school offers.
- **Kristne Friskolers Forbund (KFF)** collects information from private schools that are not in VIGO.

![Ownership, responsibility and editorial work for vilbli.no: FKU owns and instructs, Novari manages, Fagbokforlaget is main editor. Local editors, the expert group, subject offering editors and KFF contribute. Data comes from VIGO with code lists, Udir (Grep) and the National School Register](vilbli-eierskap-og-redaksjon.png)

### Data flow

- **Grep (Udir):** vilbli.no retrieves the curricula and links subjects and teaching hours to the programme areas in the structure map. Changes are made manually, including names in Nynorsk, Sami and English.
- **VIGO:** vilbli.no retrieves all training offerings per school, cooperation bodies (training offices) and training companies through an API. New education programmes and programme areas must be created manually by the main editorial team, which is notified through error messages in the import report.
- **The county authorities:** local rules are published by the local editors in a separate publishing solution.
- **utdanning.no** retrieves data from vilbli.no as XML: all upper secondary schools with addresses, education programmes and programme subjects per school, and descriptions of the programme subjects.
- **The county authorities** can use an open API with descriptions of the education programmes, for example on the schools' websites.

![Data flow and editorial responsibility for vilbli.no: national laws and rules and Grep, school offerings, class arrangements, companies, programme areas and training offices from VIGO, and county-specific forms, deadlines and articles and school-specific subject offerings into vilbli.no. Out go XML export to utdanning.no and data to the county authorities](vilbli-dataflyt.png)

The class arrangement for the next school year must be published from VIGO by 31 December, and the school offerings become available on vilbli.no in January. vilbli.no contains no personal data.

### Use

January is the month with the most visits. In January 2026, vilbli.no had about 300,000 users, 2 million page views and 6 million clicks. The most visited pages are the education programmes with the structure maps of the training pathways, and the interest tests. Among the articles, the most visited are: register your application in Vigo, application deadlines and admission calendar, points and grades, supplementary studies for general university admission certification, what you can apply for, responding to offers, and absence. Local articles on admission rules, the right to appeal, applicants with a minority language background and schooling in other counties are also widely used.

The current solution has functions that a future solution must also provide: content in more than 20 languages, a poster of the education pathways sent to all lower secondary and upper secondary schools every year, printouts of the programme structure and presentations for information meetings.

## utdanning.no

HK-dir develops and operates utdanning.no and karriereveiledning.no. utdanning.no retrieves data from a range of sources: Grep and the National School Register (Udir), VIGO with code lists, apprenticeship accounts and companies, the Brønnøysund Register Centre, the Master Craftsman Register, Nav, Statistics Norway (SSB), Geonorge and vilbli.no.

![Data flow to utdanning.no: data from Udir (Norsk skoleregister and Grep), VIGO (code lists, apprenticeship accounts and company), training offices and training companies, the county authorities, the Brønnøysund Register Centre, Posten, Geonorge, the Master Craftsman Register, Nav, vilbli.no and SSB into Datakollektivet, Data utdanning.no and Finn lærebedrift](utdanning-no-dataflyt.jpg)

HK-dir has also mapped the structure of utdanning.no and the overlap with vilbli.no in Figma.

## Overlap in use

A compilation of visits to the 90,000 most visited pages on each website, over the same period, grouped by content type and level of education, shows that:

- most visits to vilbli.no go to content found on both websites: the presentation of the education programmes, the schools and the training pathway (the programme structure)
- a large share of visits to utdanning.no concern the transition from upper secondary to higher education, and from all levels of education to working life
- much of the content on utdanning.no provides guidance regardless of level of education, for example Jobbkompasset and the interest pages
- vilbli.no also has traffic on curriculum pages from Udir and on each school's subject offering

![Page categories on vilbli.no and utdanning.no by level of education, where bubble size shows the number of sessions. At upper secondary level, vilbli.no dominates with the presentation of the education programmes, subjects and distribution of hours, schools and curricula, while utdanning.no dominates in higher education and content across levels](besoksstatistikk-2025-26.png)

The compilation is not official statistics, but was produced as a basis for decision-making.

## Stakeholders

The pilot identified 33 stakeholders and assessed their interest and influence:

| Stakeholder | Interest | Influence | Category | Measures |
|---|---|---|---|---|
| SAMT-BU | High | Medium | Keep informed | Status meetings every three weeks, pilot report and workshop in August |
| The county directors' council for competence and education (FKU) | High | High | Manage closely | Briefed in FKU-AU and FKU. Decides on vilbli.no |
| Council for HR and ICT/digitalisation (HID) | | Medium | Keep informed | Decides together with FKU on data deliveries from VIGO and InSchool |
| Network for ICT and digitalisation managers (NID) | | Low | Keep informed | Advisory on data deliveries, under HID |
| Digdir | Medium | High | Manage closely | Make API endpoints available on data.norge.no |
| Novari IKS | High | High | Manage closely | Leads the pilot. Working groups, joint editorial workshops and plan for phase-in and phase-out |
| HK-dir (owns utdanning.no) | High | High | Manage closely | Scope, governance model, future organisation, quality requirements and procedures |
| The Norwegian Directorate for Education and Training (Udir) | High | High | | |
| VIGO | High | High | Manage closely | Architecture and data meetings, joint integration plan and test environments. API to vilbli.no via IST |
| The expert group for vilbli.no | High | Medium | Manage closely | Involvement and information |
| Fagbokforlaget Vigmostad & Bjørke | High | Low | Keep informed | Contract with Novari until the end of 2027. Dialogue on insight and plans |
| Local editors | High | Low | Keep informed | Information via the county authorities, guide, possibly webinar. Involve some schools, training and support |
| Editors of subject offerings | Medium | Low | Keep informed | As for local editors |
| Kristne Friskolers Forbund (KFF) | High | Low | Keep informed | Direct information, guides and involvement in the pilot |
| Private upper secondary schools | Medium | Low | Keep informed | Information |
| Staff in the county authorities | High | Low | Keep informed | Information via the county authorities, guide, training and support |
| Career counsellors, advisers and teachers | High | Medium | Keep satisfied | Co-creation with karriereveiledning.no, reference group and briefing at national courses |
| Young people in primary, lower secondary and upper secondary school | Medium | High | Manage closely | User insight, user testing and pupil panel |
| Elevorganisasjonen (the pupils' organisation) | Low | High | Keep satisfied | Meeting in September, after the pilot's deliverable |
| Parents | Medium | Medium | Keep satisfied | Interviews, surveys and user tests |
| The Ministry of Education and Research | Low | High | Keep satisfied | Pilot report and briefing |
| Other public channels that link to the services | Medium | Medium | Keep satisfied | Service notices, newsletters and documentation |
| Norwegian Digital Learning Arena (NDLA) | High | Medium | Monitor (minimal effort) | Information |
| The National Council for Vocational Education and Training (SRY) | Low | Low | Monitor (minimal effort) | Briefing at the next meeting |
| The vocational training committees | Low | Low | Monitor (minimal effort) | Information |
| Training companies and training offices | Low | Low | Monitor (minimal effort) | Reference group or survey |
| Adults who want to complete upper secondary education | Low | Low | Monitor (minimal effort) | Good entry points to Upper secondary for adults (Videregående for voksne) |
| The State Educational Loan Fund (Lånekassen) | Low | Low | Monitor (minimal effort) | Information |
| Nav | Low | Low | Monitor (minimal effort) | Expert meetings, clarified data flows and possibly cooperation agreements |
| The National School Register | Low | Low | Monitor (minimal effort) | |
| Digiung.no | Low | Low | Monitor (minimal effort) | Information |
| Ung.no | Low | Low | Monitor (minimal effort) | Information |
| The Education Register (Utdanningsregisteret) | Low | Low | Under development | |

KS and KS Digital (interest organisation and operational actor for shared digital solutions in the municipal sector) and Sikt (shared services in the education sector) are coordinating and supporting actors.
