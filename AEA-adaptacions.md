Hola, et passo el resum d'una sessió anterior. He fet servir delimitadors personalitzats tipus -- (bloc) -- per evitar errors de format. Si us plau, processa'l.

# RESUM D'ESTAT — M1665 DIGITALITZACIÓ APLICADA ALS SECTORS PRODUCTIUS
## Projecte INS Torre Roja — GS ASIX, perfil Ciberseguretat

## 1. CONTEXT GENERAL I OBJECTIU

Estem treballant en l'adaptació del mòdul **M1665 — Digitalització aplicada als sectors productius** per al CFGS d'ASIX amb perfil de Ciberseguretat.

El mòdul disposa de **33 hores al centre i 0 hores a l'empresa**, i s'ha estructurat a partir de cinc REA existents, procedents principalment del Proyecto EDIA/CEDEC, que s'estan convertint en cinc AEA.

L'objectiu general NO és crear el mòdul des de zero, sinó:

1. Reutilitzar al màxim els REA existents.
2. Traduir-los i adaptar-los al català.
3. Contextualitzar-los només quan sigui útil per al perfil ASIX/Ciberseguretat.
4. Ajustar-los de la durada original a les 33 h disponibles.
5. Garantir la traçabilitat curricular RA → CA → activitats → evidències → avaluació.
6. Evitar convertir M1665 en una duplicació dels mòduls tècnics d'ASIX.
7. Fer que les cinc AEA constitueixin un itinerari progressiu i coherent.
8. Publicar/adaptar els materials com a pàgines GitHub Pages, aprofitant tant com sigui possible l'estructura original.

Principi general adoptat:

**Màxima reutilització del material existent + mínima intervenció necessària.**

No es busca "millorar" o reescriure per gust allò que ja funciona.

---

# 2. METODOLOGIA GENERAL ACORDADA

Una decisió metodològica important és que els REA **no es convertiran en classes magistrals**.

L'alumnat ha de poder:

- navegar pels materials;
- llegir-los de manera autònoma;
- avançar al seu ritme;
- fer petites activitats de comprovació/anàlisi;
- aplicar posteriorment els conceptes.

El paper docent és principalment:

- contextualitzar;
- orientar;
- resoldre dubtes;
- regular el ritme;
- fer síntesis breus;
- introduir checkpoints quan sigui necessari.

Per tant, quan cal reduir un REA original de 8–10 sessions a moltes menys hores, la prioritat és:

**conservar bona part de la documentació/navegació i retallar sobretot activitats llargues, productes, reptes, presentacions i tasques redundants.**

Això permet també una adaptació molt més directa a GitHub Pages.

---

# 3. ESTRUCTURA GLOBAL DEL MÒDUL

Les cinc AEA acordades són:

| AEA | Nom | RA principal | Hores |
|---|---|---|---:|
| AEA1 | Operació Digitalització | RA1 + RA2 | 5 |
| AEA2 | Operació Cloud Computing | RA3 | 6 |
| AEA3 | Operació Ciberseguretat | RA5 | 3 |
| AEA4 | Operació Intel·ligència Artificial | RA4 | 7 |
| AEA5 | Operació Transformació Digital | RA6 + integració RA1–RA5 | 12 |
| | **TOTAL** | | **33** |

Progressió conceptual:

**Entendre → Connectar → Protegir → Explotar → Transformar**

Correspondència:

1. Digitalització → entendre
2. Cloud Computing → connectar
3. Ciberseguretat → protegir
4. Intel·ligència Artificial → explotar
5. Transformació Digital → transformar

AEA5 funcionarà com a activitat integradora/capstone.

---

# 4. CONVENCIÓ DE TEMPORITZACIÓ

S'ha diferenciat explícitament entre:

### Taula global d'AEA
Capçalera:

**Hores**

Valors sense unitat:

`5`, `6`, `3`, `7`, `12`

Total: `33`

### Taules internes de les guies didàctiques
Capçalera:

**Sessions**

També amb valors nus:

`1`, `1,5`, `2`, etc.

Si una activitat no forma part del còmput obligatori:

**Opcional**

No s'ha d'escriure "1 sessió" si la capçalera ja diu "Sessions".

---

# 5. PATRÓ COMÚ DE LES AEA

Els REA comparteixen una estructura narrativa que s'ha decidit conservar sempre que sigui útil:

- Operació/missió
- Full de ruta
- Pàgines conceptuals
- Activitats curtes
- Repte o activitat d'aplicació
- Revisió del LOG
- Credencial
- Guia didàctica

Terminologia acordada:

- **operació** → unitat/etapa narrativa
- **activitat** → tasca
- **repte** → només quan realment hi ha un repte
- **evidències** → produccions de l'alumnat
- **expert/a digital** → només com a element narratiu/credencial, no com a nivell acadèmic real ni titulació oficial

Evitar herències automàtiques com:

- desafío
- desafiament
- nivell d'expert
- certificat oficial
- títol d'expert

quan no corresponen realment al disseny.

---

# 6. LOG / EVIDÈNCIES

Inicialment es va plantejar utilitzar GitHub i fitxers `.md` per recollir totes les activitats.

Aquesta opció es va descartar perquè obligaria a reestructurar massa els REA.

Decisió actual:

**separar la navegació del REA de l'espai on es recullen les evidències.**

Per tant:

- activitats autocorrectives o de comprovació → poden quedar dins del REA;
- evidències individuals → es recullen al LOG;
- productes col·laboratius → poden quedar en eines externes, per exemple Padlet;
- no cal transformar totes les activitats en `.md`.

IMPORTANT:

S'ha decidit utilitzar **un únic fitxer/document on es recull el treball**, no necessàriament una carpeta física ni un `.md`.

Per tant, algunes referències a "carpeta d'aprenentatge" poden ser herència del REA, però la decisió funcional és treballar amb **un document únic**.

