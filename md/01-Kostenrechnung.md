---
title: "Kostenrechnung"
author: ""
date: \today
subject: "Markdown"
keywords: [Markdown]
lang: "de"
bibliography: literatur-kfz.bib
csl: zitierstil-number.csl
---
<!---------------------------
Dozent: Kristijan Sebalj
EUR &euro;
Vgl. Tabellenbuch S. 87 [@bell:2021:tabellenbuchKfz].
Vgl. Fachbuch S. 87 [@heiser:2017:betriebsfuhrung].
#
#
ju 28-5-22 Kosten- und Leistungsrechnung
+------------------------------>

$\to$ *Ziel:* Kenngrößen verbessern (Produktivität, Wirtschaftlichkeit, Umsatzrentabilität)

**Kosten- und Leistungsrechnung** (KLR) $\to$ internes Rechnungswesen

vs.

**Buchhaltung** (FiBu) $\to$ externes Rechnungswesen

**Kosten einteilen** 

1. **Vollkostenrechnung** 
    - Indirekte Kosten (Gemeinkosten, kalkulatorische Kosten)
    - Direkte Kosten (Einzelkosten)

2. **Kostenstellenrechnung** (Verursachergerechte Verteilung der Kosten: Lager, Werkstatt, Vertrieb)

3. **Teilkostenrechnung** (fixe Kosten, variable Kosten, Deckungsbeitrag)

# Vollkostenrechnung

Vgl. Kostenrechnung Fachbuch S. 79-102 ([@heiser:2017:betriebsfuhrung]).

## Kosten der Werkstatt

![Kosten und Erlöse](images/Skizze/02_Umsatzerloese_Skizze.pdf){width=40%}

1. **Einzelkosten** (EK), direkte Kosten (Kunden), Fertigungslöhne $\to$ produktive Löhne
   - *Beispiel:* Fertigungslöhne, Anschaffungskosten, Fertigungsmaterialien (Ersatzteile)
   - $\boxed{\text{FL} = WSL \cdot Flh}$  
   - (WSL) = (StLs) Werkstattschnittlohn = Stundenlohnsatz

1. **Gemeinkosten** (GK), indirekte Kosten, Hilfslöhne (W-Aufträge) $\to$ unproduktive Löhne
   - $\boxed{\text{GK} = Seko - EK} \quad \boxed{\text{GK} = \frac{WSL \cdot GKZs}{100}}$  

1. **Selbstkosten** (SeKo)
   - $\boxed{SeKo = EK + GK}$ (Einzelkosten + Gemeinkosten)
   - $\boxed{SeKo = FL + GK}$ vs. $\boxed{SeKo/h = WSL + GK/h}$
   - $\boxed{SeKo_{EUR} = UE - GW} \to \boxed{SeKo_\% = 100~\% - UR_\%}$

1. **Gewinn** (GW) in &euro; 
   - $\boxed{\text{Gewinn} = UE - EK - GK} \quad \boxed{\text{Gewinn/h} = StVs - Seko/h}$ 

1. **Umsatzerlöse** (UE in EUR), Stundenverrechnungssatz (StVs in EUR/h) 
   - Betrag für eine Leistung = Kostendecken + Gewinn
   - $\boxed{UE = EK + GK + GW} \quad \boxed{UE = Seko + GW}$ (Selbstkosten + Gewinn)
   - $\boxed{StVs = StLs/WSL + GK + GW}$

## Gemeinkosten

*Beispiel:* 

- Lohn+Gehalt (unproduktiv)
- Reisekosten
- Kfz (geschäftlich)
- Afa
- Eigenkapital (EK \% Zins)
- kalkulatorische Pacht
- Meisterlohn (unproduktiv)
- kalkulatorische Lohn (Frau)

1. **Gemeinkostenzuschlagsatz** (GKZs) in \%
   - $\boxed{\text{GKZs} = \frac{GK \cdot 100}{FL}}$  

1. **Kalkulatorische Kosten** Gemeinkosten, die keine Ausgaben verursachen; aufwandsfremde Kosten
   - *Beispiel:* kalk.-Miete, kalk.-Abschreibungen, kalk.-Zinsen, kalk.-U-Lohn, kalk.-Wagnisse

1. **Hilfslöhne** entstehen bei Werkstattaufträgen (W-Aufträge)
   - *Beispiel:* Leerlauf, Nacharbeiten, Reparatur von Werkstattfahrzeuge, Urlaub, Feiertage, Wartezeiten

## Gewinn  

Einkommen des Unternehmers, Wagnis, Unternehmensrisiko

**Gewinnzuschlag** (GWZs) in \% $\boxed{\text{GWZs} = \frac{GW \cdot 100}{SeKo}}$


\newpage

## Fertigungslöhne

