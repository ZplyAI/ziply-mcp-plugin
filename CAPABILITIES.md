# What the Ziply plugin can do

The Ziply plugin connects Claude and ChatGPT to your Ziply workspace. The assistant reads your
brand context and topic queue from Ziply, writes content in your brand's voice, and saves it to
Ziply Content Factory as a draft for your team to review. It never publishes anything.

## Before you start

- **Ziply plan:** Growth or Scale, with an active subscription. On other plans the plugin
  connects but tells you the connector isn't included.
- **Your Ziply account:** the first time you use the plugin, sign in with your Ziply account and
  allow access. The assistant then sees only your own company's data.
- **Where it works:**
  - **Claude:** chat (web, desktop, mobile), Cowork and Claude Code.
  - **ChatGPT:** Work and Codex in the ChatGPT desktop app.

## What you can ask for

| Ask | What you get |
|---|---|
| "Is Ziply connected?" | Your company, plan, brand and connected blog sites, and what you can do |
| "What should we write next?" | Topics from your Ziply queue, highest opportunity score first, with where each came from: sales conversations, media and market intelligence, AI-visibility gaps or your team's plans |
| "Brief me on this topic." | Why the topic matters, its audience, pillar and clusters, key insights and data points, source links, competitive angles, keywords and journey stage, and drafts already written from it |
| "Write a blog post on it." | A blog post, landing page, pillar page, cluster page or eBook in your brand's voice, built from the topic's evidence |
| "Turn it into LinkedIn and X posts." | Posts for LinkedIn, X, Facebook, Instagram and YouTube, two versions per channel unless you ask for more |
| "Start a Reddit discussion on this." | A new Reddit post for your brand's profile or a community your team takes part in |
| "Write it in our CEO's voice." | Content in the voice of a person whose digital twin is set up in Ziply, after you confirm the person |
| "Save it to Ziply." | A new draft in Content Factory with its tags, topic link and sources, and a link to open it |

### Commands

In Claude Cowork and Claude Code you can also type these:

| Command | Does |
|---|---|
| `/ziply:status` | Checks the connection and summarises your workspace |
| `/ziply:topics` | Recommends what to write next |
| `/ziply:brief <topic>` | Builds a research brief |
| `/ziply:social <idea>` | Writes social posts |
| `/ziply:reddit <idea>` | Starts a Reddit discussion |
| `/ziply:push` | Saves the content in the conversation to Ziply |

## What the assistant reads from Ziply

| Ziply data | Used for |
|---|---|
| Company: plan, brand, connected blog sites | Checking the connection |
| Brand profile: about, brand voice, differentiators, market position, offerings, restrictions | Writing on-brand; prohibited words and excluded topics are always respected |
| Buyer personas (B2B and B2C) | Writing for a specific audience |
| Authority pillars and content clusters | Choosing topics and tagging drafts |
| Competitors, and brands AI engines mention alongside yours | Positioning and comparison content |
| Digital twins: a person's voice guide, sample passages and voice profile | Writing in that person's voice |
| Topic queue and topic briefs | Deciding what to write and grounding it in evidence |

## What it saves to Ziply

- **Content types:** blog posts, pages (landing, pillar or cluster), eBooks, and social posts
  grouped by channel, with one or more versions per channel.
- **Social channels:** LinkedIn, X, Facebook, Instagram, YouTube and Reddit.
- **Saved with the draft:** title, body, pillars, clusters, personas, offerings, use cases, journey
  stage, digital twin, topic link (blogs and social posts), source links, and SEO details (blogs and
  pages).
- **Status:** always In-Progress. Nothing is sent for review or published; your team does that in
  Ziply.
- **Channel limits it writes to:** LinkedIn 3,000 characters; X 280 for a standard post (up to 25,000
  for a long post if you ask); Instagram caption 2,200; YouTube title 100 and description 5,000;
  Reddit title 300.

## Safeguards

- **Nothing invented:** no statistics, customers, quotes, credentials or sources that Ziply or you
  didn't provide. Empty fields in Ziply are left empty.
- **It asks before saving:** it shows what will be saved and waits for your confirmation, and
  checks that the content holds no internal figures or quotes from your own buyers.
- **It asks before writing as a person:** a named person's voice is used only with their digital
  twin and your confirmation.
- **Brainstormed ideas are labelled:** suggestions that aren't in your Ziply topic queue are shown
  separately.
- **Reddit stays honest:** posts state the poster's affiliation with the brand, go only to
  communities your team takes part in, and are never repeated across communities.

## Not in this release

- AI-readiness scores and checks
- Updating or refreshing a draft already in Ziply (it saves new drafts only)
- Reading content already saved in Ziply, or your Ziply library files
- Buyer questions and how buyers phrase them
- Uploading images or video (add them in Ziply)
- Subreddit and flair on Reddit drafts (set them when publishing from Ziply)
- Publishing