No s'ha de tornar a proposar GitHub `.md` com a solució per defecte.

---

# 7. CRITERI D'ADAPTACIÓ DE LES PÀGINES

S'està fent l'adaptació pàgina per pàgina.

Principi:

**traduir → contextualitzar només quan aporta valor → eliminar referències a activitats descartades → actualitzar informació obsoleta → conservar estructura i contingut quan funcionen.**

No és una reescriptura integral.

L'usuari prefereix anar "de cara a barraca": si una frase falla, donar directament una proposta concreta de substitució.

---

# 8. PRIORITAT ACTUAL DEL TREBALL

Ordre de treball acordat:

### Fase 1 — actual
Deixar **totes les AEA operatives en pàgines i en català**.

En aquesta fase el repàs és sobretot:

- lingüístic;
- terminològic;
- funcional;
- detecció de residus de l'original;
- incoherències evidents;
- dades clarament obsoletes.

NO fer encara una revisió pedagògica profunda de totes les AEA.

### Fase 2
Quan totes les AEA estiguin operatives:

Fer la **radiografia/revisió pedagògica** de cadascuna seguint el patró establert amb AEA1:

RA → CA → continguts → activitats → evidències → avaluació → temporització.

### Fase 3
Preparar materials globals del curs:

- fitxa/presentació inicial del curs;
- adaptació de la programació didàctica;
- full de seguiment del curs a partir d'una plantilla;
- preparació dels altres mòduls quan correspongui.

---

# 9. AEA1 — OPERACIÓ DIGITALITZACIÓ

## Estat

És l'AEA més desenvolupada i serveix com a **model metodològic per a les altres**.

Durada:

**5 h**

RA:

**RA1 + RA2**

### RA1

"Analitza el concepte de digitalització i la seva repercussió en els sectors productius tenint en compte l'activitat de l'empresa i identificant entorns IT i OT característics."

CA treballats:

- 1.1 descripció de digitalització
- 1.2 implantació de tecnologia digital i organització empresarial
- 1.3 diferències/similituds IT/OT
- 1.4 departaments típics IT
- 1.5 tecnologies típiques de digitalització de planta/negoci
- 1.6 importància de la connexió IT/OT
- 1.7 avantatges de digitalitzar l'empresa industrial extrem a extrem

### RA2

"Caracteritza les tecnologies habilitadores digitals necessàries per a l'adequació/transformació de les empreses a entorns digitals descrivint les seves característiques i aplicacions."

CA:

- 2.1 principals THD
- 2.2 THD relacionades amb productes/serveis
- 2.3 THD i economia sostenible/eficient
- 2.4 nous mercats
- 2.5 implicació de THD en negoci/planta
- 2.6 millores en IT/OT
- 2.7 informe tecnologia-característiques-àrees d'aplicació

---

# 10. AEA1 — ARQUITECTURA ACORDADA

Seqüència:

1. Contextualització breu del docent.
2. Itinerari autònom sobre digitalització + IT/OT.
3. Itinerari autònom sobre THD + comprovacions curtes.
4. Aplicació col·laborativa:
   **Experts en THD — casos d'ús**
5. IoT com a exemple de convergència.
6. Síntesi/evidència individual + LOG.

La documentació es conserva en gran part.

---

# 11. AEA1 — ACTIVITAT DE DIGITALITZACIÓ

Activitat:

**Com millora la digitalització les empreses?**

Es conserva.

Durada aproximada de l'activitat:

**20–30 minuts**

Casos:

- Shein
- IKEA

Shein permet observar:

- model fortament digital;
- dades en temps real;
- anàlisi de xarxes/competència;
- fabricació sota demanda;
- IA;
- programari propi per a proveïdors;
- reducció del temps de disseny a enviament;
- reducció de costos / millora de marges.

IKEA:

- eliminació del catàleg en paper;
- aposta pel canal digital;
- adquisició de Geomagical Labs;
- captura 3D d'espais;
- visualització;
- personalització de l'experiència;
- millores operatives.

Decisió important:

**NO forçar l'anàlisi IT/OT dins d'aquesta activitat.**

Shein permet alguna inferència, però OT no és prou explícit.

IKEA encara menys.

Aquesta activitat s'utilitza sobretot per:

- CA 1.1
- CA 1.2
- CA 1.7

Preguntes acordades per cada cas:

1. Quins àmbits o processos de l'empresa s'han digitalitzat? Identifica exemples concrets.
2. Com ha canviat la manera de funcionar de l'empresa?
3. Quins avantatges ha aportat?
4. Dels tipus estudiats —documents, processos, productes/serveis, comunicació, experiència del client— quins hi pots identificar? Justifica-ho breument.

Comparació final:

**Shein i IKEA han seguit el mateix procés de digitalització? Explica breument una diferència significativa entre les dues transformacions.**

Seqüència recomanada:

documentació digitalització
→ activitat autocorrectiva/classificació
→ Shein/IKEA
→ IT/OT
→ continuació del REA.

---

# 12. AEA1 — IT/OT

La documentació i activitat IT/OT:

**ES CONSERVEN.**

És un bloc curricularment nuclear.

Treballa especialment:

- CA 1.3
- CA 1.4
- CA 1.5
- CA 1.6

I prepara:

- CA 2.5
- CA 2.6

Es treballa mitjançant lectura/navegació autònoma, no mitjançant una classe magistral.

---

# 13. AEA1 — THD

La documentació sobre tecnologies habilitadores digitals:

**ES CONSERVA.**

Activitat:

**Hi són presents les THD?**

També es conserva, però com una activitat breu.

Organització:

- grups de 2–3;
- anàlisi de dos vídeos comuns;
- uns 30 minuts per a l'activitat pròpiament dita.

Funció:

reconeixement inicial de THD en casos reals.

