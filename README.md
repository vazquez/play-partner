# Play Partner

A Claude skill that turns Claude into a partner for exploration, not a vending machine for answers.

Most of the time we use AI to *exploit*: to collapse a question into the single fastest, most obvious answer. That is useful, and it is also a trap. It narrows you at the exact moment you had the most room to wander. Play Partner puts Claude in the other mode, *explore*, where its job is to widen the space, hand you more doors than you walked in with, and help you find the one worth opening.

The whole idea in one line: **diverge before you converge, and never converge for you, only with you.**

## What it does

When you bring Play Partner a problem, it runs a simple loop:

1. **Finds the why, and leaves it with you.** A quick question or two about what you are really trying to make possible. It surfaces your goal and hands it back. It never decides your direction for you.
2. **Diverges hard.** It generates many possibilities, past the point of comfort. Safe ones, strange ones, and a few frankly impossible ones, because the surprising idea usually hides behind the obvious ten.
3. **Suspends judgment while it diverges.** No ranking or hedging until the ideas have had room to breathe.
4. **Converges with you.** Once there is a real spread, it helps you notice which ideas pull at you, cluster them, and choose. The pick is always yours.

It works as a solo thinking partner, and it can facilitate a group session by framing the work as a Hero's Journey so a team has a shared story to play inside.

## From idea to build

When you land on something buildable, Play Partner can package the direction into a detailed brief you can paste straight into [Claude Code](https://www.anthropic.com/claude-code). You keep the *why* you worked to find. Claude Code carries the *how*. The brief leads with the core insight, the non-obvious angle that makes your idea different from the generic version, so the build keeps its point of view.

## Install

Download `play-partner.skill` and open it in Claude. When the file card appears, click **Save skill** to add it to your profile. After that, it activates on its own whenever you are exploring an open-ended problem.

You can also copy `SKILL.md` into your own skills setup if you prefer to manage skills manually.

## Use it

Just start where you already are. Play Partner is built to trigger without ceremony:

- "Help me think about ..."
- "Give me ideas for ..."
- "I'm stuck on ..."
- "I need a fresh angle on ..."

You do not have to say "brainstorm." If you seem to want more possibilities rather than one tidy answer, it shows up.

A short session looks like this: you name a rough idea, it asks what you actually care about, it hands you a wide spread of directions from several angles, you point at the one that pulls at you, it widens that further, and when you have converged it offers to write you a Claude Code brief.

## What's inside

```
play-partner/
├── SKILL.md      the skill itself: the instructions Claude reads
└── README.md     this file
```

Everything lives in `SKILL.md`. It is plain Markdown, so it is easy to read, fork, and adapt to your own voice.

## Where it came from

Play Partner began as a giveaway for a keynote on play and creativity, and the argument underneath the talk runs all the way through it. We are, by nature, systems that explore. Efficiency quietly trains us into systems that exploit. AI can push us further in either direction, and which one is a choice we get to make. This skill is that choice, made into a tool: a doorway back into play, not the door itself.

## License

Add your license of choice here (MIT is a common, permissive default).
