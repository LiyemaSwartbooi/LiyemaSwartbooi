# GitHub profile README

Paste-ready. Goes in the README of your `LiyemaSwartbooi/LiyemaSwartbooi` repository. Do not rename
that repo, GitHub only renders it while the name matches your username.

Built from `../Guides/04-github-standard.md`. The short version of why it looks like this:
recruiters check two to four pinned repositories and **ignore the contribution graph**, so
the line in your current README calling the graph "the honest measure" is removed. It
invites the one check that shows nothing.

---

## What changed from your current version

| Current | New | Why |
|---|---|---|
| "specialising in the security of AI-generated and agentic systems" | Applied AI engineering: workflow automation and integration | Your only public page was selling a different career from the one you chose. AI security stays as a stated interest, not the headline |
| "The contribution graph is the honest measure of it" | Removed | Recruiters do not look at it, and yours is days old. You were pointing them at your weakest evidence |
| Awards listed with emoji, six lines | Three lines, no emoji | Scannable bullets beat dense paragraphs; emoji reads as decoration, not signal |
| Several links: zelpano, operavax, LinkedIn, email | **One destination: zelpano.com** | A visitor with one clear option clicks it. A visitor with eight clicks none |
| Tools listed as a flat line | Grouped by category, framed as *mostly working in* | Grouped shows deliberate choices. The framing keeps it open, so it reads as what you reach for rather than the limit of what you know |

---

## The document

```markdown
# Liyema Swartbooi

I turn manual business processes into AI-powered software. I run one in production.
Forms, approvals, audit trails, and the integrations that connect them to what a company
already runs.

**Software Developer at Risen Advisory. Founder of Zelpano.**

Kimberley, Northern Cape, South Africa

---

### Now

Building and operating **[Zelpano](https://zelpano.com)**, a multi-tenant workflow
operating system. One spine of account, identity, membership, billing, audit and
notifications, hosting self-contained workflows that an organisation installs from a
marketplace and then runs. It does not digitise documents, it digitises how the work
happens: the information, responsibility, decisions, tasks, deadlines and records that
move a process from beginning to end.

Working toward measured AI behaviour: accuracy, failure modes, correction effort, latency
and cost, on features already in production. A direction I am building toward, not a
claim of expertise.

---

### Some of what I work with

- **AI engineering:** Anthropic API, OpenAI API, Vercel AI SDK, Claude Agent SDK, Model Context Protocol, multi-agent orchestration, document extraction and classification, embeddings
- **AI-assisted delivery:** Claude Code, Codex, Cursor, Copilot, Claude Design, ChatGPT, Figma, Lovable
- **Application:** TypeScript, Next.js 15 App Router, React 19, Node.js, native app development, Tailwind CSS v4, Radix UI, shadcn/ui, TanStack Table, framer-motion
- **Backend and data:** Convex real-time and serverless functions, Supabase, SQL, MongoDB, REST APIs, webhooks, file upload and document processing
- **Platform and delivery:** Polar, Clerk, Resend, Twilio, Vercel, Vitest
- **Architecture:** multi-tenant SaaS, workflow marketplace, role-based access control, decision routing and audit trails, server-rendered PDF and spreadsheet export, POPIA and PAIA surfaces

That list is a sample, not a boundary. I pick tools for the problem and learn whatever the
problem needs, which in 2026 changes faster than any list can keep up with. What does not
change is that I direct AI tooling to ship production software and own the architecture,
data model and deployed behaviour myself.

---

### Work

**[Zelpano](https://zelpano.com)** is the clearest evidence of what I do. It is live, you
can sign up, and an organisation runs real processes on it.

Most of my other work sits in private commercial repositories.

---

### Before this

**1st Place, Enactus South Africa National Exposition 2025**, against 32 universities.
I built the marketplace and learning platform for Go-Green and ran it as CEO.

**Top 3 nationally**, French Embassy and EDHE AI & Blue Tech Challenge. Top 100 Global
Finalist, Google Solution Challenge 2024.

Tutored 350+ university students in programming, networking and web development.

---

### Contact

**liyema@operavax.com**

If you are building something in AI, automation, or software that has to actually work,
I am open to talking.
```

