# BACKLOG.md

## Global

- Product: GitHub profile README for lgzarturo — professional portfolio page rendered on github.com/lgzarturo
- Strategy: Make profile more professional, indexable, and content-rich with detailed project descriptions and optimized links
- Policy: Spanish-first language, English tech keywords for recruiter search. No changes to blog workflow or BLOG-ALG tags. Do not add unverified metrics.
- Stack: Markdown, GitHub Actions (blog-post-workflow)
- External sites: lgzarturo.com (portfolio primary), arthurolg.com (blog)

## Items

## Archive
### BC-003 | SEO and recruiter keyword optimization

- Priority: P2
- Status: DONE
- Type: feature
- Depends on: BC-001
- Description: Optimize README content for recruiter search and GitHub discoverability. Ensure key technical terms (Spring Boot, Kotlin, Software Architecture, Technical Leader, SaaS, Cloud, Microservices) appear naturally in headings and body text. Add structured keywords that match common recruiter search patterns without keyword stuffing.
- Scope: README.md header (lines 1-6), "Sobre mi" section (lines 20-33), "Stack principal" section (lines 67-71)
- Out of scope: Project cards (covered by BC-001), blog section, workflow
- Acceptance:
  - H1/H2 headings contain searchable role titles (Technical Leader, Product Engineer, Software Architect)
  - Key tech stack terms appear in first 10 lines for GitHub search indexing
  - "Sobre mi" section includes domain expertise keywords (hotelera, SaaS, microservicios, arquitectura)
  - Content reads naturally with no keyword stuffing
  - BLOG-ALG comment tags remain intact

### BC-001 | Enhance project cards with architecture detail

- Priority: P1
- Status: DONE
- Type: feature
- Depends on: none
- Description: Expand the two project cards in the "Proyectos que demuestran criterio" table (API REST Spring Boot + Kotlin, CodeConductor AI-assisted Engineering) from 1-line problem/solution to architecture-pattern-level detail. Each card should show architectural decisions, patterns used, and key technical choices (~3-4 bullet points per project).
- Scope: README.md lines 47-56 (project table section)
- Out of scope: Changes to "Productos en producción" section, blog workflow, external site content
- Acceptance:
  - Each project card contains 3-4 bullet points describing architecture patterns and design decisions
  - Spring Boot + Kotlin card mentions patterns (hexagonal/clean architecture, layered design, Gradle multi-module if applicable)
  - CodeConductor card mentions AI-assisted engineering patterns, framework structure, developer experience approach
  - Table remains readable and scannable on GitHub mobile/desktop
  - BLOG-ALG comment tags remain intact

### BC-002 | Switch primary portfolio link to lgzarturo.com

- Priority: P2
- Status: DONE
- Type: feature
- Depends on: none
- Description: Update all primary external links in README to point to lgzarturo.com (professional portfolio) instead of arthurolg.com. Keep arthurolg.com referenced as blog. Specific changes: header link (line 1), website badge (line 14), and any CTA/footer references.
- Scope: README.md lines 1, 14, 86-89
- Out of scope: Blog section, blog workflow, arthurolg.com content
- Acceptance:
  - Header name link points to https://lgzarturo.com
  - Website badge points to https://lgzarturo.com
  - arthurolg.com still referenced as blog in "Ultimas publicaciones" section
  - BLOG-ALG comment tags remain intact
  - No broken links


<!-- Completed items move here. Never rewrite or re-execute archived items. -->
