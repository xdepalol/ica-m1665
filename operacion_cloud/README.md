# Esquema general

| Sessió | Fil de la sessió | Organització en viu |
| --- | --- | --- |
| **S1 — La dada com a motor** | **Dada → informació → valor → on la gestionem?** | **Inici breu:** partir de dades quotidianes d'una empresa i diferenciar dada d'informació. **15–20'** _Detectiu de la dada_: emmagatzematge → processament → ús. Continuar amb local vs. cloud i activitats autocorrectives. **15'** _El Big Data en acció_: dades → anàlisi → decisió/millora. **Tancament:** connectar Big Data i cloud: quan les dades creixen en volum, velocitat i varietat, necessitem capacitat per emmagatzemar-les i processar-les. |
| **S2 — Arquitectura Cloud** | **Quan enviem una dada al núvol, què li passa?** | **Inici:** desmuntar la idea del cloud com un lloc abstracte. Revisar infraestructura bàsica: dispositiu → xarxa → centres de dades. **10–15'** _El viatge de les dades_: representar el recorregut d'una dada concreta. Continuar amb cloud distribuït: Edge, Fog i Mist. Activitat autocorrectiva de casos. **Tancament:** no tot s'ha de processar necessàriament al mateix lloc; la latència i la necessitat de resposta condicionen on processem les dades. |
| **S3 — Cloud com a estratègia** | **No existeix “el cloud”: què necessitem i quin servei ens convé?** | **Inici:** distingir dues decisions: model de servei (SaaS/PaaS/IaaS) i tipus de cloud (públic/privat/híbrid/multicloud). **20–30'** _Explorem els serveis d'un proveïdor cloud_: localitzar serveis reals i analitzar-ne un. **Posada en comú:** comparar serveis sobretot per la necessitat que resolen, no per memoritzar catàlegs. **Tancament:** servei cloud → necessitat empresarial → model → forma de tarifació. |
| **S4 — Repte: entendre abans de proposar** | **Com treballa l'empresa ara? → què necessita millorar?** | Parelles, un dels quatre casos. **Fase 1:** sintetitzar empresa, dades i gestió actual. **Fase 2:** seleccionar 2–4 dades/informacions rellevants i identificar ús → problema/necessitat → possible millora. Si avancen bé, iniciar Fase 3. **Tancament:** abans de parlar de tecnologia, ha de quedar clar quin problema volem resoldre. |
| **S5 — Repte: construir la proposta cloud** | **Necessitat → servei → infraestructura → adopció** | Continuar el repte. **Fase 3:** 1–2 solucions cloud justificades i model SaaS/PaaS/IaaS. **Fase 4:** públic/privat/híbrid/multicloud + valorar si alguna dada necessita processament proper a l'origen. **Fase 5:** tres accions prioritàries d'adopció + risc/dificultat. **Final:** revisar la coherència de tota la cadena, no només completar taules. |
| **S6 — Tancament de l'operació** | **Què hem après? → què puc demostrar individualment?** | **Metacognició:** reconstruir el recorregut global de l'operació. **Validació individual:** comprovar els aprenentatges essencials del RA3. La revisió docent posterior del LOG no consumeix aquesta sessió. |

Això encaixa amb les activitats efectivament conservades al REA: S1 concentra _Detectiu de la dada_ i _Big Data en acció_; S2 _El viatge de les dades_; S3 l'exploració d'un proveïdor; i S4–S5 el repte. AEA2

# Referència ràpida

## S1 — La dada com a motor

**Dada → informació → decisió**

Activació:

-   Quines dades genera una empresa durant un dia normal?
-   Una dada sola ens diu alguna cosa?
-   Quan es converteix una dada en informació útil?
-   Per què una empresa voldria conservar aquestes dades?
-   Què en pot fer després?

Durant / després de _Detectiu de la dada_:

-   On guardaríem aquesta dada?
-   Què hauríem de fer amb ella perquè fos útil?
-   Quina decisió podria prendre l'empresa gràcies a aquesta informació?
-   La gestionaríem localment o al núvol? Per què?

L'activitat està construïda precisament sobre `dada → emmagatzematge → processament → ús`, i acaba fent triar una dada que seria útil gestionar al núvol. AEA2

Big Data:

-   Què canvia quan ja no tenim unes poques dades sinó milions?
-   Què signifiquen volum, velocitat i varietat en un cas real?
-   De què serveix analitzar totes aquestes dades?
-   Quina decisió o millora obtenim?

Estructura: **dades → processament/anàlisi → informació → decisió**

Idea clau: **les dades tenen valor quan les transformem en informació útil.**

---

## S2 — Arquitectura Cloud

**Què passa realment quan enviem una dada “al núvol”?**

Activació:

-   Quan pugem un fitxer al núvol, on va?
-   El cloud és realment una cosa “virtual”?
-   Quins elements necessita perquè jo pugui accedir a una dada des del mòbil?

Durant _El viatge de les dades_:

-   On es genera?
-   Per quin dispositiu entra al sistema?
-   Com arriba al cloud?
-   On s'emmagatzema o processa?
-   Com torna aquesta informació a l'usuari?
-   Quin avantatge obtenim fent aquest recorregut?

Estructura: **origen/dispositiu → xarxa → infraestructura cloud → emmagatzematge/processament → ús**. És exactament el recorregut que demana l'activitat. AEA2

Edge / Fog / Mist:

-   Cal enviar sempre totes les dades fins al cloud?
-   Què passa si necessitem una resposta immediata?
-   Què guanyem processant una dada més a prop d'on es genera?
-   En aquest cas, on té sentit processar-la?

Idea clau: **on processem les dades depèn de què necessitem fer amb elles**, especialment de latència, volum i necessitat de resposta. El REA introdueix Edge, Fog i Mist justament com a capes que apropen el processament a l'origen. AEA2

---

## S3 — Cloud com a estratègia

**Què necessita l'empresa? → quin servei li dona resposta?**

Activació:

-   Quan diem que una empresa “utilitza el cloud”, què està contractant realment?
-   És el mateix utilitzar Gmail que llogar un servidor virtual?
-   Qui gestiona què en cada cas?
-   Per què una empresa voldria més control? I per què voldria delegar-lo?

Dues decisions diferents:

**Què contractem? → SaaS / PaaS / IaaS**  
**Com despleguem? → públic / privat / híbrid / multicloud**

Durant _Explorem els serveis_:

-   Què ofereix realment aquest servei?
-   Quina necessitat empresarial resol?
-   Amb quin model el relacionem?
-   Com cobra el proveïdor?
-   Estem escollint tecnologia perquè és coneguda o perquè resol una necessitat?

L'activitat real posa el focus precisament en servei concret → funció → necessitat → model → tarifació. AEA2

Idea clau: **no escollim “cloud”; escollim una solució adequada a una necessitat.**

---

## S4 — Repte: diagnosticar

**Primer entendre. Després proposar.**

Activació del repte:

-   Com treballa aquesta empresa actualment?
-   Quines dades són importants per al seu negoci?
-   On són aquestes dades?
-   Com es mouen?
-   On apareixen dificultats?

Fase 1:  
**empresa → activitat → dades → gestió actual**

Fase 2:

-   Per a què serveix aquesta dada?
-   Quin problema hi ha ara?
-   És un problema d'accés? actualització? dispersió? protecció? creixement?
-   Què voldríem que pogués fer l'empresa que ara no pot fer bé?

Estructura:  
**dada/informació → ús actual → problema o necessitat → millora esperada**

Important: **encara no començar per AWS/Azure/Nextcloud/etc.** Primer necessitat, després solució. Les dues primeres fases del repte estan construïdes expressament així. AEA2

---

## S5 — Repte: proposar

**Necessitat → solució → model → infraestructura → adopció**

Fase 3:

-   Quina necessitat prioritària volem resoldre?
-   Quin servei li dona resposta?
-   SaaS, PaaS o IaaS?
-   Per què aquest i no un altre?

Fase 4:

-   Públic, privat, híbrid o multicloud?
-   Què guanyem amb aquesta elecció?
-   Quin inconvenient o risc assumim?
-   Totes les dades han d'anar al cloud?
-   N'hi ha alguna que necessiti resposta immediata i convingui processar més a prop?

Fase 5:

-   Per on començaria l'empresa?
-   Què faria primer? I després?
-   Per què aquest ordre?
-   Quin problema podria aparèixer durant l'adopció?
-   Com l'afrontaríem?

Revisió final potent:  
**El problema que havíem detectat al principi queda realment resolt per la proposta que hem acabat fent?**

El repte tanca exactament aquesta cadena: necessitats → serveis → tipus de cloud → possible processament proper a l'origen → tres accions d'adopció i risc. AEA2

---

## S6 — Metacognició i validació

Per reconstruir l'operació:

-   Com passa una dada a convertir-se en informació útil?
-   Per què ens pot interessar gestionar-la al cloud?
-   Què passa físicament quan la dada viatja al núvol?
-   Per què no sempre convé processar-ho tot al cloud?
-   Quina diferència hi ha entre SaaS, PaaS i IaaS?
-   Quina diferència hi ha entre escollir un servei i escollir un tipus de cloud?
-   Què hauríem de mirar abans de recomanar una solució cloud a una empresa?

Fil final:

**dada → informació → necessitat → infraestructura/processament → servei cloud → tipus de cloud → valor per a l'empresa**