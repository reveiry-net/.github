# Reveiry Labs

Plataforma SaaS multi-nicho con **infraestructura dedicada por empresa**. Cada cliente que contrata una app recibe su propio stack (base de datos, cache, API, IA); nada se comparte entre empresas.

## Repositorios
| Repo | Qué contiene |
|---|---|
| `reveiry-platform` | Control plane + runtime de tenants (monorepo: control-api, control-web, tenant-api, tenant-ai, esquemas) |
| `reveiry-docs` | Arquitectura, decisiones (ADR), nichos, roadmap |
| `.github` | Este perfil, plantillas de issues/PR, workflows reutilizables |

## Nomenclatura
`reveiry-<capa>-<nombre>` · capas: `platform` · `app` (un nicho cuando se separa del monorepo) · `sdk` · `infra` · `docs`
Ejemplos futuros: `reveiry-app-whatsapp`, `reveiry-sdk-js`, `reveiry-infra-vps`.