1) **Fertigungslöhne** (FL), "produktiv", EK, direkt
   - Auftrag direkt dem Kunden in Rechnung stellen
   - $\boxed{\text{FL} = WSL \cdot Flh}$
   - *Beispiel:* $90~\%$ Lohnkosten   

$+$

2) **Hilfslöhne** (HL) "unproduktiv", GK,  nicht direkt
   - *Beispiel:* $10~\%$ Lohnkosten

$= 100~\%$

**Fertigungslöhne entstehen bei**

1) **K-Aufträge**
   - Kundenauftrag, externe Aufträge
   - *Beispiel:* Wartung, Kundendienst, Reparatur

2) **I-Aufträge**
   - interne Aufträge, innerbetrieblich (andere Abteilung des Betriebs)
   - *Beispiel:* Fahrzeugaufbereitung, Gebrauchtwagenreparatur, Überführung, Übergabedurchsicht

3) **G+K-Aufträge**
   - Garantie- und Kulanzanträge
   - für Kunden ohne Berechnung, Gründe: Kulanz, Sachmängelhaftung, Kundenzufriedenheit gewährleisten

\newpage
**Zeitlohn vs. Leistungslohn**

1) **Zeitlohn** Fertigungslohn, produktive Arbeitszeit, Stundenlohn, Tariflohn
   - **FLh** Fertigungslohnstunden
   - **WSL** Werkstattschnittlohn, quer durch die Werkstatt *Beispiel:* Lehrling, Geselle
      - $\boxed{\text{WSL} = \frac{FL}{Flh}}$

2) **Leistungslohn** Lohn für die erbrachte Leistung
   - **AWLs** Arbeitswertlohnsatz
   - **ZELs** Zeiteinheitenlohnsatz
   - **Soll-AW** Vorgabe, wie viele AW muss ich in einer Stunde machen?
   - **Ist-AW** tatsächlich erbrachte Leistung
   - **Mehr-AW** Mehrleistung in AW $\boxed{\text{AW} = \text{Ist-AW} - \text{Soll-AW}}$
   - **Vorgabezeiten** Grundlage für Leistungslohn
      - **ZE** Zeiteinheit (in Min.) 
      - (StVs / 60 = &euro;/ZE x Min. = Preis (&euro;))
      - **AW** Arbeitswert (in Min.) Richtzeiten, Vorgabezeiten
      - **WF** Werkstattfaktor $\to$ wie viele AW/ZE in einer Stunde? (Soll-Leistung, Mindestleistung) (12 AW/h = $\frac{60}{12}$ alle 5 Min. 1 AW)
      - **Leistungsfaktor** (LF) Ist-Leistung
         - tatsächlich erbrachte Leistung je Stunde
         - Leistungsfaktor = Ist-Leistung in AW / Fertigungslohnstunden
         - LF = Ist-AW / FLh
      - **Leistungsgrad** (LG)
         - $\boxed{\text{LG} = \frac{\text{Ist-AW}}{\text{Soll-AW}}}$
         - (Ist-Leistung / Soll-Leistung) und (tatsächlich erbrachte Leistung / Mindestleistung)
      - **Leistungslohnsatz** 
         - Leistungslohnsatz = Fertigungslohn / Fertigungslohnstunden
         - LLs = FL / FLh

\newpage

## Kennwerte der Werkstatt

1. **Soll-Umsatzerlös** (Soll-UE) deckt die Selbstkosten ab 
   - Soll-UE = Seko + GW

2. **Ist-Umsatzerlös** tatsächlich erwirtschaftete Umsatz

3. **Lohnerlöse** Umsatzerlöse

4. **Wirtschaftlichkeit** (WI) wurde Gewinn oder Verlust gemacht *Beispiel:* 1,05 \% $\to$ 5 \% mehr
   - Wirtschaftlichkeit = Umsatzerlöse / Selbstkosten
   - WI = LE / Seko; WI = UE/Seko
   - WI > 1 Gewinn
   - WI < 1 Verlust
   - WI = 1 Kostendeckend

5. **Produktivität** (PR)
   - Gesamte Arbeitszeit (Fertigungs- + Hilfslohnstunden)
   - Produktivität = Fertigungslohnstunden x 100 / Arbeitszeit
   - PR = FLh x 100 / AZ   

6. **Umsatzrentabilität** (UR) in \%
   - Wie viel Prozent des Umsatzes als Gewinn anfallen
   - $\boxed{\text{UR} = \frac{GW \cdot 100}{UE}} \quad \boxed{\text{UR} = \frac{GW/h \cdot 100}{StVs}}$

\newpage
### Kostenindex - Stundenverrechnungssatz - AW-Vs (Prüfung)

*3x wichtige Formeln*

