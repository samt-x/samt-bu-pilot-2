---
id: e43ca1c8-d579-4f0a-b1e9-832fdff7d21a
title: "Nåsituasjon"
linkTitle: "Nåsituasjon"
weight: 30

---
Hvordan vilbli.no og utdanning.no er eid, drevet og forsynt med data i dag, hvordan de brukes, og hvem som er berørt. Beskrivelsen av vilbli.no bygger på Novaris nåsituasjonsbeskrivelse per juli 2026, og besøkstallene på en sammenstilling fra HK-dir i september 2026.

## vilbli.no

vilbli.no er en informasjonstjeneste for søkere til videregående opplæring. Formålet er å gi søkerne oppdatert og kvalitetssikret informasjon om videregående opplæring til enhver tid, som grunnlag for valgene deres. Målgruppene er ungdom og voksne som skal søke, rådgivere og foreldre.

Fylkeskommunene har ansvaret for videregående opplæring. De så behov for en felles, kvalitetssikret informasjonstjeneste om utdanningen, skoletilbudene og nasjonale og lokale regler og frister, og valgte en felles anskaffelse framfor å løse det hver for seg. vilbli.no har eksistert i snart 20 år. Tjenesten eies av fylkeskommunene gjennom Fylkesdirektørkollegiet for kompetanse og utdanning (FKU), og Novari IKS har ansvaret for anskaffelse, forvaltning og drift.

### Drift og redaksjon

Drift og hovedredaksjon ble sist anskaffet i oktober 2023. Fagbokforlaget Vigmostad & Bjørke AS vant anbudet. Kontrakten løper til 2027 med mulighet for forlengelse (1+1+1 år), og har en verdi på 50 millioner kroner. Per juli 2026 er sju personer knyttet til avtalen, og hovedredaksjonen anslås til opptil seks årsverk, avhengig av sesong. Novari har en tjenesteansvarlig i om lag 10 % stilling.

Det redaksjonelle arbeidet skjer på flere nivåer:

- **Hovedredaksjonen** holder nettstedet oppdatert: endringer i lovverk og struktur, flere hundre artikler, yrkesbeskrivelser, quiz og interessetester, adresser til skoler og tjenester, oversettelse til nynorsk, samisk og engelsk og over 20 andre språk, teknisk drift, universell utforming, support og plakater.
- **Faggruppen for vilbli.no**, fem ansatte fra fylkeskommunene, prioriterer videreutviklingen.
- **Lokale redaktører** i hver av de 15 fylkeskommunene publiserer lokale regler, frister og informasjon om inntak og formidling.
- **Fagtilbudsredaktører** ved de videregående skolene legger ut informasjon om fag skolen tilbyr.
- **Kristne Friskolers Forbund (KFF)** samler informasjon fra private skoler som ikke er i VIGO.

![Eierskap, ansvar og redaksjonelt arbeid for vilbli.no: FKU eier og instruerer, Novari forvalter, Fagbokforlaget er hovedredaktør. Lokale redaktører, faggruppen, fagtilbudsredaktører og KFF bidrar. Data kommer fra VIGO med kodeverk, Udir (Grep) og Nasjonalt skoleregister](vilbli-eierskap-og-redaksjon.png)

### Dataflyt

- **Grep (Udir):** vilbli.no henter læreplanene og knytter fag og timetall til programområdene i strukturkartet. Endringer gjøres manuelt, også navn på nynorsk, samisk og engelsk.
- **VIGO:** vilbli.no henter alle opplæringstilbud per skole, samarbeidsorganer (opplæringskontorer) og lærebedrifter gjennom et API. Nye utdanningsprogram og programområder må opprettes manuelt av hovedredaksjonen, som får beskjed gjennom feilmeldinger i importrapporten.
- **Fylkeskommunene:** lokale regler publiseres av de lokale redaktørene i en egen publiseringsløsning.
- **utdanning.no** henter data fra vilbli.no som XML: alle videregående skoler med adresser, utdanningsprogram og programfag per skole, og beskrivelser av programfagene.
- **Fylkeskommunene** kan bruke et åpent API med beskrivelser av utdanningsprogrammene, for eksempel på skolenes nettsider.