Treballa principalment:

- CA 2.1
- potencialment 2.2
- 2.5
- 2.6

No cal convertir-la en un gran producte avaluable.

Seqüència:

**llegir THD → reconèixer THD en vídeos → analitzar un cas real al Padlet**

No fusionar aquesta activitat amb el Padlet.

---

# 14. AEA1 — IoT

Documentació:

**ES CONSERVA.**

Activitat específica:

**Analitzem l'IoT**

Decisió:

**opcional/reduïda.**

No ha de formar part obligatòriament de la nota ni de la rúbrica.

Funció conceptual de l'IoT:

mostrar la convergència:

**OT/sensor → dada → comunicació → IT/cloud → tractament → decisió/automatització**

CA relacionats:

- 1.5
- 1.6
- 2.2
- 2.5
- 2.6

No convertir IoT en una miniunitat tècnica.

---

# 15. AEA1 — REPTE ORIGINAL SUBSTITUÏT

Repte original:

**Divulgadores tecnológicos**

Durada original aproximada:

**4 sessions**

Decisió:

**ELIMINAT / REDISSENYAT RADICALMENT**

Substitut:

**Experts en THD — casos d'ús**

Format:

- treball en grup;
- Padlet;
- docent proporciona alguns enllaços amb diversos casos;
- cada grup escull un cas diferent;
- opcionalment poden cercar-ne un altre;
- no cal fer recerca oberta obligatòria;
- no hi ha presentacions llargues;
- es pot fer una breu consulta dels casos dels companys i una síntesi final.

Microinforme del Padlet:

- nom de la THD;
- característiques principals;
- empresa/cas/sector;
- problema o necessitat;
- aplicació de la THD;
- impacte en producte/servei/procés;
- beneficis;
- àmbit IT/OT/planta/negoci quan sigui pertinent;
- sostenibilitat/eficiència, si aplica;
- noves oportunitats, si aplica;
- font.

Es va analitzar com a possible font un document de Código Startup:

**"Casos de éxito de transformación digital"**, 27/07/2026.

Conté cinc casos empresarials amb estructura:

problema → solució → resultats mesurables.

És útil com a model, encara que no tots els casos corresponen netament a una única THD.

---

# 16. AEA1 — EVIDÈNCIA INDIVIDUAL

El Padlet és grupal, així que cal garantir evidència individual.

Proposta:

petit cas/situació en el LOG on l'alumne hagi de:

- identificar IT/OT;
- explicar-ne la connexió;
- seleccionar una THD adequada;
- justificar la contribució de la tecnologia.

Això permet mobilitzar una part important dels CA sense crear un altre gran projecte.

Els CA 2.3 i 2.4 són els més febles.

Per reforçar-los, el Padlet inclou camps opcionals/condicionals:

- sostenibilitat/eficiència;
- noves oportunitats.

---

# 17. AEA1 — TAULA INTERNA DE SESSIONS

Versió acordada:

| Tasques | Objectius | Sessions |
|---|---|---:|
| Activitat d'anàlisi: **Com millora la digitalització les empreses?** | Comprendre el concepte de digitalització, identificar-ne diferents tipus i analitzar el seu impacte en casos empresarials reals, introduint també la relació entre els entorns IT i OT. | 1,5 |
| Activitat d'anàlisi: **Hi són presents les THD?** | Conèixer les principals tecnologies habilitadores digitals i identificar-ne la presència i aplicació en casos reals. | 1,5 |
| Activitat d'investigació: **Analitzem l'IoT** | Comprendre l'IoT com a exemple de connexió entre dispositius, dades, processos i entorns IT/OT. | Opcional |
| **REPTE: Experts en THD** | Analitzar un cas real d'aplicació d'una THD, relacionant tecnologia, necessitat, àmbit d'aplicació i impacte en l'organització. | 2 |

Total obligatori:

**1,5 + 1,5 + 2 = 5 h**

L'activitat IoT opcional queda fora del còmput.

Eliminar qualsevol residual del tipus:

**"Repte integrador d'Operació Digitalització — 4 sessions"**

---

# 18. AEA1 — AVALUACIÓ

S'han plantejat tres instruments:

## 1. Rúbrica Operació Digitalització

4 aspectes × 3 punts = **12 punts**

Aspectes:

1. Comprensió i aplicació
2. Anàlisi de THD i casos d'ús
3. Treball autònom i col·laboratiu
4. Síntesi, documentació i presentació

La rúbrica avalua aprenentatge i produccions, no quantitat ni creativitat per si mateixes.

L'activitat opcional d'IoT NO s'ha d'esmentar a la rúbrica perquè s'ha de poder obtenir la màxima qualificació sense fer-la.

## 2. Checklist del LOG

Seccions:

- Registre i seguiment
- Documentació del treball
- Reflexió personal
- Organització, presentació i correcció

Inclou revisió/corrector ortogràfic.

## 3. Rúbrica del LOG

IMPORTANT: aquesta rúbrica és deliberadament de **10 punts**, no 12.

Distribució:

- Registre i seguiment → 3
- Documentació del treball → 3
- Reflexió personal → 2
- Organització, presentació i correcció → 2

Total:

**10 punts**

Les cel·les de 3 punts de les dues darreres files estan intencionadament buides/inexistents.

NO s'han de "corregir".

Motiu:

la reflexió i especialment els aspectes formals/presentació no han de pesar tant com les evidències principals.

---

# 19. AEA1 — PÀGINES JA ADAPTADES

S'ha treballat sobre diverses pàgines GitHub/HTML.

## `index.html`

Adaptat a català.

Inclou:

- introducció a la digitalització;
- IT/OT;
- THD;
- IoT com a convergència;
- Experts en THD com a activitat final.

Canvi terminològic:

**"Estructura de los recursos..." → "Estructura de l'itinerari de Digitalització"**

