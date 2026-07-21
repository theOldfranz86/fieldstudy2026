# Istruzioni di repository

## Finalità

Mantieni questo repository come fonte operativa per il corso **Field Study 2 – Application**. Il corso conduce i gruppi dal brief di Maison Maye alla raccolta qualitativa, alla costruzione del questionario quantitativo, all'analisi integrata e alla comunicazione orale di raccomandazioni evidence-based.

## Gerarchia delle fonti

1. `COURSE_SPEC.yaml` definisce identità, risultati di apprendimento, formato didattico e disegno metodologico.
2. `COURSE_SCHEDULE.yaml` definisce calendario e sequenza settimanale.
3. `MILESTONES.yaml` definisce consegne, checkpoint, soglie di qualità e azioni di recupero.
4. `ASSESSMENT_SPEC.yaml` definisce prove e requisiti valutativi.
5. `curriculum/PEDAGOGICAL_FRAMEWORK.md` definisce il quadro pedagogico.
6. I file in `curriculum/`, `project-management/`, `evaluation/` e `teaching-materials/` concretizzano tali specifiche.

In caso di conflitto, aggiorna prima la fonte di livello superiore e poi propaga la modifica ai file dipendenti. Lo scaffold locale è autorevole rispetto a versioni remote precedenti; la pubblicazione Git avviene soltanto dopo i controlli di coerenza.

## Decisioni stabili del corso

- 12 sessioni da 180 minuti, in francese.
- Formato: breve briefing/apporto metodologico, workshop, lavoro di progetto e coaching.
- Disegno sequenziale: ricerca qualitativa → sintesi tracciabile → questionario quantitativo → Sphinx → analisi integrata.
- Almeno un'intervista qualitativa per studente, quindi almeno 38 interviste complessive.
- Almeno 300 risposte quantitative complete utilizzabili per lo studio; il campione analitico finale è dichiarato dopo il controllo qualità.
- Nessun rapporto scritto valutato: output sommativo di gruppo esclusivamente orale, sostenuto da portfolio di evidenze e recommendation package.
- `A1_GROUP_ORAL` 50%, `A2_INDIVIDUAL_EXAM` 50%, `A3_PROJECT_PROCESS` 0% e formative only.

## Protocollo di modifica

- Leggi `COURSE_CONTEXT.md` e le quattro specifiche YAML prima di modificare la progettazione didattica.
- Mantieni invariati gli identificativi: `LO01`–`LO06`, `W01`–`W12`, `M01`–`M04`, `A1_GROUP_ORAL`, `A2_INDIVIDUAL_EXAM`, `A3_PROJECT_PROCESS`.
- Registra una data solo dopo conferma; usa `null` o `TBD` per informazioni non disponibili.
- Allinea ogni attività, consegna e criterio di valutazione ad almeno un learning outcome.
- Non introdurre requisiti istituzionali, etici, logistici o valutativi non confermati.
- Non inventare informazioni sul problema manageriale di Maison Maye prima del brief del 22.09.2026.
- Non generare un PPTX prima che i cinque file settimanali siano completi e revisionati: `SESSION_PLAN.md`, `SLIDE_BRIEF.md`, `COACHING_GUIDE.md`, `DELIVERABLE.md`, `QUALITY_CHECKLIST.md`.

## Controlli minimi

- Verifica che ogni riferimento a LO, W, M e A esista nella specifica pertinente.
- Verifica che i pesi valutativi certificativi sommino a 100; escludi A3 dal totale.
- Verifica che `due_week` e `due_date` di ogni milestone coincidano con `COURSE_SCHEDULE.yaml`.
- Verifica che ogni milestone abbia output osservabili, quality gate e risposta per i gruppi a rischio.
- Verifica la tracciabilità evidenza qualitativa → item del questionario → variabile Sphinx → analisi → raccomandazione.
- Mantieni i materiali didattici nominati con il prefisso della settimana, per esempio `W03-desk-research`.