**Kostenindex, Werkstattindex, Faktor** (KI) wievielmal mehr der Kunde für eine Fertigungslohnstunde zu bezahlen hat, als der Monteur in dieser Stunde verdient. (bezieht sich auf Löhne)

$\boxed{\text{KI} = \frac{\text{Prod. Löhne} + \text{GK} + \text{Gewinn}}{\text{Prod. Löhne}}} \quad \boxed{\text{KI} = \frac{\text{FL} + \text{GK} + \text{GW}}{\text{FL}}} \quad$  $\boxed{\text{KI} = \frac{\text{StVs}}{\text{WSL}}} \quad \boxed{\text{KI} = \frac{\text{UE}}{\text{FL}}}$

**Stundenverrechnungssatz** Arbeitspreis, der dem Kunden für eine Stunde berechnet wird. Reparaturstunde = Fertigungslohnstunde

$\boxed{\text{StVs} = \frac{\text{UE}}{\text{FLh}}} \quad \boxed{\text{StVs} = \text{KI} \cdot \text{WSL}}$ 

$\boxed{\text{StVs}_{neu} = \frac{\text{Seko}_{neu} \cdot 100~\%}{\text{Seko}_{alt}}} \quad \boxed{\Delta \text{StVs} = \text{StVs}_{neu} - \text{StVs}_{alt}}$

Erhöhung $\boxed{\text{StVs}_\% = \frac{\Delta \text{StVs} \cdot 100~\%}{\text{StVs}_{alt}}}$

**AW-Verrechnungssatz** Ermittlung des Arbeitspreises für eine Arbeitsposition (Leistungslohn) 

Erlös je AW

$\boxed{\text{AW-Vs} = \frac{\text{StVs}}{\text{WF}}} \quad \boxed{\text{AW-Vs} = \frac{\text{WSL} \cdot \text{KI}}{\text{WF}}} \quad \boxed{\text{AW-Vs} = \frac{\text{UE}}{\text{FLh} \cdot \text{WF}}}$





\newpage

## Handelswarenkalkulation

**Kalkulationsarten** Vorwärts-, Rückwärts-, Differenzkalkulation

### Einkaufskalkulation

```
  BP                                           LEP                 // 100 %
- BK                                         - Rabatt       10 %                 
= BEP                           // 98 %      = ZEP                 // 100 % 
+ Skonto    2 % (in 100)                     - Skonto        2 %
= ZEP                           // 90 %      = BEP                 
+ Rabatt   10 % (in 100)                     + BK
________________________________             ______________________         
= LEP                           EUR          = BP                  EUR 
```

1) **Listeneinkaufspreis** (LEP), Ware, Angebot, $\boxed{BEP + \text{Skonto} + \text{Rabatt}}$
1) **Lieferantenrabatt** (LRa), Preisnachlass
1) **Zieleinkaufspreis** (ZEP), Zahlungszeitpunkt, Kauf auf Ziel $\boxed{BEP + \text{Skonto}}$
1) **Lieferantenskonto** (LSk)
1) **Bareinkaufspreis** (BEP), bei sofortiger Barzahlung
1) **Bezugskosten** (BK), Transport: Verpackung, Fracht, Zoll, Rollgeld

### Verkaufskalkulation, Ersatzteilkalkulation

```
  BP                                           LVP                 // 100 %
+ GK       20 % (auf 100)                    - Rabatt       10 %                 
= SEKO                                       = ZVP                 // 100 %
+ Gewinn    8 % (auf 100)                    - Skonto        2 %
= BVP                           // 98 %      = BVP        
+ Skonto    2 % (in 100)                     - Gewinn
= ZVP                           // 90 %      = Seko                 
+ Rabatt   10 % (in 100)                     - GKZs
________________________________             ______________________          
= LVP                           EUR          = BP                  EUR
+ UST      19 %                                                 
________________________________                        
= Rechnungsbetrag ohne Rabatt   EUR                                 
```


1) **Bezugspreis** (BP), Anschaffungskosten, Einstandspreis $\boxed{BEP + BK}$
2) **Gemeinkosten** (GK), anteilig, nicht direkt
3) **Selbstkosten** (SEKO), Beschaffung, Bereitstellung, Weiterverarbeitung
4) **Gewinn** Wagnis, U-Lohn
5) **Verkaufssonderkosten** Garantie, Provision, Kundendienst
6) **Barverkaufspreis** (BVP) $\boxed{BP + GK + \text{Gewinn}}$
7) **Kundenskonto** (KSk)
8) **Zielverkaufspreis** (ZVP) $\boxed{BP + GK + \text{Gewinn} + \text{Skonto}}$
9) **Kundenrabatt** (KRa)
10) **Listenverkaufspreis** (LVP) $\boxed{BP + GK + \text{Gewinn} + \text{Skonto} + \text{Rabatt}}$


### Kalkulationsfaktor