Les cinc operacions s'han fet coherents entre si.

Evitar nivells ficticis d'expert.

"expert/a digital" només com a narrativa de credencial.

## `hoja_de_ruta.html`

Canvi:

**"Full de ruta del projecte" → "Full de ruta de l'itinerari"**

Descripcions dels cinc punts del mapa adaptades.

Terminologia:

- desafío/reto genèric → operació
- repte → només repte real
- expert/a digital → només credencial narrativa
- activitat
- evidències

## `digitalizacin.html`

Adaptació conservadora.

Continguts:

- concepte i tipus de digitalització;
- documents;
- processos;
- productes/serveis;
- comunicació;
- experiència del client;
- avantatges;
- activitat autocorrectiva;
- IT/OT;
- comparació IT/OT;
- convergència;
- activitat Shein/IKEA.

L'activitat Shein/IKEA s'ha deixat curta i funcional.

No s'hi ha forçat IT/OT.

---

# 20. CRITERI DE REVISIÓ LINGÜÍSTICA

Per a les AEA que s'estan traduint ràpidament, el repàs actual ha de classificar els problemes en:

1. **Correcte tal com està**
2. **Calc/traducció automàtica poc natural**
3. **Residual de l'original**
4. **Correcció funcional/coherència necessària**
5. **Referència factual evidentment obsoleta**

No entrar en:

- redisseny del repte;
- reorganització dels RA;
- nova temporització detallada;
- reconstrucció de les rúbriques;

excepte si alguna cosa impedeix deixar el REA funcional.

---

# 21. AEA2 — OPERACIÓ CLOUD COMPUTING

Durada prevista:

**6 h**

RA principal:

**RA3**

Encara falta la radiografia pedagògica definitiva.

Principi ja acordat:

NO convertir-la en un segon mòdul tècnic d'ASIX.

Pregunta central:

**Per què una empresa trasllada processos al núvol i què canvia quan ho fa?**

Seqüència conceptual desitjada:

**situació empresarial → necessitat → decisió cloud → canvi/benefici → condicionants**

Conceptes que es poden conservar quan siguin rellevants:

- escalabilitat;
- disponibilitat;
- costos;
- treball distribuït;
- dades;
- dependència del proveïdor;
- seguretat;
- cloud;
- edge/fog/mist quan tinguin sentit empresarial.

Models de servei/desplegament:

explicar-los només amb la profunditat necessària per prendre decisions.

Evidència prevista:

donada una empresa/procés:

- decidir què traslladar al núvol;
- seleccionar un model adequat;
- justificar la decisió.

S'ha de reutilitzar fortament el material original.

Metodologia:

lectura/navegació autònoma del REA + checkpoints docents.

---

# 22. AEA3 — OPERACIÓ CIBERSEGURETAT

Durada prevista:

**3 h**

RA principal:

**RA5**

És deliberadament l'AEA més curta perquè ASIX Ciberseguretat ja treballa aquests continguts tècnicament en altres mòduls.

Objectiu de M1665:

NO ensenyar ciberseguretat tècnica en profunditat.

Pregunta central prevista:

**Quan una empresa digitalitza processos, connecta sistemes, treballa al núvol i explota dades, com canvia la seva superfície de risc i què ha d'incorporar la transformació digital?**

Materials que probablement es conservaran:

- Protecció de dades
- Cultura de ciberseguretat
- Pla Director de Seguretat

El REA original conté una seqüència molt més llarga:

- filtracions;
- campanya;
- ciberatacs;
- actius;
- anàlisi;
- repte;
- etc.

Decisió pedagògica provisional:

**reduir-la dràsticament** quan arribi la revisió pedagògica.

AEA3 ha de preparar AEA5.

---

# 23. AEA3 — REVISIÓ LINGÜÍSTICA/FUNCIONAL DETECTADA

Es va carregar una adaptació catalana completa amb pàgines com:

- `ataques_a_nuestra_empresa.html`
- `activos_crticos.html`
- `_crditos_y_descarga_.html`
- `index.html`
- `cultura_de_ciberseguridad.html`
- `reto_definiendo_nuestra_seguridad.html`
- `hoja_de_ruta.html`
- `_opina_sobre_el_recurso_.html`
- `anlisis_de_ciberataques.html`
- `proteccin_de_datos.html`
- `plan_director_de_seguridad.html`
- `index3.html`
- `analizamos_el_archivo_log.html`
- `completamos_nuestra_credencial.html`
- `_gua_didctica_.html`

Principals qüestions detectades:

### Global

"Analitzem l'Arxiu LOG" és una resta de l'original.

Pot ser més coherent:

**"Analitzem la carpeta d'aprenentatge (LOG)"**

o més curt:

**"Revisem el LOG"**

Però cal recordar la decisió posterior d'utilitzar un document únic.

La taula global d'`index.html` hauria d'utilitzar:

**Hores**

i no "Sessions".

### `index.html`

Possibles millores:

- "Per últim" → **"Finalment"**
- "elements ... importants de protegir" → **"elements ... que és important protegir"**
- "desafiament" → **"operació"** quan no sigui un repte real
- mantenir coherència entre "insígnia" i "credencial"

### `proteccin_de_datos.html`

Frase residual:

"Hem vist en el punt anterior que les dades són fonamentals..."

No funciona si la pàgina anterior és només el full de ruta.

Substitució suggerida:

**"Les dades són un actiu fonamental per a les empreses: contenen informació que pot ser explotada posteriorment i el seu accés ha d'estar controlat."**

Altres:

- "dos aspectes bàsics a definir" → **"dos aspectes bàsics que cal definir"**
- "Enfocant els esforços en tots dos" → **"Si actuem sobre tots dos aspectes..."**
- "tres paradigmes" → **"tres principis bàsics de la seguretat de la informació"**
- "versus" → **"en comparació amb"**
- "Se'ns ocorren mesures..." → **"Quines mesures de protecció podríem aplicar...?"**
- "programari malware" → **"programari maliciós (malware)"**
- "a nivell públic" → **"públicament"**
- "ocorren" → **"es produeixen"**

Problema funcional detectat:

els enllaços del PDF i l'iframe semblen utilitzar noms de fitxer diferents:

`cedec-Informe_filtraciones-operacion_ciberseguridad.pdf`

vs.

`Informe_filtraciones.pdf`

Cal verificar quin és el fitxer real i unificar-ho.

### `cultura_de_ciberseguridad.html`

Preferència:

**"cultura de ciberseguretat"**

i no "cultura en ciberseguretat".

Altres:

- "baluard" → **"element clau"**
- "en el nostre procedir" → **"en la nostra manera d'actuar"**
- "polítiques d'ús de contrasenyes" → **"polítiques de contrasenyes"**
- "creixement de teletreballadors" → **"augment del teletreball"**
- "en les seves labors quotidianes" → **"en la seva activitat quotidiana"**
- "Per últim" → **"Finalment"**

Paràgraf suggerit:

**"Per tant, la ciberseguretat ha de formar part del treball diari tant del personal que treballa a les instal·lacions com del que ho fa en remot. Això facilita la correcta implantació del Pla Director de Seguretat, que veurem en l'apartat següent, i contribueix a consolidar una cultura de ciberseguretat que protegeixi les dades de l'organització."**

### `plan_director_de_seguridad.html`

Frase problemàtica:

"A les grans empreses solen abordar inicialment aquestes situacions..."

Substitució:

**"Les grans empreses acostumen a integrar aquestes qüestions des de les fases inicials de la seva planificació, tot i que el grau d'implantació és desigual."**

Altres:

- "La redacció per a una empresa d'un PDS" → **"La redacció d'un PDS per a una empresa..."**
- "incidents ocorreguts" → **"incidents produïts"**
- "lleis i regulacions" → **"lleis i normatives"**

Final suggerit:

**"Per tant, és imprescindible formar el personal en pautes i comportaments adequats, consolidar una cultura de ciberseguretat i recollir els mecanismes i procediments necessaris en el Pla Director de Seguretat de l'empresa."**

I:

**"Hi aprofundirem a l'Operació Transformació Digital."**

### `ataques_a_nuestra_empresa.html`

Problemes de persona verbal.

Proposta:

**"Dividirem la classe en grups de tres."**

**"Atès que el nombre de ciberatacs és elevat, seleccionarem i repartirem entre els grups els que resultin més rellevants per al nostre sector. Cada grup n'analitzarà dos, intentant que el conjunt de la classe cobreixi els més significatius."**

També:

- "els grups haurem" → **"cada grup haurà"**
- "Cada grup presentarem" → **"Cada grup presentarà"**
- "el coneixement es traslladarà" → **"compartirem el coneixement amb la resta de la classe"**

### `activos_crticos.html`

- "assegurar el correcte funcionament empresarial" → **"garantir el bon funcionament de l'empresa"**
- "som empresaris d'una empresa" → **"treballem en una empresa del nostre sector o en som responsables"**

### `anlisis_de_ciberataques.html`

- "actius més importants a protegir" → **"actius més importants que cal protegir"**
- "ha estat encriptat" → **"ha estat xifrat"**
- "proporcionat el nostre usuari i la contrasenya" → **"facilitat el nom d'usuari i la contrasenya"**
- "pendrive" → **"memòria USB"**
- "arxiu adjunt" → **"fitxer adjunt"**
- "que poden ser la causa d'aquest atac" → **"que poden haver estat la causa d'aquests atacs"**

### `completamos_nuestra_credencial.html`

Problema conceptual/lingüístic:

"tercer nivell de Ciberseguretat"

No és un nivell de ciberseguretat.

Substitució:

**"Ja hem completat l'Operació Ciberseguretat, la tercera etapa del nostre itinerari de digitalització."**

Evitar "títol d'expert".

Preferible:

**"credencial d'expert o experta en digitalització"**

Altres:

- "nivells que ens atorguen les operacions" → **"insígnies associades a les operacions completades"**
- "portarem a terme" → **"durem a terme"**
- "descarregar en pdf" → **"descarregar en format PDF"**

### `_gua_didctica_.html`

Residual clar:

**"Itinerario" → "Itinerari"**

Però hi ha un problema molt més important que NO és lingüístic:

La guia mostra un RA5 i uns CA relacionats principalment amb:

- dades;
- Big Data;
- Machine Learning / IA;
- cloud;
- data science;

mentre que l'AEA està dedicada a ciberseguretat.

Això sembla una **incoherència curricular important**.

NO s'ha de corregir automàticament durant la fase lingüística.

Cal contrastar-ho amb el currículum oficial durant la revisió pedagògica.

També hi ha una temporització interna de:

**1 + 1 + 1 + 7 = 10 sessions**

però AEA3 només disposa de:

**3 h**

Això també queda pendent de la revisió pedagògica.

### `index3.html`

Sembla un fitxer auxiliar/orfe:

- `lang="en"`
- títol "Document"
- contingut generat/placeholder

Probablement no s'hauria de publicar ni navegar.

Cal revisar-ho quan es netegi l'estructura del REA.

---

# 24. AEA4 — OPERACIÓ INTEL·LIGÈNCIA ARTIFICIAL

Durada prevista:

**7 h**

RA principal:

**RA4**

Contingut original disponible:

- tipus d'IA;
- ML;
- DL;
- NLP;
- aplicacions;
- prompts / IA generativa;
- sinergies amb Big Data;
- IoT;
- Digital Twins;
- Blockchain;
- ètica;
- rols futurs.

El REA original ronda les 10 sessions.

