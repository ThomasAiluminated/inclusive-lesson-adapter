# Inclusive Lesson Adapter

**A Claude skill that makes existing lesson materials more accessible, without lowering the learning objective.**

🇧🇪 [Nederlandstalige versie](README.md) · 📄 [Examples](examples/)

Paste a text, worksheet, assignment or test and describe your learners, and get an adapted version based on Universal Design for Learning (UDL), plus concrete adjustments for, for example, dyslexia, ADHD, autism or language learners.

It works in English, Dutch and French: it replies in the language you write in.

## What the skill does

- **Protects the objective:** names what the material must teach or assess, and adapts everything else.
- **Finds the barriers:** long instructions, dense text, unexplained terms, no model answer, only one way to respond.
- **Adapts for everyone first (UDL)**, so no learner is singled out.
- **Then adds targeted adjustments**, only for needs the teacher mentions.
- **Talks about barriers, not labels**, and recommends checking adjustments with the learner and support team.

## What you get

1. **Objective** to keep intact
2. **Barriers found**
3. **Adapted material**, ready to use
4. **Targeted adjustments** per need
5. **Notes** on what was deliberately not changed

See [examples/](examples/) for a full input and output.

## Who it's for

Teachers, special-needs coordinators, lecturers and trainers who want inclusive materials for diverse groups.

This skill is part of **[Claude Skills for Education](https://github.com/ThomasAiluminated/claude-skills-for-education)**, an open collection for education and L&D:
- [Edu Prompt Coach](https://github.com/ThomasAiluminated/edu-prompt-coach): ready-to-paste prompts for teachers, with the pedagogy behind them
- [Lesson Designer](https://github.com/ThomasAiluminated/lesson-designer): lessons designed from objective to exit check
- [Rubric Builder](https://github.com/ThomasAiluminated/rubric-builder): assessment rubrics with observable levels
- [Assessment Item Writer](https://github.com/ThomasAiluminated/assessment-item-writer): test and exam questions with answer key and feedback
- [Feedback Writer](https://github.com/ThomasAiluminated/feedback-writer): specific, actionable feedback on student work
- [Learning Program Designer](https://github.com/ThomasAiluminated/learning-program-designer): training programs and learning journeys
- [Prompt Architect](https://github.com/ThomasAiluminated/prompt-architect): rough requests turned into strong prompts for Claude

## Install

**In Claude (web, desktop or mobile):**
1. Download [`inclusive-lesson-adapter.skill`](inclusive-lesson-adapter.skill)
2. Upload it under Skills in your Claude settings
   (or open the file in a Claude conversation and click *Save skill*)

**In Claude Code:** copy the `inclusive-lesson-adapter/` folder to `~/.claude/skills/`.

Then just ask, for example *"make this worksheet accessible for two learners with dyslexia and a newcomer learning Dutch"*. The skill starts automatically.

## Contributing

Ideas and improvements are welcome via an issue or pull request.

## License

[CC BY 4.0](LICENSE): free to use, adapt and share, with attribution.

---

Made by **Thomas Donvil**, [Ailuminated](https://ailuminated.org), AI literacy for education.
