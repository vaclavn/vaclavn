## Václav Novotný

Founder at [Headers](https://headers.cz) and part-time CTO at GoPay, a payment
provider, where I have spent the last seven years.

The work in both places is the same: building AI-native teams. Not bolting an
assistant onto an existing process, but changing how a team works once agents are
part of it - what gets written down and where, who checks what, which decisions
stay with people, and how you tell whether any of it is actually working.

Client work lives in private repositories, so this profile stays quiet. My own
time goes into a second brain I have been keeping for years, and into the layer
that now lets an agent work inside it.

The notes came first and would exist either way. Agents only sharpened the
question: what does a knowledge base have to look like when something other than
me reads and writes it? That layer is mostly unglamorous. Memory that survives
between sessions. Task state that is true whether I touched it from the phone or
an agent touched it at 3am. Notes written during the work instead of after it.

Most of the interesting part turns out to be measurement rather than building:

- I parsed 1,732 of my own session transcripts to find out which tools the agent
  actually reaches for. One integration I had installed since January had been
  called exactly once. Another was costing ~3k tokens of context in every
  session, whether I needed it or not.
- The task API I use daily returns roughly eight times more data than an agent
  needs, and accepts an invalid date with `201 Created`. A quarter of my task
  records carried the string "Invalid date" before I noticed.

None of that shows up in a demo. It shows up on day forty.

I read whatever is written from practice rather than from a launch - Karpathy
among others. Interested in agentic workflows, how people actually work with
these systems, and where the time really goes.

Based in České Budějovice, Czech Republic.
[vaclav.novotny@headers.cz](mailto:vaclav.novotny@headers.cz)
