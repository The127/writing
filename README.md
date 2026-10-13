# docs-voice

How I want docs and READMEs to read. It comes from my own writing from
before AI tools: the READMEs of FluentBlazorRouter and MScript, and part of
a book I wrote. Give it to anyone, person or model, who writes docs for my
projects.

## The voice

- Open with what it is and the problem it solves. Then say how it solves it.
- Talk to "you". Give instructions plainly: "Add one of these to `env`".
- Use active voice and the present tense. Put the condition before the
  instruction: "If you use Nix, install it with ...".
- Keep sentences short and words everyday. Contractions are fine.
- Write "Claude Code's login", not "the login of Claude Code".
- Put steps in order with "First", "Then" and "Finally". Put a caveat right
  after its step, as "Note that ...".
- Show the code first, then say in a line or two what it does.

## What makes text feel generated

Avoid these:

- chains of "of": "the folder of the tasks of the project"
- the same shapes again and again, like "X, since Y" or a sentence that
  starts with "So"
- bold lead-ins on bullets
- a list where a paragraph would do
- stiff verbs, like "lets through" or "dials"

## Rules for all prose

These hold for docs, READMEs, pull request descriptions, commit messages and
code comments:

- Simple technical English with plain sentence structure.
- No em dashes and no semicolons.
- No lore, no narration, no reasoning about how we got there.
- Write for the reader: what changed and what it means for them.
- Before you publish, read the text again as someone who wasn't there.
