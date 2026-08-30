# 📐 Documentación de Arquitectura & Casos de Estudio

Bienvenido a la suite de documentación técnica de proyectos liderados y diseñados por **Arturo L. Gómez**.

Esta carpeta contiene la especificación de arquitectura, decisiones de diseño (**ADRs - Architecture Decision Records**) y análisis del impacto técnico de las plataformas principales en las que me desempeño como **Technical Leader** y **Software Architect**.

---

## 📂 Índice de Proyectos

### 🏨 [Revenatium — Hospitality Platform & Direct Booking Engine](projects/revenatium/README.md)
Plataforma core para la industria hotelera. Motor de reservaciones de alta disponibilidad, canal directo y motor de fidelización/lealtad.
- **Stack**: `Spring Boot` • `Kotlin` • `Django` • `PostgreSQL` • `Microservicios` • `Redis`
- **Tópicos**: Arquitectura de microservicios, migración zero-downtime, estrategia multi-tenant y optimización del motor de reservas.

### 🤖 [CodeConductor — AI-Assisted Software Engineering Framework](projects/codeconductor/README.md)
Framework Open Source para la orquestación determinista de agentes de IA en ingeniería de software.
- **Stack**: `Multi-Agent Orchestration` • `CCEP Protocol` • `TypeScript` • `TDD` • `AST Verification`
- **Tópicos**: Protocolo de ejecución en fases (CCEP), simulación de roles (Architect, Tester, Implementer, Security), control de cambios quirúrgicos y mitigación de alucinaciones en LLMs.

### 💼 [StarTalent — Applicant Tracking System & HR SaaS](projects/startalent/README.md)
SaaS integral de gestión de recursos humanos y seguimiento de candidatos (ATS).
- **Stack**: `Java` • `Spring Boot` • `React` • `PostgreSQL` • `REST APIs` • `Docker`
- **Tópicos**: Máquina de estados para embudos de reclutamiento, optimización de queries y seguridad basada en roles (RBAC).

---

## 🎯 Estructura Estándar de Casos de Estudio
Cada proyecto documentado cumple con el siguiente estándar:
1. **Visión General & Problema de Negocio**
2. **Diagrama de Arquitectura de Sistema** (Mermaid)
3. **Architecture Decision Records (ADRs)**
4. **Desafíos de Ingeniería & Métricas de Impacto**
5. **Stack Tecnológico & Patrones Aplicados**