Vgl. Tabellenbuch S. 61 und 69 ([@bell:2021:tabellenbuchKfz]).

![Kalkulationsfaktor](images/Skizze/03_Kalkulationsfaktor_Skizze.pdf){width=60%}

**Kalkulationsfaktor** (KF) wievielmal höher der (Verkaufspreis = Listenpreis) gegenüber (Bezugspreis) 
bezieht sich auf das Lager, Ersatzteil

$\boxed{KF = \frac{LVP}{BP}} \quad \to \boxed{LVP = BP \cdot KF}$

**Kalkulationszuschlag** enthält $(GK + \text{Gewinn} + \text{Skonto} + \text{Rabatt})$ bezogen auf (Bezugspreis)

**Handelsspanne** (HSP) unterschied zwischen (Verkaufspreis + Bezugspreis) bezogen auf (Verkaufspreis) $\boxed{HSP_\% = \frac{HSP \cdot 100}{LVP}}$
$\boxed{HSP_\text{EUR} = LVP - BP}$

### Verkauf von Tauschteilen und Agenturwarenverkauf

**Altteilesteuer** (AT-St) kauft ein Kunde ein Tauschteil und gibt dabei sein defektes Teil (Altteil) in Zahlung, fällt Altteilesteuer an. $\boxed{LVP \cdot 10~\% \cdot 19~\%} \quad \boxed{LVP \cdot 0,1 \cdot 0,19}$

**Agenturwaren** sind Waren, die im Auftrag und auf Rechnung einer Fremdfirma verkauft werden (Preise inkl. Gesetzl. Ust.).


### Rechnungserstellung

Kostenvoranschlag (KVA)

**Formvorschriften beachten** 

- Rechnung schriftlich mit Rechnungsnummer und Leistungsdatum 
- Kunden- und Fahrzeugdaten wichtige aufführen 
- Arbeitspreis und Ersatzteilpreise detailliert aufführen 
- Netto-Rechnungsbetrag, Umsatzsteuer, Altteilesteuer und Brutto-Rechnungsbetrag einzeln aufführen.

$\text{AP} = \text{Flh} \cdot \text{StVs} \quad \text{AP} = \text{AW-Vs} \cdot \Sigma \text{AW}$

$\text{AP}_\text{Seko} = \Sigma \text{AW} \cdot \text{Seko}_{AW} \quad \text{Werkstatt AW-Preis} = \Sigma \text{AW} \cdot \text{Seko}_{AW} + \text{GW}$

```
Pos    Bezeichnung                              AW-Vs x AW           Preis
_____________________________________________________________________________
  1
  2
  3
_____________________________________________________________________________
  Summe AP                                                                EUR

                           EK                                  VP
                           80 %  20 %     100 % 24 %           124 %
                           ZEP x Rabatt = LEP + GW                      
Anzahl      Ersatzteil     (EK x 1,25)    (LEP x 1,24)       E-Preis Et-Preis
   oder
Anzahl      Ersatzteil     Rabatt (Kunden)      LVP          E-Preis Et-Preis
_____________________________________________________________________________
  1                        10 %                 (Preis x 0,9)
  1         AT-Teil
  3
_____________________________________________________________________________
  Summe ET                                                                EUR

                                                                     Preis
_____________________________________________________________________________
  AP
+ ET
+ Fremdleistung
+ Zubehör
+ Schmierstoffe
= Reparaturkosten 
+ UST                                           19 % 
+ AT-Steuer (AT-Teil x 0,1 x 0,19)
+ Agenturware (Öl)
_____________________________________________________________________________
= Rechnungsbetrag                                                         EUR
```

\newpage

### Kosten des Lagers

- Kosten des Lagers
- Kennwerte des Lagers

\newpage

# Abschreibung

- linear 
- degressiv: am Anfang schnell abschreiben, Investition ankurbeln 
- Kombination aus linear und degressiv
- Leistung

**Begriffe**

- Anschaffungswert 
- Buchwert 
- Nutzungsdauer 
- Abschreibungsbetrag 
- Abschreibungssatz 
- AfA mindert Gewinn, weniger Steuern zahlen 
- GWG

**Berechne den Buchwert nach 6 Jahren**

```
  Einkaufspreis  10.000,00
+ 5%                500,00   // Transport-, Montage und Anschlusskosten
__________________________
= AK             10.500,00   // ND: 8J

            Jahr Abschreibung Buchwert
__________________________________________           
degressiv 1J 20%     2.100,00 8.400,00 EUR
          2J 20%     1.680,00 6.720,00 EUR
          3J 20%     1.344,00 5.376,00 EUR      
          4J 20%     1.075,20 4.300,80 EUR
linear    5J         1.075,20 3.225,60 EUR
          6J         1.075,20 2.150,40 EUR
```

\newpage
