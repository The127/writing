# writing

How I want text in my projects to read: docs and READMEs, pull requests,
issues, commit messages, code comments and replies in discussions. Give it
to anyone, person or model, who writes for my projects.

The voice comes from my own writing from before AI tools: the READMEs of
FluentBlazorRouter and MScript, and part of a book I wrote. It also follows
Google's [developer documentation style guide](https://developers.google.com/style).

## For everything

Always write for the reader. Everything has to make sense to someone who
wasn't there.

- Write simple technical English with plain sentence structure.
- Don't use em dashes or semicolons.
- Say what changed and what it means for the reader. Leave out lore,
  narration and how we got there.
- Never mention AI: no reasoning, no thinking out loud, no links to AI
  sessions.
- Leave out what only made sense in the conversation: other repositories you
  looked at, ideas you dropped, names you made up along the way.
- Assume the reader comes in cold. Start with the problem in everyday words.
  A concrete example helps.
- Say what an internal name is before you use it.
- Keep to one topic. Leave out details nobody asked for. The reader can ask.
- Before you publish, read the text again as someone who wasn't there.

## Docs and READMEs

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

## Pull requests

A pull request description has three parts:

1. The problem, in everyday words.
2. What the change does about it.
3. What it doesn't do, and what wasn't tested.

Link the issue it closes. Say which docs you checked, also when none needed
a change. If the change adds something nobody asked for, say so plainly and
ask. Don't hide it in the description.

Don't be verbose. Saying "I read the docs and nothing needs to be changed" 
(for example) when it's obvious is an example of being verbose.

## Issues

- Start with the problem: what goes wrong, for whom, and when. Paste the
  error if there is one.
- Point to the code that is involved.
- List what is still to decide, as questions.
- End with "Done when", so everyone knows when the issue can close.

## Commit messages

- Use Conventional Commits: `feat:`, `fix:`, `docs:`, `chore:` and so on.
- Sign off every commit with `git commit -s`.
- Say what changed and why, for someone who reads the history later.
- Don't link to an AI session, and don't add a `Co-Authored-By` line for an
  AI (unless the project specifically has differing guidelines).

## Code comments

- Comment the why, never the what. When code needs a comment to say what it
  does, rename or restructure it instead.
- Exported names get their doc comment.
- A why is something the code can't show, like a quirk of a protocol or a
  limit from outside.

## Discussions and updates

When you answer in an issue or lay out options, keep it short:

- what it's about
- the trade-off
- your recommendation
- one question

A few bullets beat sections with sub-bullets.

## Diagrams

- Leave the bottom right of a Mermaid diagram empty, because GitHub draws its
  zoom buttons there. In a sequence diagram, turn off the actors at the bottom
  with `%%{init: {"sequence": {"mirrorActors": false}}}%%`.
- Spread the arrows apart so they don't meet in one point.
- Check the diagram on GitHub itself, in the light and the dark theme.
