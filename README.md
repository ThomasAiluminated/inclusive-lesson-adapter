# Inclusive Lesson Adapter

**Een Claude-skill die bestaand lesmateriaal toegankelijker maakt, zonder het leerdoel te verlagen.**

Je plakt een tekst, werkblad, opdracht of toets en vertelt welke leerlingen je hebt, en je krijgt een aangepaste versie terug volgens Universal Design for Learning (UDL), plus concrete aanpassingen voor bijvoorbeeld dyslexie, ADHD, autisme of anderstalige nieuwkomers.

🇬🇧 [English version](README.en.md) · 📄 [Voorbeelden](examples/)

*English summary: a Claude skill that adapts existing lesson materials, texts, assignments and tests using Universal Design for Learning, with targeted adjustments for neurodivergent learners and language learners, without lowering the learning objective. It works in Dutch, French and English.*

## Wat de skill doet

- **Beschermt het leerdoel.** Eerst wordt benoemd wat het materiaal moet leren of toetsen; alles daarbuiten mag aangepast worden.
- **Zoekt de drempels** in het materiaal: lange instructies, te moeilijke tekst, onverklaarde vaktermen, geen voorbeeld van een goed antwoord, maar één manier om te antwoorden.
- **Past eerst aan voor iedereen (UDL):** heldere structuur, één instructie per regel, een woordenlijst, een uitgewerkt voorbeeld, keuze in hoe je toont wat je kan. Zo zet je niemand apart.
- **Voegt daarna gerichte aanpassingen toe**, alleen voor noden die je noemt.
- **Spreekt over drempels, niet over labels**, en raadt aan aanpassingen af te stemmen met de leerling en het zorgteam.
- **Volgt je context:** redelijke aanpassingen en STICORDI (Vlaanderen), passend onderwijs (Nederland), aménagements raisonnables (Franstalig).

## Wat je terugkrijgt

1. **Leerdoel**: wat intact moet blijven
2. **Gevonden drempels**
3. **Aangepast materiaal**, klaar voor gebruik
4. **Gerichte aanpassingen** per genoemde nood
5. **Notities**: wat bewust níet is aangepast, en waarom

## Voor wie

Voor leerkrachten, zorgcoördinatoren, docenten en trainers die hun materiaal inclusiever willen maken voor een diverse groep.

Deze skill hoort bij **[Claude Skills for Education](https://github.com/ThomasAiluminated/claude-skills-for-education)**, een open reeks voor onderwijs en L&D:
- [Edu Prompt Coach](https://github.com/ThomasAiluminated/edu-prompt-coach): prompts voor leerkrachten, met uitleg waarom ze werken
- [Lesson Designer](https://github.com/ThomasAiluminated/lesson-designer): lessen ontwerpen van leerdoel tot exit-check
- [Rubric Builder](https://github.com/ThomasAiluminated/rubric-builder): beoordelingsrubrics met observeerbare niveaus
- [Assessment Item Writer](https://github.com/ThomasAiluminated/assessment-item-writer): toets- en examenvragen met sleutel en feedback
- [Feedback Writer](https://github.com/ThomasAiluminated/feedback-writer): specifieke, haalbare feedback op leerlingenwerk
- [Learning Program Designer](https://github.com/ThomasAiluminated/learning-program-designer): opleidingen en leertrajecten ontwerpen
- [Prompt Architect](https://github.com/ThomasAiluminated/prompt-architect): een ruwe vraag omzetten in een sterke prompt voor Claude

## Installeren

**In Claude (web, desktop of mobiel):**
1. Download [`inclusive-lesson-adapter.skill`](inclusive-lesson-adapter.skill)
2. Upload het bij de Skills in je Claude-instellingen
   (of open het bestand in een gesprek met Claude en klik op *Save skill*)

**In Claude Code:** kopieer de map `inclusive-lesson-adapter/` naar `~/.claude/skills/`.

Daarna volstaat een gewone vraag, zoals *"maak dit werkblad toegankelijk voor twee leerlingen met dyslexie en een anderstalige nieuwkomer"*. De skill start vanzelf.

## Structuur

```
inclusive-lesson-adapter/
└── SKILL.md                       # de volledige instructies van de skill
examples/                          # voorbeelden van input en output
inclusive-lesson-adapter.skill     # installeerbaar pakket
```

## Bijdragen

Ideeën en verbeteringen zijn welkom via een issue of pull request.

## Licentie

[CC BY 4.0](LICENSE): vrij te gebruiken, aan te passen en te delen, met naamsvermelding.

---

Gemaakt door **Thomas Donvil**, [Ailuminated](https://ailuminated.org), AI-geletterdheid voor het onderwijs.
