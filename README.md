# meshcode-ai/skills-design

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Skills](https://img.shields.io/badge/skills-3-blue)](#)
[![Standard](https://img.shields.io/badge/agent--skills-spec-brightgreen)](https://agentskills.io/specification)

**Design skills for Claude Code, Codex, Cursor, and meshcode — homepage/landing design, UI design audit, and design-token systems.** The 3 design skills (`design-*`) are distilled editions containing **judgment knowledge only**, with no scripts: the AI-template tells that make a page look generated (cream+serif+terracotta, the SaaS-card kit, ALL-CAPS eyebrow chrome), conversion-order page structure, a 6-axis UI audit with A–F grading, and a three-layer token architecture (primitive → semantic → component) with a legacy migration rule. They follow the Agent Skills standard (agentkills.io) — unzip into your project's `.meshcode/skills/` (flat layout) and Claude Code, Codex, Cursor, and meshcode desktop pick them up from the next session.

## Who this is for

- **Founders and marketers** — a homepage that converts instead of a template that "looks like AI made it"
- **Designers and PMs** — a repeatable design-review contract: graded axes, cited evidence, impact-ranked fixes
- **Frontend teams** — token architecture and a legacy value→token migration map that survives the codemod
- **AI agent operators** — knowledge-first design skills ready for stores and registries

## Skill list

| Skill | Role | Core judgment criteria |
|---|---|---|
| `design-homepage` | Homepage / landing page design | Conversion order, AI-template tells, one boldness point, quality floor |
| `design-ui-audit` | UI design review | 6 axes A–F with cited elements, priority = impact × 1/difficulty |
| `design-design-system` | Design tokens / system | 3 token layers, dark mode swaps semantic only, mapping-table migration |

## Install

1. Download the zip → extract into your project's `.meshcode/skills/` (flat: `.meshcode/skills/design-homepage/SKILL.md`)
2. Start a new Claude Code · Codex · Cursor · meshcode session → skills are exposed automatically
3. Full catalog at the hub: [github.com/meshcode-ai/skills](https://github.com/meshcode-ai/skills)

## Skill details

### design-homepage
> Homepage and landing page design — structure, hero, visual hierarchy, motion restraint, and AI-template tells. Use when the user says "design a homepage", "landing page design", "hero section", "website design"…

### design-ui-audit
> UI design review — grades hierarchy, spacing, typography, color, consistency, accessibility of a page or component set, then ranks fixes by impact. Use when the user says "design review", "UI audit", "critique this UI"…

### design-design-system
> Design system and design tokens — token layering (primitive → semantic → component), minimal token set, dark mode, and legacy migration mapping. Use when the user says "design system", "design tokens", "unify our styles"…

## Hub & related repos

- Hub catalog: **[github.com/meshcode-ai/skills](https://github.com/meshcode-ai/skills)** (llms.txt · index.json · robots.txt)
- [skills-seo](https://github.com/meshcode-ai/skills-seo) · [skills-copy](https://github.com/meshcode-ai/skills-copy) · [skills-video](https://github.com/meshcode-ai/skills-video) · [skills-docs](https://github.com/meshcode-ai/skills-docs) — landing copy, video, and document production around the same page

## Use with meshcode

Built for [meshcode](https://meshcode.ai) (free download — macOS/Windows):

1. Open your project in meshcode
2. In chat, ask **"show available skills"**, then **"install the design skills"** — meshcode fetches from this repo automatically
3. They appear in the next session and load only when a task matches

Manual alternative: repo zip → `.meshcode/skills/`. Also works in Claude Code (`~/.claude/skills/`), Codex, and Cursor.

## 정리 로그 (2026-09-13)

- 소스: [xiaopu-ai/web-design](https://github.com/xiaopu-ai/web-design) (MIT), [anthropics/skills](https://github.com/anthropics/skills) frontend-design · theme-factory (Apache-2.0)
- 원본 워크플로우/스크립트 구조는 제외하고 판단 지식만 정제: AI 템플릿 텔 목록, 구조 순서, 감사 축·등급, 토큰 3계층과 마이그레이션 표 규칙
- 출력 계약(`## Output contract`)을 3개 스킬 공통으로 고정 — 플랜/아웃라인 승인 → 산출물 → 자기 비평/검증 리포트
