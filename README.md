# Hey, I'm James Liu 👋

**Software Engineer | UC Irvine Computer Science '27**

I build full-stack applications and practical AI systems using TypeScript, React, Python, and AWS.

Currently developing AI applications at UCI Beall Applied Innovation, with experience in RAG, LLM evaluation, and systems optimization. Recent work reduced context tokens by 74% and p95 latency by 50% on a 40-turn benchmark.

Seeking full-time software engineering opportunities starting July 2027.

[![Portfolio](https://img.shields.io/badge/Portfolio-jam3sl1u.github.io-222?style=flat-square&logo=github)](https://jam3sl1u.github.io/portfolio/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-james--liu-0A66C2?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/james-liu-426a50281/)
[![Email](https://img.shields.io/badge/Email-jliuzhishun%40gmail.com-444?style=flat-square&logo=gmail&logoColor=white)](mailto:jliuzhishun@gmail.com)

## Current work

**Software Engineer, UCI Beall Applied Innovation**

I build AI applications in TypeScript and React on AWS. The work covers RAG over a Neo4j knowledge graph, DynamoDB and S3, LLM orchestration, and document ingestion with OCR and metadata generation, along with AI safety, evaluation, and context compaction.

These results are from a controlled 40-turn benchmark, not a production-wide measurement: 74% fewer context tokens, 50% lower p95 latency, and 100% anchor-fact recall. A safety-layer redesign uses rule-based checks for clear cases and parallel model checks for the rest, with under 0.1% false positives on an idiom and hyperbole evaluation suite.

## Featured projects

### [Chariot](https://github.com/Jam3sl1u/Chariot)

Solo. A Discord bot that coordinates weekly club rides, stores them in Google Sheets, and assigns drivers with a Saturday Apps Script job. More than one club uses it.

- Driver assignment is a deterministic pure function covering capacity, housing, distance, and church isolation. Each organization has its own data.
- Weekly posts and driver asks are skipped if they already went out for that week. Scheduled messages are claimed before sending, and missed jobs are caught up within the same week. The Apps Script job runs under a script lock.
- 100 automated tests passing. CI runs typecheck and tests.

### [Graceful](https://github.com/Jam3sl1u/Graceful) · [Live demo](https://graceful-wheat.vercel.app)

Scheduling, setlists, and music files for worship teams. Next.js, React, TypeScript, Supabase (Postgres with row-level security), Clerk, Zod, Jest, and Playwright.

- Invitations and conflict detection are complete.
- 3,233 unit tests passing across 153 suites.
- Every pull request runs typecheck, lint, a dependency audit, unit tests with coverage, and a full-history secret scan.

### [AI Calendar Assistant](https://github.com/Jam3sl1u/NLP-Calendar)

Four-person team. Turns a sentence into a structured calendar event. Next.js frontend, Flask server around a fine-tuned Flan-T5-Base model, with rule-based post-processing.

Team testing outside the repo: 1,430 generated training examples and a 500-example eval. Recurrence 95.6%, time 93.8%, date 32.2%. Date parsing is the open problem.

My part: the Flan and Claude API routes, date and time resolution, the app shell and events page, and the Jest route and live integration tests.

Write-ups live in the [portfolio repo](https://github.com/Jam3sl1u/portfolio).

## Skills

**Languages:** TypeScript, JavaScript, Python, Java, C++, SQL

**Frameworks:** React, Next.js, Node.js, Flask

**Data and cloud:** AWS (S3, DynamoDB), Neo4j, Supabase/Postgres

**Testing:** Jest, Playwright, GitHub Actions

**AI:** LLMs and RAG, OpenRouter

## GitHub

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=Jam3sl1u&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117" />
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api?username=Jam3sl1u&show_icons=true&theme=default&hide_border=true&bg_color=ffffff" />
  <img alt="GitHub stats for Jam3sl1u" height="165" src="https://github-readme-stats.vercel.app/api?username=Jam3sl1u&show_icons=true&theme=default&hide_border=true&bg_color=ffffff" />
</picture>

## Contact

[jliuzhishun@gmail.com](mailto:jliuzhishun@gmail.com)

Open to new-grad software engineering, full-stack, backend, and applied AI roles starting July 2027. Willing to relocate anywhere in the US.
