# ThriftyFig: agent skills by task

A curated list for people choosing a skill for a concrete job: extracting a PDF, reviewing a diff, making a short video or analyzing a CSV. These entries are **Listed public-repo skills** in the [ThriftyFig catalog](https://thriftyfig.pages.dev/), with links to both the source and a catalog page.

Browse [all 1,030 skills](https://thriftyfig.pages.dev/skills/), [25 topic pages](https://thriftyfig.pages.dev/topics/) or [the guide to finding agent skills](https://thriftyfig.pages.dev/tasks/find-agent-skills/). Tool support varies; a listing here does not mean that every skill works in every Claude, Cursor or other agent environment.

## How this list is selected

Task relevance comes first. Within each shortlist, entries with a stated license are preferred, then parent-repository stars and last-push recency from the existing repository snapshot (November 11, 2026). A useful specialist can still earn a place ahead of a popular general-purpose skill. The sections below are organized for reading rather than presented as a quality ranking.

Stars and last-push dates belong to the **parent GitHub repository** and are shared by every skill in that repository. They do not measure an individual skill’s quality. Catalog pages show those signals and the recorded license; inspect the upstream license and requirements yourself. ThriftyFig curates public data and does not claim to have run, installed or benchmarked these skills. It is independent of Anthropic, Cursor and the source authors.

## Contents

- [PDF extraction and conversion](#pdf-extraction-and-conversion)
- [Word, slides and documents](#word-slides-and-documents)
- [Coding and code review](#coding-and-code-review)
- [Video and subtitles](#video-and-subtitles)
- [Audio, voiceover and transcription](#audio-voiceover-and-transcription)
- [Data analysis and CSV](#data-analysis-and-csv)
- [Writing and reports](#writing-and-reports)
- [Testing](#testing)
- [DevOps and deployment](#devops-and-deployment)
- [Security review](#security-review)
- [Visual design and illustrations](#visual-design-and-illustrations)

## PDF extraction and conversion

Related: [Claude PDF skills for extraction, OCR and file workflows](https://thriftyfig.pages.dev/topics/claude-skills-for-pdf/) · [Claude skills for PDF to Markdown](https://thriftyfig.pages.dev/topics/claude-pdf-to-markdown/) · [Extract usable content from PDFs](https://thriftyfig.pages.dev/tasks/pdf-extract/) · [Extract data from PDFs with AI](https://thriftyfig.pages.dev/tasks/extract-data-from-pdfs/).

- [Pdf](https://thriftyfig.pages.dev/skills/pdf/) — Work with PDF files ([source](https://github.com/anthropics/skills/tree/main/skills/pdf)).
- [Documents to Markdown](https://thriftyfig.pages.dev/skills/markitdown/) — Convert heterogeneous documents into Markdown for reading and analysis ([source](https://github.com/K-Dense-AI/scientific-agent-skills/tree/main/skills/markitdown)).
- [Convert Pdf To Md](https://thriftyfig.pages.dev/skills/convert-pdf-to-md/) — Convert PDF contents to Markdown for analysis or search ([source](https://github.com/github/awesome-copilot/tree/main/skills/convert-pdf-to-md)).
- [pdf-analyzer](https://thriftyfig.pages.dev/skills/pdf-analyzer/) — Pull text and tables out of PDFs so you can work with their contents ([source](https://github.com/TerminalSkills/skills/tree/main/skills/pdf-analyzer)).
- [Scanned PDF Text Recognition](https://thriftyfig.pages.dev/skills/pdf-ocr/) — Recognize text in scanned PDFs with OCR and language settings ([source](https://github.com/TerminalSkills/skills/tree/main/skills/pdf-ocr)).
- [PDF Page Merge and Split](https://thriftyfig.pages.dev/skills/pdf-merge-split/) — Combine PDFs or extract page ranges while preserving originals ([source](https://github.com/TerminalSkills/skills/tree/main/skills/pdf-merge-split)).
- [Structured PDF Extraction](https://thriftyfig.pages.dev/skills/opendataloader-pdf/) — Extract PDF structure to Markdown, JSON with boxes, HTML, or text ([source](https://github.com/TerminalSkills/skills/tree/main/skills/opendataloader-pdf)).
- [Mineru](https://thriftyfig.pages.dev/skills/mineru/) — Convert PDFs, scans, images or Office files to Markdown or structured JSON ([source](https://github.com/TerminalSkills/skills/tree/main/skills/mineru)).
- [Pdf To Markdown](https://thriftyfig.pages.dev/skills/pdf-to-markdown/) — Converts PDF files to Markdown using Microsoft's markitdown package ([source](https://github.com/pamelafox/presentation-skills/tree/main/.agents/skills/pdf-to-markdown)).
- [Pdf Table Data Conversion](https://thriftyfig.pages.dev/skills/pdf-table-data-conversion/) — Extract PDF tables into a spreadsheet or CSV file ([source](https://github.com/microsoft/cat-agent-skills/tree/main/submissions/pdf-table-data-conversion)).

## Word, slides and documents

Related: [Claude DOCX skills for Word documents and templates](https://thriftyfig.pages.dev/topics/claude-docx-skill/) · [Claude document skills: PDF, DOCX, PPTX and XLSX](https://thriftyfig.pages.dev/topics/claude-document-skills/) · [Claude PowerPoint skill: PPTX and presentation options](https://thriftyfig.pages.dev/topics/claude-powerpoint-skill/) · [Claude Excel skills for spreadsheets and data](https://thriftyfig.pages.dev/topics/claude-excel-skills/) · [Write a clear report from source material](https://thriftyfig.pages.dev/tasks/write-report/) · [Make an editable presentation](https://thriftyfig.pages.dev/tasks/make-ppt/) · [Clean up Excel and CSV files](https://thriftyfig.pages.dev/tasks/excel-cleanup/).

- [Pptx](https://thriftyfig.pages.dev/skills/pptx/) — Work with PowerPoint PPTX or POTX files as input or output ([source](https://github.com/anthropics/skills/tree/main/skills/pptx)).
- [Xlsx](https://thriftyfig.pages.dev/skills/xlsx/) — Work on a task whose main input or output is a spreadsheet ([source](https://github.com/anthropics/skills/tree/main/skills/xlsx)).
- [Md To Docx](https://thriftyfig.pages.dev/skills/md-to-docx/) — Convert Markdown to a formatted Word document with embedded PNG images ([source](https://github.com/github/awesome-copilot/tree/main/skills/md-to-docx)).
- [Convert Word To Md](https://thriftyfig.pages.dev/skills/convert-word-to-md/) — Convert a DOCX file to Markdown for reading, search or extraction ([source](https://github.com/github/awesome-copilot/tree/main/skills/convert-word-to-md)).
- [Markdown To Word Mermaid](https://thriftyfig.pages.dev/skills/markdown-to-word-mermaid/) — Export Markdown and Mermaid diagrams to Word with embedded diagrams ([source](https://github.com/github/awesome-copilot/tree/main/skills/markdown-to-word-mermaid)).
- [Node.js Word Document Generation](https://thriftyfig.pages.dev/skills/docx/) — Generate Word documents with tables, headings, and page elements using docx ([source](https://github.com/TerminalSkills/skills/tree/main/skills/docx)).
- [Word Templates and Mail Merge](https://thriftyfig.pages.dev/skills/microsoft-word/) — Create and edit DOCX files or fill templates with Python ([source](https://github.com/TerminalSkills/skills/tree/main/skills/microsoft-word)).
- [Powerpoint](https://thriftyfig.pages.dev/skills/powerpoint/) — Create, edit or read PowerPoint files with python-pptx ([source](https://github.com/TerminalSkills/skills/tree/main/skills/powerpoint)).
- [Template Based Document Generation](https://thriftyfig.pages.dev/skills/template-based-document-generation/) — Fill a Word (.docx) template from structured data and return the finished document with its branding intact ([source](https://github.com/microsoft/cat-agent-skills/tree/main/submissions/template-based-document-generation)).
- [Doc Format Converter](https://thriftyfig.pages.dev/skills/doc-format-converter/) — Convert between document formats such as Markdown, PDF, Word and plain text ([source](https://github.com/microsoft/cat-agent-skills/tree/main/submissions/doc-format-converter)).

## Coding and code review

Related: [Claude skills for code review before a merge](https://thriftyfig.pages.dev/topics/claude-skills-for-code-review/) · [Claude Code skills list: practical examples](https://thriftyfig.pages.dev/topics/claude-code-skills-list/) · [Superpowers for Claude Code: skills and plugin workflows](https://thriftyfig.pages.dev/topics/superpowers-claude-code/) · [AI code review before merge](https://thriftyfig.pages.dev/tasks/ai-code-review-before-merge/).

- [Systematic Debugging](https://thriftyfig.pages.dev/skills/systematic-debugging/) — Find the root cause of a failure through structured investigation ([source](https://github.com/obra/superpowers/tree/main/skills/systematic-debugging)).
- [Requesting Code Review](https://thriftyfig.pages.dev/skills/requesting-code-review/) — Prepare scoped review context and handle findings before integration ([source](https://github.com/obra/superpowers/tree/main/skills/requesting-code-review)).
- [Code Review Reception](https://thriftyfig.pages.dev/skills/receiving-code-review/) — Evaluate review feedback against technical evidence before applying changes ([source](https://github.com/obra/superpowers/tree/main/skills/receiving-code-review)).
- [Writing Plans](https://thriftyfig.pages.dev/skills/writing-plans/) — Turn approved requirements into specific implementation and verification steps ([source](https://github.com/obra/superpowers/tree/main/skills/writing-plans)).
- [Executing Plans](https://thriftyfig.pages.dev/skills/executing-plans/) — Execute an approved implementation plan with task-by-task verification ([source](https://github.com/obra/superpowers/tree/main/skills/executing-plans)).
- [Code Review Excellence](https://thriftyfig.pages.dev/skills/code-review-excellence/) — Structure code review feedback and look for bugs early ([source](https://github.com/wshobson/agents/tree/main/plugins/developer-essentials/skills/code-review-excellence)).
- [Architecture Patterns](https://thriftyfig.pages.dev/skills/architecture-patterns/) — Apply backend patterns such as Clean Architecture or Domain-Driven Design ([source](https://github.com/wshobson/agents/tree/main/plugins/backend-development/skills/architecture-patterns)).
- [Create high‑quality AGENTS.md file](https://thriftyfig.pages.dev/skills/create-agentsmd/) — Generate an AGENTS.md instruction file for a repository ([source](https://github.com/github/awesome-copilot/tree/main/skills/create-agentsmd)).
- [supabase-postgres-best-practices](https://thriftyfig.pages.dev/skills/supabase-postgres-best-practices/) — Improve PostgreSQL queries and database design using source guidance ([source](https://github.com/supabase/agent-skills/tree/main/skills/supabase-postgres-best-practices)).
- [code-reviewer](https://thriftyfig.pages.dev/skills/code-reviewer/) — Review code changes for bugs, risks, and maintainability problems ([source](https://github.com/TerminalSkills/skills/tree/main/skills/code-reviewer)).

## Video and subtitles

Related: [Claude skills for video editing and short videos](https://thriftyfig.pages.dev/topics/claude-skills-for-video/) · [Claude skills for subtitles, captions and timing checks](https://thriftyfig.pages.dev/topics/claude-skills-for-subtitles/) · [Make a short video](https://thriftyfig.pages.dev/tasks/make-short-video/) · [Add and check subtitles](https://thriftyfig.pages.dev/tasks/add-subtitles/).

- [Video Router](https://thriftyfig.pages.dev/skills/video-router/) — Choose generation, composition or supplied-footage editing before production ([source](https://github.com/sickn33/agentic-awesome-skills/tree/main/skills/video-router)).
- [Caption Qa](https://thriftyfig.pages.dev/skills/caption-qa/) — Check subtitle timing, reading speed and line lengths against a chosen standard ([source](https://github.com/github/awesome-copilot/tree/main/skills/caption-qa)).
- [Transloadit Media Processing](https://thriftyfig.pages.dev/skills/transloadit-media-processing/) — Build media processing assemblies for encoding, thumbnails and subtitles ([source](https://github.com/github/awesome-copilot/tree/main/skills/transloadit-media-processing)).
- [Demo Video](https://thriftyfig.pages.dev/skills/demo-video/) — Turn screenshots and scene descriptions into a narrated product demo ([source](https://github.com/alirezarezvani/claude-skills/tree/main/engineering/demo-video/skills/demo-video)).
- [Ffmpeg](https://thriftyfig.pages.dev/skills/ffmpeg/) — Trim, compress, concatenate and caption video or audio files ([source](https://github.com/TerminalSkills/skills/tree/main/skills/ffmpeg)).
- [Remotion Video Toolkit](https://thriftyfig.pages.dev/skills/remotion-video-toolkit/) — Create repeatable React videos with animation, captions and local rendering ([source](https://github.com/TerminalSkills/skills/tree/main/skills/remotion-video-toolkit)).
- [Ai Video Generator](https://thriftyfig.pages.dev/skills/ai-video-generator/) — Build narrated vertical shorts from scripts, stock footage and subtitles ([source](https://github.com/TerminalSkills/skills/tree/main/skills/ai-video-generator)).
- [Moviepy](https://thriftyfig.pages.dev/skills/moviepy/) — Edit or compose video programmatically with Python ([source](https://github.com/TerminalSkills/skills/tree/main/skills/moviepy)).
- [Youtube Transcription](https://thriftyfig.pages.dev/skills/youtube-transcription/) — Download authorized YouTube audio and generate subtitles with Whisper ([source](https://github.com/TerminalSkills/skills/tree/main/skills/youtube-transcription)).
- [Explainer Video](https://thriftyfig.pages.dev/skills/explainer-video/) — Produce a narrated educational video with captions and a sourced script ([source](https://github.com/microsoft/cat-agent-skills/tree/main/submissions/explainer-video)).

## Audio, voiceover and transcription

Related: [Claude skills for text to speech and voiceovers](https://thriftyfig.pages.dev/topics/claude-skills-for-text-to-speech/) · [Claude skills for audio transcription and speaker labels](https://thriftyfig.pages.dev/topics/claude-skills-for-transcription/) · [Create a voiceover with TTS](https://thriftyfig.pages.dev/tasks/voiceover-tts/) · [Add and check subtitles](https://thriftyfig.pages.dev/tasks/add-subtitles/).

- [Podcast Generation](https://thriftyfig.pages.dev/skills/podcast-generation/) — Convert source text into a two-host podcast script and synthesized audio ([source](https://github.com/bytedance/deer-flow/tree/main/skills/public/podcast-generation)).
- [Audio Transcriber](https://thriftyfig.pages.dev/skills/audio-transcriber/) — Turn an audio recording into a readable Markdown transcript with optional summaries ([source](https://github.com/sickn33/agentic-awesome-skills/tree/main/skills/audio-transcriber)).
- [Speak Summary](https://thriftyfig.pages.dev/skills/speak-summary/) — Turn text, Markdown or a summary into an MP3 with local text to speech ([source](https://github.com/github/awesome-copilot/tree/main/skills/speak-summary)).
- [Speech](https://thriftyfig.pages.dev/skills/speech/) — Generate narrated audio from exact text using the bundled speech CLI ([source](https://github.com/openai/skills/tree/main/skills/.curated/speech)).
- [Transcribe](https://thriftyfig.pages.dev/skills/transcribe/) — Transcribe audio through the bundled CLI with optional speaker labels and hints ([source](https://github.com/openai/skills/tree/main/skills/.curated/transcribe)).
- [Elevenlabs](https://thriftyfig.pages.dev/skills/elevenlabs/) — Generate speech with the ElevenLabs API and its Python or Node.js SDK ([source](https://github.com/TerminalSkills/skills/tree/main/skills/elevenlabs)).
- [Whisper](https://thriftyfig.pages.dev/skills/whisper/) — Transcribe recordings locally and produce SRT or VTT subtitles ([source](https://github.com/TerminalSkills/skills/tree/main/skills/whisper)).
- [Vibe Voice](https://thriftyfig.pages.dev/skills/vibe-voice/) — Transcribe long recordings with speaker labels and explore streaming speech workflows ([source](https://github.com/TerminalSkills/skills/tree/main/skills/vibe-voice)).
- [Assemblyai](https://thriftyfig.pages.dev/skills/assemblyai/) — Transcribe recordings or streams with a hosted API and speaker labels ([source](https://github.com/TerminalSkills/skills/tree/main/skills/assemblyai)).
- [Deepgram](https://thriftyfig.pages.dev/skills/deepgram/) — Use the Deepgram API for transcription, speech analysis or text to speech ([source](https://github.com/TerminalSkills/skills/tree/main/skills/deepgram)).

## Data analysis and CSV

Related: [Claude skills for data analysis and CSV files](https://thriftyfig.pages.dev/topics/claude-skills-for-data-analysis/) · [Start a practical data analysis](https://thriftyfig.pages.dev/tasks/data-analysis-quickstart/) · [Clean up Excel and CSV files](https://thriftyfig.pages.dev/tasks/excel-cleanup/).

- [Statistical Analysis](https://thriftyfig.pages.dev/skills/statistical-analysis/) — Choose statistical tests, check assumptions and report research results ([source](https://github.com/K-Dense-AI/scientific-agent-skills/tree/main/skills/statistical-analysis)).
- [Business Chart Design](https://thriftyfig.pages.dev/skills/data-visualization/) — Choose readable business charts, axes, and colors ([source](https://github.com/anthropics/knowledge-work-plugins/tree/main/data/skills/data-visualization)).
- [Pandas](https://thriftyfig.pages.dev/skills/pandas/) — Load, clean, transform or analyze tabular data with pandas ([source](https://github.com/TerminalSkills/skills/tree/main/skills/pandas)).
- [Streaming CSV Import and Export](https://thriftyfig.pages.dev/skills/csv-parse/) — Parse and validate CSV through streaming JavaScript tools ([source](https://github.com/TerminalSkills/skills/tree/main/skills/csv-parse)).
- [Data Validator](https://thriftyfig.pages.dev/skills/data-validator/) — Validate data quality in CSV, JSON, and database exports by checking for missing values, type mismatches, duplicates, outliers, and schema violations ([source](https://github.com/TerminalSkills/skills/tree/main/skills/data-validator)).
- [Jupyter](https://thriftyfig.pages.dev/skills/jupyter/) — Analyze and visualize data interactively in Jupyter notebooks ([source](https://github.com/TerminalSkills/skills/tree/main/skills/jupyter)).
- [Pandas Ai](https://thriftyfig.pages.dev/skills/pandas-ai/) — Ask questions about a DataFrame or CSV using an LLM that runs analysis code ([source](https://github.com/TerminalSkills/skills/tree/main/skills/pandas-ai)).
- [Pandera](https://thriftyfig.pages.dev/skills/pandera/) — Validate DataFrames against column types, constraints and custom checks ([source](https://github.com/TerminalSkills/skills/tree/main/skills/pandera)).
- [Ibis](https://thriftyfig.pages.dev/skills/ibis/) — Use dataframe expressions that compile to SQL on the data engine ([source](https://github.com/TerminalSkills/skills/tree/main/skills/ibis)).
- [Chart Builder](https://thriftyfig.pages.dev/skills/chart-builder/) — Make a chart from a CSV, table or DataFrame ([source](https://github.com/microsoft/cat-agent-skills/tree/main/submissions/chart-builder)).

## Writing and reports

Related: [Write a clear report from source material](https://thriftyfig.pages.dev/tasks/write-report/) · [Build a sustainable personal content identity](https://thriftyfig.pages.dev/tasks/grow-personal-ip/).

- [Copy Editing](https://thriftyfig.pages.dev/skills/copy-editing/) — Improve an existing draft while preserving its argument and voice ([source](https://github.com/coreyhaines31/marketingskills/tree/main/skills/copy-editing)).
- [Copywriting](https://thriftyfig.pages.dev/skills/copywriting/) — Write evidence-based marketing copy with a clear audience and next action ([source](https://github.com/coreyhaines31/marketingskills/tree/main/skills/copywriting)).
- [Evidence-traceable Scientific Writing](https://thriftyfig.pages.dev/skills/scientific-writing/) — Draft and audit manuscripts with evidence provenance ([source](https://github.com/K-Dense-AI/scientific-agent-skills/tree/main/skills/scientific-writing)).
- [Traceable Literature Reviews](https://thriftyfig.pages.dev/skills/literature-review/) — Organize reproducible searches, screening, and review writing ([source](https://github.com/K-Dense-AI/scientific-agent-skills/tree/main/skills/literature-review)).
- [Scientific Markdown and Diagrams](https://thriftyfig.pages.dev/skills/markdown-mermaid-writing/) — Write structured Markdown with checked Mermaid diagrams ([source](https://github.com/K-Dense-AI/scientific-agent-skills/tree/main/skills/markdown-mermaid-writing)).
- [Write In My Voice](https://thriftyfig.pages.dev/skills/write-in-my-voice/) — Draft X or LinkedIn posts from a user's real writing samples ([source](https://github.com/sickn33/agentic-awesome-skills/tree/main/skills/write-in-my-voice)).
- [Postmortem Writing](https://thriftyfig.pages.dev/skills/postmortem-writing/) — Write a blameless postmortem with a timeline, root causes and actions ([source](https://github.com/wshobson/agents/tree/main/plugins/incident-response/skills/postmortem-writing)).
- [Content Humanizer](https://thriftyfig.pages.dev/skills/content-humanizer/) — Identify robotic writing patterns and replace them with concrete, natural phrasing ([source](https://github.com/alirezarezvani/claude-skills/tree/main/marketing-skill/skills/content-humanizer)).
- [markdown-writer](https://thriftyfig.pages.dev/skills/markdown-writer/) — Turn project information into readable Markdown documentation ([source](https://github.com/TerminalSkills/skills/tree/main/skills/markdown-writer)).
- [Brand Voice Pass](https://thriftyfig.pages.dev/skills/brand-voice-pass/) — Align a draft with a defined brand or personal voice while retaining evidence ([source](https://github.com/microsoft/cat-agent-skills/tree/main/submissions/brand-voice-pass)).

## Testing

Related: [Claude skills for testing web apps, APIs and code](https://thriftyfig.pages.dev/topics/claude-skills-for-testing/) · [Auto-test your web app with AI](https://thriftyfig.pages.dev/tasks/auto-test-your-web-app/).

- [Test-Driven Development (TDD)](https://thriftyfig.pages.dev/skills/test-driven-development/) — Build behavior through failing tests, minimal implementation, and refactoring ([source](https://github.com/obra/superpowers/tree/main/skills/test-driven-development)).
- [webapp-testing](https://thriftyfig.pages.dev/skills/webapp-testing/) — Check how a local web app behaves in a browser and investigate broken flows ([source](https://github.com/anthropics/skills/tree/main/skills/webapp-testing)).
- [Python Testing Patterns](https://thriftyfig.pages.dev/skills/python-testing-patterns/) — Build pytest tests with fixtures and mocking ([source](https://github.com/wshobson/agents/tree/main/plugins/python-development/skills/python-testing-patterns)).
- [JavaScript Testing Patterns](https://thriftyfig.pages.dev/skills/javascript-testing-patterns/) — Build JavaScript tests with Jest, Vitest or Testing Library ([source](https://github.com/wshobson/agents/tree/main/plugins/javascript-typescript/skills/javascript-testing-patterns)).
- [E2e Testing Patterns](https://thriftyfig.pages.dev/skills/e2e-testing-patterns/) — Plan end-to-end tests with Playwright or Cypress ([source](https://github.com/wshobson/agents/tree/main/plugins/developer-essentials/skills/e2e-testing-patterns)).
- [Test Gap Audit](https://thriftyfig.pages.dev/skills/test-gap-audit/) — Run a read-only audit for missing, weak, stale, or mis-scoped test coverage ([source](https://github.com/github/awesome-copilot/tree/main/skills/test-gap-audit)).
- [playwright](https://thriftyfig.pages.dev/skills/playwright/) — Automate a real browser to inspect pages and repeat common actions ([source](https://github.com/openai/skills/tree/main/skills/.curated/playwright)).
- [api-tester](https://thriftyfig.pages.dev/skills/api-tester/) — Check API endpoints and investigate unexpected responses ([source](https://github.com/TerminalSkills/skills/tree/main/skills/api-tester)).
- [test-generator](https://thriftyfig.pages.dev/skills/test-generator/) — Create tests for code, including edge cases that are easy to miss ([source](https://github.com/TerminalSkills/skills/tree/main/skills/test-generator)).
- [Playwright Testing](https://thriftyfig.pages.dev/skills/playwright-testing/) — Write and maintain end-to-end Playwright tests ([source](https://github.com/TerminalSkills/skills/tree/main/skills/playwright-testing)).

## DevOps and deployment

Related: [Claude skills for deployment, Docker and CI/CD](https://thriftyfig.pages.dev/topics/claude-skills-for-deployment/).

- [Deployment Pipeline Design](https://thriftyfig.pages.dev/skills/deployment-pipeline-design/) — Design a multi-stage CI/CD pipeline with approval gates and security checks ([source](https://github.com/wshobson/agents/tree/main/plugins/cicd-automation/skills/deployment-pipeline-design)).
- [GitHub Actions Templates](https://thriftyfig.pages.dev/skills/github-actions-templates/) — Create GitHub Actions workflows for testing, building or deploying ([source](https://github.com/wshobson/agents/tree/main/plugins/cicd-automation/skills/github-actions-templates)).
- [GitLab CI Patterns](https://thriftyfig.pages.dev/skills/gitlab-ci-patterns/) — Build GitLab CI/CD pipelines with stages, caching and distributed runners ([source](https://github.com/wshobson/agents/tree/main/plugins/cicd-automation/skills/gitlab-ci-patterns)).
- [GitOps Workflow](https://thriftyfig.pages.dev/skills/gitops-workflow/) — Set up declarative Kubernetes deployments with ArgoCD or Flux ([source](https://github.com/wshobson/agents/tree/main/plugins/kubernetes-operations/skills/gitops-workflow)).
- [Multi Stage Dockerfile](https://thriftyfig.pages.dev/skills/multi-stage-dockerfile/) — Create a multi-stage Dockerfile for an application ([source](https://github.com/github/awesome-copilot/tree/main/skills/multi-stage-dockerfile)).
- [deploy-to-vercel](https://thriftyfig.pages.dev/skills/deploy-to-vercel/) — Publish a web project to Vercel using the upstream deployment workflow ([source](https://github.com/vercel-labs/agent-skills/tree/main/skills/deploy-to-vercel)).
- [vercel-deploy](https://thriftyfig.pages.dev/skills/vercel-deploy/) — Create a Vercel deployment for a web project ([source](https://github.com/openai/skills/tree/main/skills/.curated/vercel-deploy)).
- [cloudflare-deploy](https://thriftyfig.pages.dev/skills/cloudflare-deploy/) — Choose a Cloudflare service and deploy a project to it ([source](https://github.com/openai/skills/tree/main/skills/.curated/cloudflare-deploy)).
- [docker-helper](https://thriftyfig.pages.dev/skills/docker-helper/) — Package an application in containers and make it easier to run consistently ([source](https://github.com/TerminalSkills/skills/tree/main/skills/docker-helper)).
- [Ansible](https://thriftyfig.pages.dev/skills/ansible/) — Configure servers or deploy applications over SSH using YAML playbooks ([source](https://github.com/TerminalSkills/skills/tree/main/skills/ansible)).

## Security review

Related: [Claude skills for security review and audits](https://thriftyfig.pages.dev/topics/claude-skills-for-security/) · [AI code review before merge](https://thriftyfig.pages.dev/tasks/ai-code-review-before-merge/).

- [SAST Configuration](https://thriftyfig.pages.dev/skills/sast-configuration/) — Configure static analysis tools to look for code vulnerabilities ([source](https://github.com/wshobson/agents/tree/main/plugins/security-scanning/skills/sast-configuration)).
- [Security Requirement Extraction](https://thriftyfig.pages.dev/skills/security-requirement-extraction/) — Derive security requirements from threat models and business context ([source](https://github.com/wshobson/agents/tree/main/plugins/security-scanning/skills/security-requirement-extraction)).
- [Kubernetes Security Policies](https://thriftyfig.pages.dev/skills/k8s-security-policies/) — Review Kubernetes network policies, service-account RBAC and pod standards ([source](https://github.com/wshobson/agents/tree/main/plugins/kubernetes-operations/skills/k8s-security-policies)).
- [GitHub Actions Hardening](https://thriftyfig.pages.dev/skills/github-actions-hardening/) — Audit GitHub Actions trust boundaries, token permissions, action references, and untrusted inputs ([source](https://github.com/github/awesome-copilot/tree/main/skills/github-actions-hardening)).
- [MCP Implementation Security Review](https://thriftyfig.pages.dev/skills/mcp-implementation-security-review/) — Audit MCP implementation code for identity isolation, input validation, sessions, and injection risks ([source](https://github.com/github/awesome-copilot/tree/main/skills/mcp-implementation-security-review)).
- [Mcp Security Audit](https://thriftyfig.pages.dev/skills/mcp-security-audit/) — Audit MCP server configurations for security issues ([source](https://github.com/github/awesome-copilot/tree/main/skills/mcp-security-audit)).
- [Agent Owasp Compliance](https://thriftyfig.pages.dev/skills/agent-owasp-compliance/) — Check agent code against the OWASP Agentic Security Initiative Top 10 ([source](https://github.com/github/awesome-copilot/tree/main/skills/agent-owasp-compliance)).
- [security-best-practices](https://thriftyfig.pages.dev/skills/security-best-practices/) — Review code for security risks and safer implementation choices ([source](https://github.com/openai/skills/tree/main/skills/.curated/security-best-practices)).
- [Security Audit](https://thriftyfig.pages.dev/skills/security-audit/) — Scan code for security vulnerabilities, misconfigurations, and exposed secrets ([source](https://github.com/TerminalSkills/skills/tree/main/skills/security-audit)).
- [Webhook Security](https://thriftyfig.pages.dev/skills/webhook-security/) — Check webhook signatures, replay protection and retry deduplication ([source](https://github.com/TerminalSkills/skills/tree/main/skills/webhook-security)).

## Visual design and illustrations

Related: [Build a sustainable personal content identity](https://thriftyfig.pages.dev/tasks/grow-personal-ip/).

- [Canvas Design](https://thriftyfig.pages.dev/skills/canvas-design/) — Create visual art in PNG or PDF documents ([source](https://github.com/anthropics/skills/tree/main/skills/canvas-design)).
- [theme-factory](https://thriftyfig.pages.dev/skills/theme-factory/) — Give documents and other artifacts a consistent set of fonts and colors ([source](https://github.com/anthropics/skills/tree/main/skills/theme-factory)).
- [slack-gif-creator](https://thriftyfig.pages.dev/skills/slack-gif-creator/) — Make a small animated GIF for a Slack conversation ([source](https://github.com/anthropics/skills/tree/main/skills/slack-gif-creator)).
- [algorithmic-art](https://thriftyfig.pages.dev/skills/algorithmic-art/) — Create artwork with code and adjustable visual patterns ([source](https://github.com/anthropics/skills/tree/main/skills/algorithmic-art)).
- [Infographics](https://thriftyfig.pages.dev/skills/infographics/) — Create or review infographics with Nano Banana 2 through OpenRouter ([source](https://github.com/K-Dense-AI/scientific-agent-skills/tree/main/skills/infographics)).
- [Generate Image](https://thriftyfig.pages.dev/skills/generate-image/) — Generate or edit images through the OpenRouter Image API ([source](https://github.com/K-Dense-AI/scientific-agent-skills/tree/main/skills/generate-image)).
- [Baoyu Cover Image](https://thriftyfig.pages.dev/skills/baoyu-cover-image/) — Design article covers through explicit palette, type, text and mood choices ([source](https://github.com/JimLiu/baoyu-skills/tree/main/skills/baoyu-cover-image)).
- [Baoyu Infographic](https://thriftyfig.pages.dev/skills/baoyu-infographic/) — Turn structured information into an infographic with a suitable layout and style ([source](https://github.com/JimLiu/baoyu-skills/tree/main/skills/baoyu-infographic)).
- [Baoyu Article Illustrator](https://thriftyfig.pages.dev/skills/baoyu-article-illustrator/) — Find useful illustration positions in an article and generate a consistent visual plan ([source](https://github.com/JimLiu/baoyu-skills/tree/main/skills/baoyu-article-illustrator)).
- [Baoyu Comic](https://thriftyfig.pages.dev/skills/baoyu-comic/) — Turn educational material into a panel-by-panel knowledge comic ([source](https://github.com/JimLiu/baoyu-skills/tree/main/skills/baoyu-comic)).

## How to use a skill

Start with the [Claude and Cursor installation guide](https://thriftyfig.pages.dev/topics/how-to-install-claude-skills/). Open a skill’s source, read its instructions and license, and check dependencies and any external service costs. Keep the complete skill folder, including scripts and references. Try a small input and review the result.

For setup details, follow the official [Claude upload guide](https://support.claude.com/en/articles/12512180-use-skills-in-claude), [Claude Code skills documentation](https://code.claude.com/docs/en/skills/) or [Cursor skills documentation](https://cursor.com/docs/skills), as linked in the installation topic.

## More ways to browse

Use [topics](https://thriftyfig.pages.dev/topics/) for focused shortlists, [task guides](https://thriftyfig.pages.dev/tasks/) for a starting workflow, or [the complete skill directory](https://thriftyfig.pages.dev/skills/) to compare alternatives. The catalog also has [five guides](https://thriftyfig.pages.dev/guides/), including [free agent skills vs paid stacks](https://thriftyfig.pages.dev/guides/free-agent-skills-vs-paid-stacks/).
