<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=120&color=0:1e293b,100:64748b&section=header" alt="" width="100%" />
</p>

<h1>Ryan Choi</h1>

<p>
  <strong>Senior frontend engineer · 10+ years · Vue &amp; React</strong><br/>
  Building AI-powered products. Recently shipped a production RAG chatbot that lets customers get answers in natural language instead of searching and skimming the help center.<br/><br />
  <strong>Open to senior frontend or full-stack roles where AI is part of the product.</strong>
</p>

<p>
  <a href="https://www.linkedin.com/in/ryanchoimn" target="_blank">LinkedIn</a> ·
  <a href="mailto:ryan@ryanchoi.dev?subject=Introduction%20via%20your%20GitHub%20profile">Email</a> ·
  <a href="https://ryanchoi.dev" target="_blank">ryanchoi.dev</a>
</p>

---

## Recent work

### Pathway Chatbot: privacy-first RAG documentation assistant
A production retrieval-augmented chatbot that ingests company documentation (including a live Zendesk knowledge-base sync via n8n) and answers end-user questions with streaming generation. Entire stack runs on the customer's infrastructure: embeddings and LLM inference via Ollama (Mistral + nomic-embed-text), pgvector for retrieval. No data leaves the box.

- **Impact:** Faster, easier documentation lookup for customers; conversational Q&A with streaming responses replaces searching and skimming through the help center.
- **Stack:** Nuxt 4 / Vue 3 · Nuxt server routes (Node) · PostgreSQL + pgvector · Drizzle · Ollama (Mistral + nomic-embed-text) · Redis · n8n for Zendesk sync · Docker Compose
- **Notable engineering:** hybrid retrieval with query rewriting, reranking, and RRF · prompt-injection defense pipeline (direct- and context-injection risk assessment, hard-block / soft-allow / sanitize modes, hardened system prompt) · streaming chat, message regeneration, feedback capture
- **My role:** Sole developer and designer on the project.
- **Link:** Private; happy to walk through in an interview.

---

## Tech stack

**Core Languages & Frontend**
* **TypeScript:** Deepest expertise in **Vue 3** and **Nuxt**; experienced with **React** and **Next.js**.
* **Frontend Competencies:** Component Architecture, Vue Composition API, React Hooks, State Management (Pinia, Redux), Client-Side Routing (Vue Router, React Router), and Server-Side Rendering.

**Backend & Database**
* **Backend:** Node.js (implemented via Nuxt server routes), PHP, Python, and C#.
* **Databases & ORM:** PostgreSQL (including `pgvector` for AI), MySQL, and MariaDB, interfaced via Drizzle ORM.

**AI & Machine Learning Stack**
* **RAG Architecture:** Shipped end-to-end pipelines featuring hybrid retrieval and prompt-injection defense.
* **Self-Hosted Inference:** Experience with Ollama and Mistral.
* **Mobile AI:** Currently building with on-device Gemma 4 E2B on iOS.

**Tooling & Testing**
* **Build Tools:** Vite
* **Testing:** Vitest (utilizing `.spec.ts` format for unit testing)

**Team Philosophy**
* Adaptable and happy to pick up whatever technologies the team uses.

---

## Currently building

iOS macronutrient tracker where users photograph a meal and get nutritional entries back from Gemma 4 E2B running on-device (via LiteRT-LM). No backend, no account, no network. Data stays on the phone. Built in Swift 6 with strict concurrency, SwiftData, and a dedicated `ModelActor` keeping inference off the main thread. Attacking the manual-entry friction that kills most food-logging habits.

---

<sub>Fastest way to reach me: <a href="mailto:ryan@ryanchoi.dev">ryan@ryanchoi.dev</a>. Based in Minnesota, open to remote or hybrid.</sub>
