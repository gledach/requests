# requests

The intake queue for [gledach](https://gledach.de), a shelf of free tools that each watch
something public and hand back an answer.

Five of twelve slots are filled. This repository is where the next one gets argued for. It
holds no code. Every issue here is a request, a decision on a request, or the note saying
why a request cannot be built.

## Ask for a tool

**[Open a request](https://github.com/gledach/requests/issues/new?template=tool-request.yml)**

The form asks three questions:

1. What do you check by hand today, and how often?
2. Where is it published? A URL, even a bad one.
3. Does seeing it need an account?

They are not paperwork. They are the three questions that decide whether anything is
watchable at all, and they are the same ones
[signal-patterns](https://github.com/gledach/signal-patterns) puts to every source it
evaluates. A request that answers them can be judged in a minute. A request that cannot is
usually asking for something no tool can see, and hearing that quickly is more use to you
than a polite maybe.

No GitHub account? Send the same three answers to `request@gledach.de`. Anything worth
building gets filed here afterwards, so the queue stays public either way.

## How a request is handled

| Label | What it means |
|---|---|
| `watchable` | The source exists, it is public, and a tool could read it |
| `needs a source` | Nobody has named where this is published yet |
| `not watchable` | The thing is real and no public source carries it. Closed, with the reason |
| `on the shelf` | Built. The issue links to the repository and the preview |

A request that would help more people than the person asking is built first. That is the
only prioritisation rule there is, and this list is how you check whether it was followed.

Nothing here is a commitment to a date. There is no roadmap to quote, deliberately, which
is the same reason the site carries an empty slot card instead of a plan.

## Bugs in a tool that already exists

Those go on that tool's own repository, not here:
[signals](https://github.com/gledach/signals/issues),
[whenrun](https://github.com/gledach/whenrun/issues),
[phonehome](https://github.com/gledach/phonehome/issues),
[recall](https://github.com/gledach/recall/issues).

## The shelf

| Tool | Watches | Tells you |
|---|---|---|
| [signal](https://github.com/gledach/signals) | Thirteen public sources around whichever market you name | What changed, scored and attributed, over MCP |
| [signal-patterns](https://github.com/gledach/signal-patterns) | Nothing. It is the written reasoning | What is watchable, what it costs, how to build it |
| [whenrun](https://github.com/gledach/whenrun) | Day-ahead power prices and renewable share | The cheapest or greenest window, then starts the job in it |
| [phonehome](https://github.com/gledach/phonehome) | Every DNS query on your own network | Which device talked where, and when that changed |
| [recall](https://github.com/gledach/recall) | Four public registers, against a list of what you own | Which of your things has a notice, and how sure the match is |

Every tool is free, MIT licensed, runs on your own machine, needs no account to start, and
ships a written audit of what it cannot see. The figures and those audits are on
[gledach.de](https://gledach.de).