![Dataflyt og redaksjonelt ansvar for vilbli.no: nasjonale lover og regler og Grep, skoletilbud, klasseordning, bedrifter, programområder og opplæringskontorer fra VIGO, og fylkesspesifikke skjemaer, frister og artikler og skolespesifikke fagtilbud inn til vilbli.no. Ut går XML-eksport til utdanning.no og data til fylkeskommunene](vilbli-dataflyt.png)

Klasseordningen for neste skoleår må være lagt ut fra VIGO innen 31. desember, og skoletilbudene blir tilgjengelige på vilbli.no i januar. vilbli.no inneholder ikke personopplysninger.

### Bruk

Januar er måneden med mest besøk. I januar 2026 hadde vilbli.no om lag 300 000 brukere, 2 millioner sidevisninger og 6 millioner klikk. De mest besøkte sidene er utdanningsprogrammene med strukturkartene over opplæringsløpene, og interessetestene. Blant artiklene er de mest besøkte: registrer søknaden på Vigo, søknadsfrister og inntakskalender, poengsum og karakterer, påbygging til generell studiekompetanse, hva du kan søke, svar på tilbud og fravær. Lokale artikler om inntaksregler, klagerett, minoritetsspråklige søkere og skolegang i andre fylker er også mye brukt.

Dagens løsning har funksjoner som en framtidig løsning også må ivareta: innhold på over 20 språk, en plakat over utdanningsløpene som sendes til alle ungdomsskoler og videregående skoler hvert år, utskrift av tilbudsstrukturen og presentasjoner til orienteringsmøter.

## utdanning.no

HK-dir utvikler og drifter utdanning.no og karriereveiledning.no. utdanning.no henter data fra en rekke kilder: Grep og Nasjonalt skoleregister (Udir), VIGO med kodeverk, læreplassregnskap og bedrifter, Brønnøysundregistrene, Mesterregisteret, Nav, SSB, Geonorge og vilbli.no.

![Dataflyt til utdanning.no: data fra Udir (Norsk skoleregister og Grep), VIGO (kodeverk, læreplassregnskap og bedrift), opplæringskontorer og lærebedrifter, fylkeskommunene, Brønnøysundregistrene, Posten, Geonorge, Mesterregisteret, Nav, vilbli.no og SSB inn til Datakollektivet, Data utdanning.no og Finn lærebedrift](utdanning-no-dataflyt.jpg)

HK-dir har også kartlagt strukturen på utdanning.no og overlappen med vilbli.no i Figma.

## Overlapp i bruken

En sammenstilling av besøket på de 90 000 mest besøkte sidene på hvert nettsted, i samme periode, gruppert etter innholdstype og utdanningsnivå, viser at:

- det meste av besøket på vilbli.no går til innhold som finnes på begge nettstedene: presentasjonen av utdanningsprogrammene, skolene og opplæringsløpet (tilbudsstrukturen)
- en stor del av besøket på utdanning.no gjelder overgangen fra videregående til høyere utdanning, og fra alle utdanningsnivåer til arbeidslivet
- mye av innholdet på utdanning.no veileder uavhengig av utdanningsnivå, for eksempel Jobbkompasset og interessesidene
- vilbli.no har også trafikk på læreplansider fra Udir og på hver skoles fagtilbud

![Sidekategorier på vilbli.no og utdanning.no etter utdanningsnivå, der boblestørrelsen viser antall sesjoner. På videregående nivå dominerer vilbli.no med presentasjon av utdanningsprogrammene, fag og timefordeling, skoler og læreplaner, mens utdanning.no dominerer på høyere utdanning og innhold på tvers av nivåer](besoksstatistikk-2025-26.png)

Sammenstillingen er ikke offisiell statistikk, men laget som beslutningsgrunnlag.

## Interessenter

Piloten identifiserte 33 interessenter og vurderte deres interesse og innflytelse:

| Interessent | Interesse | Innflytelse | Kategori | Tiltak |
|---|---|---|---|---|
| SAMT-BU | Stor | Middels | Holdes informert | Statusmøter hver tredje uke, pilotrapport og workshop i august |
| Fylkesdirektørkollegiet for kompetanse og utdanning (FKU) | Stor | Stor | Tett oppfølging | Orientert i FKU-AU og FKU. Beslutter om vilbli.no |
| Kollegiet for HR og IKT/digitalisering (HID) | | Middels | Holdes informert | Beslutter sammen med FKU om dataleveranser fra VIGO og InSchool |
| Nettverk for IKT- og digitaliseringsledere (NID) | | Lav | Holdes informert | Rådgivende om dataleveranser, under HID |
| Digdir | Middels | Stor | Tett oppfølging | Tilgjengeliggjøre API-endepunkter på data.norge.no |
| Novari IKS | Stor | Stor | Tett oppfølging | Leder piloten. Arbeidsgrupper, felles redaksjonelle workshops og plan for innfasing og avvikling |
| HK-dir (eier utdanning.no) | Stor | Stor | Tett oppfølging | Scope, styringsmodell, framtidig organisering, kvalitetskrav og rutiner |
| Utdanningsdirektoratet | Stor | Stor | | |
| VIGO | Stor | Stor | Tett oppfølging | Arkitektur- og datamøter, felles integrasjonsplan og testmiljøer. API mot vilbli.no via IST |
| Faggruppen for vilbli.no | Stor | Middels | Tett oppfølging | Involvering og informasjon |
| Fagbokforlaget Vigmostad & Bjørke | Stor | Lav | Holdes informert | Kontrakt med Novari ut 2027. Dialog om innsikt og planer |
| Lokale redaktører | Stor | Lav | Holdes informert | Informasjon via fylkeskommunene, veileder, eventuelt webinar. Involvere noen skoler, opplæring og support |
| Redaktører for fagtilbud | Middels | Lav | Holdes informert | Som for lokale redaktører |
| Kristne Friskolers Forbund (KFF) | Stor | Lav | Holdes informert | Direkte informasjon, veiledninger og involvering i pilot |
| Private videregående skoler | Middels | Lav | Holdes informert | Informasjon |
| Ansatte i fylkeskommunene | Stor | Lav | Holdes informert | Informasjon via fylkeskommunene, veileder, opplæring og support |
| Karriereveiledere, rådgivere og lærere | Stor | Middels | Tilfredsstilles | Samskaping med karriereveiledning.no, referansegruppe og orientering på landskurs |
| Ungdom i grunnskole og videregående | Middels | Høy | Tett oppfølging | Brukerinnsikt, brukertesting og elevpanel |
| Elevorganisasjonen | Liten | Høy | Tilfredsstilles | Møte i september, etter pilotens leveranse |
| Foresatte | Middels | Middels | Tilfredsstilles | Intervjuer, spørreundersøkelser og brukertester |
| Kunnskapsdepartementet | Lav | Stor | Tilfredsstilles | Pilotrapport og orientering |
| Andre offentlige kanaler som lenker til tjenestene | Middels | Middels | Tilfredsstilles | Driftsmeldinger, nyhetsbrev og dokumentasjon |
| Nasjonal digital læringsarena (NDLA) | Høy | Middels | Minimal innsats | Informasjon |
| Samarbeidsrådet for yrkesopplæring (SRY) | Lav | Lav | Minimal innsats | Orientering i neste møte |
| Yrkesopplæringsnemndene | Lav | Lav | Minimal innsats | Informasjon |
| Lærebedrifter og opplæringskontor | Lav | Lav | Minimal innsats | Referansegruppe eller spørreundersøkelse |
| Voksne som vil ta videregående | Lav | Lav | Minimal innsats | Gode innganger til Videregående for voksne |
| Lånekassen | Lav | Lav | Minimal innsats | Informasjon |
| Nav | Lav | Lav | Minimal innsats | Fagmøter, avklarte dataløp og eventuelt samarbeidsavtaler |
| Nasjonalt skoleregister | Lav | Lav | Minimal innsats | |
| Digiung.no | Lav | Lav | Minimal innsats | Informasjon |
| Ung.no | Lav | Lav | Minimal innsats | Informasjon |
| Utdanningsregisteret | Lav | Lav | Under utvikling | |

KS og KS Digital (interesseorganisasjon og operativ aktør for felles digitale løsninger i kommunesektoren) og Sikt (fellestjenester i utdanningssektoren) er samordnende og støttende aktører.
