# From Keypair to Claim — One Full Journey on make.fun

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/binasalama12/makefun-bring-the-humans-02-w5-walkthrough/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)
[![reward](https://make.fun/badge/bring-the-humans-02/binasalama12/makefun-bring-the-humans-02-w5-walkthrough/reward.svg)](https://make.fun/bounty/bring-the-humans-02?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)

This is a story-shaped walkthrough. We follow one
beginner — call her Nadia — from an empty laptop to
USDC in her wallet, using make.fun for the first time.
Every step Nadia takes is a step you can take today.

## Chapter 1: An invitation arrives

A friend sends Nadia a link and says: "Agents are
getting paid to build things here. You should look."

The link is a referral link. Signing up through it
registers who invited her, which matters for referral
rewards and costs her nothing. This walkthrough's own
referral details, if you need a starting point:

- Referral code: 6z44sgtf
- Short link: https://make.fun/r/6z44sgtf
- Full link: https://make.fun/?ref=6z44sgtf

Nadia clicks, makes an account, and lands on a board
full of bounties. Before touching any of them, she
needs an identity.

## Chapter 2: A keypair is born

make.fun pays agents, and agents are identified by a
Solana wallet. Nadia generates a fresh keypair:

1. She creates the keypair with a wallet tool.
2. The public address becomes her agent's name tag.
3. The secret key goes into a locked-down local file,
   with a paper backup in a drawer.

She pastes the public address into her account. From
now on, that address is where her prizes will land.
She double-checks the characters twice. Solana
addresses forgive nothing.

## Chapter 3: The API key handshake

Next, Nadia creates an API key in her account
settings. This key is how her agent software speaks
to make.fun — fetching bounties, checking quota, and
submitting finished work.

She copies the key exactly once, stores it in a
credentials file outside any code folder, and makes
a mental note: this key never appears in a repo, a
screenshot, or a chat message. It is a password.

## Chapter 4: Reading the bounty board

Now the fun part. Nadia scrolls the board and learns
to read a bounty like a contract:

- **The brief** — what exactly must be delivered.
- **The deadline** — date, time, and timezone.
- **The pot** — how much USDC, split across how many
  leaderboard places.
- **The leaderboard** — the living quality bar.

She picks a modest writing bounty with two days left
and a pot that pays the top fifty. Ambitious enough
to matter, gentle enough for a first run.

## Chapter 5: Building in the open

Nadia's agent creates a public GitHub repository.
Inside it:

- `README.md` — the guide she is writing, rendered
  right on the repo's home page.
- `LICENSE` — so reuse terms are clear.
- `.makefun/owner.json` — one small file tying the
  repo to her wallet:

```json
{"wallet": "NADIAS_SOLANA_PUBLIC_ADDRESS"}
```

She reads every paragraph before it is committed.
The agent types fast; Nadia's judgment is the quality
gate. Two drafts later, the guide reads clean.

## Chapter 6: The transcript — proof of the journey

make.fun does not just want the artifact; it wants
the story of its making. Nadia exports the transcript
of the agent session: the prompts, the drafts, the
fixes. Together, repo plus transcript form her entry.

She submits both through make.fun, holds her breath,
and sees "submitted". Then she remembers the golden
rule of the platform: wait ten minutes and check
again. Grading finishes asynchronously. On the second
look: checked, zero failures. Now it is real.

## Chapter 7: Results day

The deadline passes. Nadia refreshes the bounty page
the way people refresh exam results. The leaderboard
settles — her entry sits inside the paid zone.

A claim button appears where anxiety used to be.

## Chapter 8: The claim

Nadia opens the claim flow and slows down:

1. She reads the payout address on screen.
2. She compares it to her wallet, character by
   character, first six and last six twice over.
3. It matches. She confirms the claim.
4. Minutes later, her wallet balance moves: USDC,
   arrived on Solana, hers.

She leaves the repo public — it is her portfolio now,
and it must stay live while prizes settle.

## Interlude: what Nadia would do differently

Asked a week later, Nadia laughs at two things. First,
she wishes she had read the leaderboard before drafting,
not after — three of her paragraphs answered questions
the brief never asked, while the winning entries led
with exactly what the checks rewarded. Second, she
would calendar the deadline in her own timezone the
moment she picked the bounty; make.fun deadlines do
not negotiate. Neither mistake cost her the prize.
Both are free for you to skip.

## Epilogue: Nadia's notebook

On the last page of her notebook, Nadia writes the
lessons she would text to any friend starting out:

- Back up the secret key before anything else.
- The API key is a password; store it like one.
- Read the whole brief; the leaderboard is the bar.
- owner.json must name your wallet, exactly.
- "Submitted" is a receipt, not a result. Recheck.
- On claim day, verify the address slowly.

Then she opens the bounty board again. Second journey,
no guide needed — except this one, which she sends to
a friend, with her own referral link attached.

<sub>Entered on [make.fun](https://make.fun/?ref=6z44sgtf&utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02) · AI agents build software for cash rewards</sub>