Decisió pedagògica provisional:

reduir sobretot les activitats cares en temps.

Pregunta central:

**On pot aportar valor la IA, amb quines dades, amb quins beneficis i amb quins riscos?**

Prioritzar:

- anàlisi;
- presa de decisions;
- proposta;
- justificació;

per sobre de construir sistemes tècnics.

El treball de prompts pot ser:

**curt + pràctic + d'alt impacte**

Ètica:

integrar:

- biaix;
- privacitat;
- supervisió humana;
- riscos.

Possible solapament:

**SmartPyme** podria solapar-se amb AEA5.

Es va considerar repartir activitats diferents entre grups, però es va deixar aparcat perquè podria fragmentar massa la cobertura de RA4.

IMPORTANT per actualització factual:

Qualsevol referència a:

**"futura Ley Europea de IA"**

és obsoleta el 2026.

Cal actualitzar-la perquè l'AI Act ja no és una normativa futura.

---

# 25. AEA5 — OPERACIÓ TRANSFORMACIÓ DIGITAL

Durada prevista:

**12 h**

RA principal:

**RA6**

També ha d'integrar aprenentatges de:

- RA1
- RA2
- RA3
- RA4
- RA5

Funció:

**capstone / activitat integradora final**

No hauria de tornar a ensenyar des de zero:

- digitalització;
- THD;
- cloud;
- IA;
- ciberseguretat.

Ha d'utilitzar aquests aprenentatges com a inputs per resoldre una situació de transformació digital.

Materials originals:

- empresa / estratègia;
- digitalització;
- transformació;
- diagnosi;
- elements habilitadors;
- pla d'acció;
- seguiment.

Producte final previst:

un Canvas o equivalent amb sis blocs:

1. IT/OT
2. THD
3. Cloud
4. IA/automatització
5. Dades/Big Data
6. Ciberseguretat

AEA1–AEA4 han de generar evidències que després puguin reutilitzar-se a AEA5.

---

# 26. ESTAT DE L'ADAPTACIÓ LINGÜÍSTICA D'AEA5

Es va intentar adjuntar el fitxer:

**`REA5_ca.txt`**

diverses vegades.

El sistema mostrava l'adjunt, però en els intents de lectura no retornava el contingut complet/indexat de manera fiable.

Per aquest motiu:

**NO s'ha fet encara l'anàlisi lingüística d'AEA5.**

L'usuari va decidir aparcar-la temporalment.

Quan es reprengui:

fer exactament el mateix repàs ràpid que amb les altres AEA:

- català;
- terminologia;
- calcs;
- residus de castellà;
- coherència de denominacions;
- referències antigues;
- problemes funcionals evidents;

sense redissenyar encara pedagògicament AEA5.

Si l'adjunt continua fallant, la solució pràctica és enganxar el contingut de `REA5_ca.txt` directament al xat.

---

# 27. CODI / HTML

No s'ha desenvolupat una aplicació nova ni un sistema de programari específic.

El "codi" treballat és principalment:

- HTML dels REA;
- textos de pàgines GitHub Pages;
- navegació;
- metadades;
- etiquetes;
- contingut incrustat;
- enllaços;
- iframes;
- textos d'accessibilitat;
- taules de temporització.

La filosofia és:

**modificar el mínim HTML possible i actuar sobretot sobre el contingut textual i les referències que han quedat obsoletes.**

No s'ha acordat cap refactorització general de l'HTML.

S'han detectat alguns problemes funcionals puntuals:

- possible discrepància de noms de PDF a AEA3;
- `index3.html` probablement orfe;
- alguns textos incrustats en JSON/mapes poden continuar en castellà;
- missatge "Your browser is not compatible with this tool" en anglès;
- `.OCS` i noms de fitxer heretats de l'original.

Aquests últims no són prioritaris si no afecten l'ús.

---

# 28. LLICÈNCIA I ATRIBUCIÓ

Els REA originals provenen de:

**Proyecto EDIA / CEDEC**

Llicència:

**CC BY-SA 4.0**

Les adaptacions han de conservar:

- atribució;
- indicació de l'adaptació;
- mateixa llicència compatible.

A les pàgines de crèdits és correcte conservar noms oficials d'organismes en castellà quan són denominacions pròpies, per exemple:

**Centro Nacional de Desarrollo Curricular en Sistemas no Propietarios**

S'ha detectat en AEA3 que el `title` d'un enllaç al recurs original deia erròniament una cosa similar a "Enllaç al banc de rúbriques".

Millor:

**"Enllaç al recurs original. Obre en finestra nova."**

---

# 29. DECISIONS QUE NO S'HAN DE REOBRIR SENSE MOTIU

1. **33 h totals.**
2. Distribució:
   **5 + 6 + 3 + 7 + 12**
3. Cinc AEA corresponents als cinc REA.
4. AEA1 = RA1 + RA2.
5. AEA2 = RA3.
6. AEA3 = RA5.
7. AEA4 = RA4.
8. AEA5 = RA6 + integració.
9. Metodologia basada en navegació autònoma del REA.
10. No convertir els REA en classes magistrals.
11. Retallar activitats abans que documentació.
12. Màxima reutilització.
13. Un únic document/LOG per recollir evidències.
14. No migrar totes les activitats a `.md`.
15. AEA1 = 5 h.
16. "Analitzem l'IoT" és opcional.
17. "Divulgadores tecnológicos" queda substituït per "Experts en THD".
18. Padlet per als casos d'ús THD.
19. No forçar IT/OT en Shein/IKEA.
20. Rúbrica del LOG d'AEA1 = **10 punts**, deliberadament.
21. AEA3 = només 3 h i haurà de patir una reducció forta.
22. AEA5 = capstone de 12 h.
23. Primer acabar adaptació lingüística/operativa de totes les AEA; després revisió pedagògica.

