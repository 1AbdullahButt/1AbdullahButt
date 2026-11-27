### Hi, I'm Abdullah 👋

**I find bugs in AI tooling and send the fixes upstream.** 76 pull requests merged across 48 projects so far, including 13 at Microsoft and others at Google, NVIDIA, Grafana, Tauri and a2a. I also build AI products end to end, from the voice input to the database.

Before this I worked in fintech operations, building integrations that saved staff hours every workday. **Open to remote AI Product Engineer roles.**

[LinkedIn](https://www.linkedin.com/in/mabdullahbutt/) · **Follow me here** to see what I fix next.

---

### Recent fixes upstream

- [pipecat-ai/pipecat#6999](https://github.com/pipecat-ai/pipecat/pull/6999): FunctionFilter ran its filter on frames it was meant to pass straight through
- [collabora/WhisperLive#576](https://github.com/collabora/WhisperLive/pull/576): the client kept showing a stale partial segment after it was completed
- [NVIDIA/ccluster#306](https://github.com/NVIDIA/ccluster/pull/306): `register` dropped the context's TLS server name from the saved credentials
- [google/adk-go#2342](https://github.com/google/adk-go/pull/2342): the logging plugin cut text by bytes and could split a character in half; it now cuts by character
- [grafana/grafana#136705](https://github.com/grafana/grafana/pull/136705): ad hoc filters stopped working after a reload in panels with expressions
- [a2aproject/a2a-python#1460](https://github.com/a2aproject/a2a-python/pull/1460): a streaming send now fails clearly when the agent produces no events
- [tauri-apps/tauri#16521](https://github.com/tauri-apps/tauri/pull/16521): `tauri migrate` rejected a package version inherited from the workspace
- [shaka-project/shaka-player#10937](https://github.com/shaka-project/shaka-player/pull/10937): HLS AES-128 decryption broke once the media sequence number passed 2^31

Also: 7 merged in [microsoft/TokenEconomizer](https://github.com/microsoft/TokenEconomizer/pulls?q=is%3Apr+author%3A1AbdullahButt+is%3Amerged), 6 in [microsoft/SkillOpt](https://github.com/microsoft/SkillOpt/pulls?q=is%3Apr+author%3A1AbdullahButt+is%3Amerged), and [more](https://github.com/search?q=author%3A1AbdullahButt+is%3Apr+is%3Amerged+-user%3A1AbdullahButt&type=pullrequests). Each one comes with a regression test. I've also reviewed 200+ pull requests, in google/adk-python, langchain, haystack, microsoft/agent-framework and voice AI projects such as pipecat, livekit/agents and speechbrain.

---

### What I've built

| Project | What it does | Built with |
|---|---|---|
| **[WhatsApp, AWS and n8n agents](https://github.com/1AbdullahButt/whatsapp-aws-n8n-agents)** (demo) | WhatsApp maintenance desk (text and voice notes, human handoff) and an invoice-reading agent, run on real WhatsApp and AWS: Lambda, SQS with dead-letter queues, DynamoDB. 99/108 invoice fields correct on synthetic PDFs | FastAPI · AWS SAM · n8n · WhatsApp Cloud API |
| **[Stoke](https://github.com/1AbdullahButt/stoke-showcase)** | Voice-first nutrition tracker: say a whole meal in one sentence and get editable entries with macros | Expo · Supabase · Groq Whisper |
| **[Fathom AI](https://github.com/1AbdullahButt/fathom-ai)** ([live demo](https://fathom-ai-tau.vercel.app)) | Meeting notes with no meeting bot. Every summary point links to the transcript quote it came from | Next.js · Supabase · AssemblyAI · Groq |
| **[LendLoop](https://github.com/1AbdullahButt/lendloop)** ([live demo](https://lendloop-demo.vercel.app)) | Neighbourhood tool-lending board with role-based access, masked personal data and signed, retried n8n notifications | Next.js · Clerk · Convex · n8n |
| **[SureSend](https://github.com/1AbdullahButt/suresend)** ([live demo](https://suresend-demo.vercel.app)) | Holds a support reply that contradicts the team's newest docs and offers the safe reply instead, before it reaches the customer | Next.js · TypeScript |
| **[MeowPay](https://github.com/1AbdullahButt/meowpay)** | Fintech prototype (for cats) with atomic transfers; passes all 25 checks in a black-box grader | FastAPI · SQLite |
| **[AI Voice Orders](https://github.com/1AbdullahButt/AI-Voice-Order-Management)** | Calls customers, transcribes the reply, works out what they want and updates the order | Flask · Twilio · Whisper · GPT-4o |

---

**Stack:** Python · TypeScript · SQL · React Native/Expo · Next.js · FastAPI · Supabase/Postgres · OpenAI · Groq · n8n · Playwright · GitHub Actions · Claude Code