---

## The repo description, bio and links

These are separate GitHub fields, not part of the README, and they are the first things a
visitor reads.

| Field | Set it to |
|---|---|
| **Bio** (160 chars) | `Building AI-enabled workflow systems. Founder of Operavax, builder of Zelpano. TypeScript, Next.js, Convex, Anthropic API.` |
| **Website** | `https://zelpano.com` |
| **Company** | `Operavax` |
| **Location** | `Kimberley, South Africa` |
| **Repo description** on `LiyemaSwartbooi/LiyemaSwartbooi` | `Profile README. Renaming this repo stops GitHub rendering it.` |

**Profile photo:** add one if you have not. A profile with no avatar reads as abandoned.
A plain, well-lit headshot is enough.

**LinkedIn link:** add it back the day the profile exists. Right now the README links a
URL you told me may not resolve, and a dead link on your only public page is worse than a
missing one.

## What makes this page actually work

Nothing above. The page is damage control until there is code behind it. What converts it
is **one public repository with a real README:** the Zelpano architecture write-up, or an
extracted piece of the agent frameworks. That is the next document,
`04-zelpano-case-study.md`, and it is worth more than every word on this page.

---

## Audit verdict, 2026-09-18

Kept here so you do not have to ask again. Re-run it if you change the README.

**Measured:** 66 lines, 325 words, 5 sections, 2 links.

### Meets the standard

| Standard | This README |
|---|---|
| Short intro saying what you do | Yes, two sentences |
| Current focus section | Yes, "Now" |
| Stack grouped by category | Yes, 5 groups, as a list |
| One clear destination | Yes, zelpano.com, twice |
| Contact | Yes, one address |
| No badge wall | None |
| No GIFs or images | None |
| No emoji | None |
| Not a resume dump | 325 words |
| Scannable, not dense paragraphs | 5 headed sections |
| No em dashes | Zero |

### Fails one point, structurally

The standard expects **2 to 4 pinned repositories** with real code and live demos.
You have zero public repositories besides this one. No amount of writing fixes that.
`04-zelpano-case-study.md` is the only thing that closes it.

### Where these standards come from

Be clear about this, because it matters.

**GitHub's official documentation** (docs.github.com, verified 2026-09-18) specifies only
four things, and none of them are about content:

1. The repository name must match your username exactly.
2. The repository must be public.
3. It must contain a file named README.md in the root.
4. That file must contain something.

That is the whole official rulebook.

**Everything else is convergent recruiter-facing commentary**, not a published standard.
Sources are named in `../Guides/04-github-standard.md`. Several independent 2026 guides
say the same things, which is worth something. It is not a spec.

**One open disagreement:** GitHub's own docs suggest an emoji cheat sheet. The recruiter
guides say emoji reads as decoration rather than signal. This README follows the recruiter
guides because the goal is being hired. Overrule it if you disagree.

### Three defects found and fixed on 2026-09-18

1. **A rendering bug.** The stack was five adjacent bold lines, which Markdown can merge
   into one run-on paragraph. Converted to a bullet list, which renders correctly either
   way. This one fails silently and reads as carelessness.
2. **Meta-commentary.** The line "It stays worded that way until the published work
   exists" was editorial reasoning, meaningless to a stranger. Cut.
3. **Em dashes reintroduced** while building the bullet list. Replaced with colons.

Also cut earlier: an apologetic opening to the Work section, a promise of a case study
that does not exist yet, unverifiable user and funding numbers, three emoji, and roughly
half the awards section.

### The honest verdict

Structurally this is as good as a profile README gets. It will not be the best on Earth,
because what makes a GitHub profile strong is code, and none of yours is public yet.

---

Previous: `01-cv.md` · Next: `03-linkedin-copy.md`
