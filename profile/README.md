# Lone Star Observatories

Lone Star Observatories builds and operates a small portfolio of astronomy,
dark-sky, commerce, community, and agentic software products. This organization
README is a map of the repositories currently visible in GitHub for the LSO
workspace.

Last inventoried: 2026-08-23

## Core Platform And Workspace

| Repository | Visibility | Language | Responsibility |
|---|---:|---|---|
| [riofuego](https://github.com/Lone-Star-Observatories/riofuego) | Private | PHP | Shared Rio Fuego platform kernel for LSO public applications: auth, tenants, WCM/assets, APIs, platform console, and related backend capabilities. |
| [lonestar](https://github.com/Lone-Star-Observatories/lonestar) | Private | HTML | LSO workspace and agentic operating framework. |
| [.github](https://github.com/Lone-Star-Observatories/.github) | Public | - | Organization profile, GitHub community health files, and repo map. |

## Product Repositories

| Repository | Visibility | Language | Responsibility |
|---|---:|---|---|
| [bortlebug](https://github.com/Lone-Star-Observatories/bortlebug) | Private | Python | Astrophotography planning and outlook application. |
| [illume-sky](https://github.com/Lone-Star-Observatories/illume-sky) | Private | HTML | Deterministic astronomical product renderer for Illume. |
| [telescope.repair.web](https://github.com/Lone-Star-Observatories/telescope.repair.web) | Private | HTML | Telescope Repair tenant website content, theme, manifest, delivery package, and planning assets. |
| [arby](https://github.com/Lone-Star-Observatories/arby) | Private | PHP | Arbitrage agent tenant for long-running marketplace opportunity monitoring. |
| [scopehound](https://github.com/Lone-Star-Observatories/scopehound) | Private | PHP | Scope opportunity monitoring. |

## Web, Marketing, And Content

| Repository | Visibility | Language | Responsibility |
|---|---:|---|---|
| [webs](https://github.com/Lone-Star-Observatories/webs) | Private | HTML | Website assets and static/WCM source bundles for LSO web surfaces. |
| [marketing](https://github.com/Lone-Star-Observatories/marketing) | Private | HTML | Marketing assets. |
| [lso-claude-marketplace](https://github.com/Lone-Star-Observatories/lso-claude-marketplace) | Private | JavaScript | Claude connectors and plugin marketplace for `aimarket.lonestar.codes`. |

## Infrastructure

| Repository | Visibility | Language | Responsibility |
|---|---:|---|---|
| [awsinfra](https://github.com/Lone-Star-Observatories/awsinfra) | Private | HCL | LSO utility AWS infrastructure, DNS/account context, and shared operational support. |

## Apps, Utilities, And Experiments

| Repository | Visibility | Language | Responsibility |
|---|---:|---|---|
| [ClaudeVision](https://github.com/Lone-Star-Observatories/ClaudeVision) | Private | Swift | Swift application repository. |
| [EbayAuctionReporter](https://github.com/Lone-Star-Observatories/EbayAuctionReporter) | Private | Swift | eBay auction reporting utility. |
| [AmazonOrderReporter](https://github.com/Lone-Star-Observatories/AmazonOrderReporter) | Private | Swift | Amazon order reporting utility. |
| [enterprise](https://github.com/Lone-Star-Observatories/enterprise) | Private | Swift | Swift application repository. |
| [kalshit](https://github.com/Lone-Star-Observatories/kalshit) | Private | Python | Python utility or experiment repository. |
| [nonsenselator](https://github.com/Lone-Star-Observatories/nonsenselator) | Private | JavaScript | Application for interpreting alien languages. |
| [BionicBirb](https://github.com/Lone-Star-Observatories/BionicBirb) | Private | - | Utility or experiment repository. |

## Operating Notes

- Private repository links require access to the `Lone-Star-Observatories`
  GitHub organization.
- Product-specific behavior should stay in product or tenant repositories unless
  it has been intentionally promoted to a reusable Rio Fuego platform primitive.
- Website content should move toward WCM/content-object ownership where
  practical; static bundles are acceptable as migration or delivery artifacts.
- Infrastructure changes should flow through reviewed source, CI/CD, and the
  approved dev/prod QA gates.
