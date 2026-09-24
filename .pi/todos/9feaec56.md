{
  "id": "9feaec56",
  "title": "FR stage C: review + repair + gates + container verify",
  "tags": [
    "i18n",
    "fr",
    "stage-C"
  ],
  "status": "completed",
  "created_at": "2026-09-11T15:57:24.360Z"
}

DONE except the open product question: reviewer verdict OK-with-notes, P1 (5× ungrammatical caveat) + P2s fixed in ae54753, doc drift corrected, gates green (2745/2743/1-known/1-skip, i18n 38/38, build ✓), env-pair verified live in Docker (FR|EN selector, full French UI, persistence). PENDING USER DECISION: navigator-vs-default precedence when GEV_DEFAULT_LOCALE is explicitly set (A keep / B default-wins / C auto-detect knob). Remaining after decision: implement if B/C, update PR description + CHANGELOG for fr/config story, final container rebuild.