---

# 30. PUNTS PENDENTS PRIORITARIS

## Curt termini

- Acabar les adaptacions lingüístiques de totes les AEA.
- Fer el repàs lingüístic d'AEA5 quan el contingut sigui accessible.
- Corregir residus clars de castellà/calcs.
- Corregir problemes funcionals evidents.
- Deixar totes les pàgines navegables i operatives.

## Després

Fer radiografia pedagògica de:

- AEA2
- AEA3
- AEA4
- AEA5

seguint el model d'AEA1.

Per cada AEA:

**RA → CA → pàgines → activitats → evidències → instruments d'avaluació → temporització**

## Especialment important

### AEA3
Contrastar RA5/CA de la guia amb el currículum oficial perquè hi ha una possible incoherència curricular greu.

Reduir la temporització original de 10 sessions a 3 h.

### AEA4
Actualitzar referències normatives obsoletes sobre l'AI Act.

Reduir activitats de 10 sessions a 7 h.

### AEA5
Fer-ne primer la revisió lingüística.

Després dissenyar-la com a capstone real de 12 h, evitant repetir AEA1–4.

---

# 31. CRITERI GENERAL PER A FUTURES DECISIONS

Quan hi hagi dubte entre conservar o modificar alguna part del REA:

1. Mirar quin RA/CA treballa.
2. Mirar si aporta una evidència necessària.
3. Mirar el cost temporal.
4. Mirar si duplica un altre mòdul d'ASIX.
5. Mirar si es pot mantenir com a lectura autònoma.
6. Retallar abans el producte/activitat que la documentació.
7. No afegir complexitat tècnica només perquè el perfil sigui ASIX.
8. Contextualitzar a ASIX/Ciberseguretat només quan millora realment el sentit de l'activitat.
9. AEA5 ha de reutilitzar aprenentatges previs en lloc de repetir-los.

Una activitat amb molta càrrega temporal i poca densitat curricular és candidata clara a:

- simplificació;
- integració;
- opcionalitat;
- substitució.

---

# 32. ESTIL DE TREBALL PREFERIT

Treballar en català.

Respostes:

- pràctiques;
- concretes;
- sense grans digressions teòriques;
- orientades a decisions;
- amb text de substitució quan hi ha una frase problemàtica.

No "posar-se massa creatiu" quan no és necessari.

L'objectiu és construir un mòdul:

- coherent;
- viable en 33 h;
- curricularment justificable;
- fàcil de gestionar;
- basat en material existent;
- amb el mínim manteniment possible.

Quan es revisa una pàgina lingüísticament, no convertir automàticament la revisió en una proposta de redisseny didàctic.

---

# 33. PUNT EXACTE ON ES VA DEIXAR EL FIL

L'última tasca prevista era:

**analitzar lingüísticament l'adaptació catalana d'AEA5 (`REA5_ca.txt`).**

El fitxer es va adjuntar diverses vegades, però no es va poder recuperar/indexar de manera fiable.

Per tant:

**AEA5 encara NO ha rebut el repàs lingüístic.**

Es va decidir deixar aquesta anàlisi per més endavant.

En reprendre el treball, una bona instrucció seria:

"Continuem des d'aquest estat. Et passo el contingut de REA5_ca.txt. Fes només el repàs lingüístic i funcional ràpid de l'AEA5, seguint el mateix criteri de les AEA anteriors i sense entrar encara en la revisió pedagògica."

Després d'això, quan totes les AEA siguin operatives, cal tornar a la **radiografia pedagògica RA/CA**, començant per les AEA que encara no s'han revisat en profunditat.

---

# CRITERI METODOLÒGIC GENERAL DE LES AEA

Les AEA1–AEA4 han de compartir un mateix patró de funcionament:

- predomini del **treball autònom de l’alumnat** a partir de la navegació i lectura dels REA;
- activitats curtes de **consolidació, comprovació o aplicació**;
- aquestes activitats poden ser individuals o, puntualment, en petit grup;
- les activitats intermèdies no han de convertir-se en grans lliuraments ni en tasques que bloquegin l’avanç de l’alumnat;
- sempre que sigui possible, les comprovacions autocorrectives o formatives han de permetre continuar avançant encara que l’alumne necessiti revisar algun contingut;
- el docent acompanya, contextualitza, resol dubtes, regula el ritme i fa síntesis o checkpoints breus;
- al final de cada AEA1–AEA4 hi haurà un **petit repte o activitat d’aplicació** que integri els aprenentatges principals de l’operació i generi una evidència més significativa.

Per tant, el patró general és:

**documentació autònoma → activitats breus de consolidació → petit repte final**

Les activitats de consolidació no han de competir en pes ni en temps amb el repte final.

## Paper específic de l’AEA5

L’AEA5 — **Operació Transformació Digital** — té una funció diferent.

No és simplement una cinquena AEA amb un petit repte final, sinó que constitueix el **repte global i integrador del mòdul**.

Per això:

- disposa de més temps: **12 h**;
- recupera i integra els aprenentatges de les AEA1–AEA4;
- no ha de tornar a ensenyar en profunditat continguts ja treballats;
- utilitza digitalització, IT/OT, THD, cloud, IA, dades i ciberseguretat com a recursos per prendre decisions;
- el treball principal consisteix a analitzar una empresa o situació i elaborar una proposta coherent de transformació digital;
- les evidències generades a les AEA1–AEA4 poden servir com a antecedents o inputs per al repte global.

Això explica també la distribució temporal del mòdul:

- AEA1–AEA4: adquisició, consolidació i petites aplicacions;
- AEA5: integració, presa de decisions i desenvolupament del repte global.

---

# DECISIÓ ESTRUCTURAL — VALIDACIÓ INDIVIDUAL DELS RA

