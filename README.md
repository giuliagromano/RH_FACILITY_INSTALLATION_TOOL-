# RH_FACILITY_INSTALLATION_TOOL
Il progetto consiste nella Prototipazione Virtuale del sistema di attrezzature ausiliarie che fungano da supporto agli operatori della RH Facility nella movimentazione dei moduli Inboard First Wall ed Outboard First Wall soddisfacendo determinati requisiti.
<div align="center">
  <img src="./media/RH_fac.jpg" alt="RH_facility" width="50%">
  <p><em>CIMA Reactions and Empirical Rate Laws</em></p>
</div>

La soluzione proposta è stata:
- modellata in **CATIA V5**
- sottoposta ad una analisi **FEM**
- **Simulazione cinematica** per il test di configurazioni critiche
- Analisi **ergonomica** tramite **Siemens Jack**
  
Il report completo è disponibile [qui](./PV2324_PROGETTO_PERFETTA-ROMANO.pdf).

## Idea
Per consentire l’accesso all’ambiente dei mockup, l’operatore può avvalersi di una passerella a cui è collegata una scala a castello. Mentre per manovrare in sicurezza i moduli IFW ed OFW, è stato realizzato un sistema costituito da un manipolatore allungabile con supporto mobile similare ad un manipolatore per vetri. 
<div align="center">
  <img src="./media/pass.jpg" alt="Passerella + Scala a Castello" width="50%">
  <p><em>Passerella + Scala a Castello</em></p>
</div>

<div align="center">
  <img src="./media/man.jpg" alt="Manipolatore con Supporto Mobile" width="50%">
  <p><em>Manipolatore con Supporto Mobile</em></p>
</div>

## Analisi FEM
### Passerella
La passerella è stata realizzata in Alluminio e, tramite l'analisi FEM, sono state verificate le specifiche richieste.
<div align="center">
  <img src="./media/Fem_Pass.jpg" alt="Analisi FEM - Passerella" width="50%">
  <p><em>Analisi FEM - Passerella</em></p>
</div>

### Scala
La scala è stata realizzata in Alluminio e, tramite l'analisi FEM, sono state verificate le specifiche richieste.
<div align="center">
  <img src="./media/Fem_Scala.jpg" alt="Analisi FEM - Scala" width="50%">
  <p><em>Analisi FEM - Scala</em></p>
</div>

### Manipolatore
Il Manipolatore è stato realizzato in Acciaio e, tramite l'analisi FEM, sono state verificate le specifiche richieste e sono state ricavate le infomazioni necessarie per modellare il cuscinetto assiale tra Supporto Mobile e Manipolatore.
<div align="center">
  <img src="./media/Fem_Manip.jpg" alt="Analisi FEM - Manipolatore" width="50%">
  <p><em>Analisi FEM - Manipolatore</em></p>
</div>

### Supporto Mobile con Manipolatore 
Il Supporto Mobile con Manipolatore è stato realizzato in Acciaio e, tramite l'analisi FEM, le specifiche richieste risultano soddisfatte.
<div align="center">
  <img src="./media/Fem_supp.jpg" alt="Analisi FEM - Supporto Mobile con Manipolatore " width="50%">
  <p><em>Analisi FEM - Supporto Mobile con Manipolatore </em></p>
</div>

## Analisi ergonomica 
L'analisi ergonomica è stata realizzata con il software Jack con l'utilizzo di modelli umani di default (uomo ed una donna caucasici del 50esimo percentile) con un avvitatore di 1.5 kg. In particolare sono state effettuate varie tipologie di analisi, di seguito è riportata i risultati del montaggio del modulo OFW in basso. 
Le coppie sulle vertebre L4/L5 rimangono al di sotto del valore critico 3400 N.
<div align="center">
  <img src="./media/jack_1.jpg" alt="Analisi in Jack - Coppie sulle vertebre L4/L5 " width="50%">
  <p><em>Analisi in Jack - Coppie sulle vertebre L4/L5  </em></p>
</div>
Gli angolo più critici sono raggiungibili dal 60esimo percentile della popolazione
<div align="center">
  <img src="./media/jack_2.jpg" alt="Analisi in Jack " width="50%">
  <p><em>Analisi in Jack  </em></p>
</div>
