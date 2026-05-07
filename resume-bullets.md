# Resume Bullets — Ready to Copy

## Header (ใส่แทน objective/summary)

> Self-taught AI engineer with hands-on experience building production SaaS, LLM-powered applications, and event-driven backend systems. Background in design thinking; strong bias toward shipping working software fast.

---

## SKILLS SECTION

```
Languages:     TypeScript, Python
Frontend:      Next.js (App Router), React, Tailwind CSS
Backend:       Supabase, Prisma ORM, Inngest, Upstash Redis
AI/LLM:        Anthropic Claude API, OpenAI API, prompt engineering,
               streaming responses, prompt caching, RAG pipelines
ML/Data:       PyTorch, scikit-learn, MLOps fundamentals
Infrastructure: Vercel, Stripe, PostHog, Sentry, Resend
Tools:         n8n, Hermes Agent, Obsidian, Git
```

---

## PROJECTS SECTION

### RepeatTree — Customer Revenue Intelligence SaaS
*github.com/Streynight/Repeat-Customer-Intelligence-SaaS*

- Built a production-grade multi-tenant SaaS from scratch in 4 days (39 commits) — organizations, workspaces, RBAC, audit logs, Stripe billing
- Designed a 771-line Prisma schema supporting multi-tenant data isolation, RFM segmentation, cohort metrics, automation rules, and audit trails
- Integrated Anthropic Claude API with streaming responses and prompt caching to generate AI-powered operator insights from live workspace metrics
- Implemented distributed background job pipeline with Inngest step functions and Redis distributed locking — preventing duplicate metric recompute runs across concurrent Shopify webhooks
- Built native Shopify integration (full sync, incremental sync, webhook processor) and marketplace CSV import engine for Shopee, TikTok Shop, and Lazada
- Deployed on Vercel with Stripe subscription billing (free trials, plan limits), Supabase Postgres, Upstash Redis, PostHog analytics, and Sentry error tracking
- **Stack:** Next.js 16, TypeScript strict, Supabase, Prisma, Inngest, Redis, Stripe, Claude API

---

### AI-Augmented Development Workflow
*Personal tooling — in use daily*

- Built a local AI agent environment using Hermes Agent (Nous Research) with Discord, n8n workflow automation, and cron-based task scheduling
- Created Obsidian ↔ Claude memory sync scripts that auto-generate session context before each coding sprint — compressing previous decisions and roadmap state into structured prompts
- Configured Claude Code with architectural rules (CLAUDE.md) to enforce tenant isolation, auth patterns, and Inngest job requirements across all AI-assisted coding sessions

---

## EDUCATION SECTION (ใส่ล่างสุด)

```
Bachelor's — Culinary Arts and Design
[ชื่อมหาวิทยาลัย], [ปี]
```

---

## TIPS

- ถ้า apply startup / AI-first company → เอา "AI-Augmented Workflow" project ขึ้นก่อน
- ถ้า apply product/SaaS company → เอา RepeatTree ขึ้นก่อน
- ถ้า apply remote (USD) → เพิ่มบรรทัดว่า "Open to remote work (UTC+7)"
- อย่าใส่ "Junior" ใน title ที่ apply — ให้ระบุ "AI Engineer" หรือ "Full-Stack Engineer" ตรงๆ