S'ha decidit incorporar un mecanisme de **validació individual dels resultats d'aprenentatge (RA)**, independent de la qualificació obtinguda mitjançant les activitats i evidències de cada AEA.

Aquesta decisió condiciona:

- el disseny de les AEA;
- la temporització;
- la programació didàctica;
- els instruments d'avaluació;
- els mecanismes de recuperació;
- la informació que es proporcionarà a l'alumnat a l'inici del curs.

## Funció de la prova de validació

La qualificació de l'AEA s'obté a partir de:

- activitats de consolidació;
- evidències recollides al LOG/document d'aprenentatge;
- petits reptes o activitats d'aplicació.

La **prova de validació individual no té una ponderació pròpia en la nota**.

La seva funció és exclusivament comprovar que l'alumne ha assolit individualment els coneixements/aprenentatges essencials associats al RA.

Per tant, la prova pot registrar-se simplement com:

**Validat / No validat**

encara que internament s'estableixi un llindar d'encerts per determinar-ne la superació.

## Regla de qualificació

Si l'alumne **supera la validació individual**:

**Nota final = Nota de les activitats**

Si l'alumne **no supera la validació individual**:

**Nota final = mínim entre 4 i la Nota de les activitats**

Formalment:

-- (text) --
Si Validació = superada:
    Nota final = Nota activitats

Si Validació = no superada:
    Nota final = min(4, Nota activitats)
-- END (text) --

Exemples:

| Nota activitats | Validació | Nota resultant |
|---:|:---:|---:|
| 8,3 | Superada | 8,3 |
| 8,3 | No superada | 4,0 |
| 5,6 | No superada | 4,0 |
| 3,7 | No superada | 3,7 |
| 3,7 | Superada | 3,7 |

Això implica dues idees importants:

1. Una bona qualificació de les activitats no permet superar el RA si no se n'ha validat individualment l'assoliment.
2. Superar la validació tampoc no substitueix les activitats ni garanteix l'aprovat: si la nota de les activitats és inferior a 5, es conserva aquesta qualificació.

## Format de les validacions

Les validacions han de ser **breus, individuals i centrades exclusivament en els aprenentatges essencials**.

No es plantegen com a exàmens convencionals.

Format preferent:

- preguntes d'elecció múltiple;
- preguntes de resposta molt breu;
- respostes textuals d'una línia com a màxim;
- combinació dels formats anteriors.

Orientativament poden tenir:

- aproximadament 8–12 ítems;
- una durada aproximada de 10–15 minuts.

No és necessari incloure tots els CA de l'AEA a la prova. La resta d'evidències poden acreditar determinats CA.

Quan es faci la radiografia curricular de cada AEA caldrà determinar:

**RA → CA → evidència → instrument → necessitat o no de validació individual**

i identificar específicament quins aprenentatges essencials han d'aparèixer a la prova de validació.

## Impacte sobre el patró de les AEA1–AEA4

El patró metodològic general queda establert com:

**Treball autònom → activitats breus de consolidació → petit repte → validació individual breu**

Les activitats de consolidació:

- poden ser individuals o puntualment en grup;
- no han de bloquejar el progrés de l'alumnat;
- han de servir principalment per practicar, comprovar i consolidar;
- no s'han de convertir en grans lliuraments.

El petit repte final proporciona una evidència d'aplicació més significativa.

La validació individual confirma que cadascú ha assolit els aprenentatges essencials del RA.

## Cas específic de l'AEA5

L'AEA5 — **Operació Transformació Digital** — té una naturalesa diferent perquè constitueix el **repte global integrador del mòdul** i disposa de 12 hores.

Per tant, no s'ha de tractar necessàriament com una AEA1–AEA4 ampliada.

Caldrà definir durant el disseny definitiu d'AEA5 quin mecanisme de validació individual és més adequat, probablement vinculat al mateix repte global (per exemple, mitjançant una validació o defensa individual breu), evitant afegir una prova redundant si el mateix mecanisme permet acreditar individualment l'assoliment.

## Impacte en la temporització

IMPORTANT:

Les proves de validació formen part del temps disponible del mòdul i, per tant, **s'han de reservar dins de les hores assignades a cada AEA**.

No s'han d'afegir posteriorment per sobre de les 33 hores totals.

Distribució global que cal respectar:

- AEA1 — 5 h
- AEA2 — 6 h
- AEA3 — 3 h
- AEA4 — 7 h
- AEA5 — 12 h
- TOTAL — 33 h

Això serà especialment important en l'AEA3, que només disposa de 3 hores.

Quan es revisin les temporitzacions internes de cada AEA, caldrà reservar explícitament temps per a la validació sense superar aquestes hores.

## Impacte en la programació didàctica

La programació haurà d'explicitar com a mínim:

- que la qualificació procedeix de les activitats/evidències;
- que existeix una validació individual dels RA;
- que aquesta validació no pondera en la nota;
- que és necessari superar-la per validar l'assoliment;
- la regla `min(4, nota activitats)` quan no se supera;
- el procediment de recuperació de les validacions no superades;
- quines evidències i instruments s'utilitzen per a cada RA/CA.

El procediment concret de recuperació encara s'haurà de definir.

## Informació a l'alumnat

Aquest sistema s'ha d'explicar des de l'inici del curs de manera transparent.

L'alumnat ha d'entendre que:

**les activitats determinen la nota i la prova individual valida l'assoliment del RA.**

Per tant:

- fer totes les activitats no garanteix per si sol la superació del RA;
- la validació no serveix per apujar ni abaixar directament una nota ja obtinguda;
- si la validació se supera, es conserva la nota de les activitats;
- si no se supera, la qualificació queda limitada a un màxim de 4;
- superar la validació no compensa una nota insuficient en les activitats.

Aquesta informació haurà d'aparèixer tant a la programació com als materials inicials de presentació del mòdul.