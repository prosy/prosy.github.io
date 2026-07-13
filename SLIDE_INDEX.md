# Slide Bank — index (mirrors Qualifications_Bank)

Each slide is a reusable asset. Assemble per-JD cuts in `build_deck.py` CUTS.

| id | title | tags | bank rows | in cuts |
| :-- | :-- | :-- | :-- | :-- |
| `surface` | An AI-native shopping surface. | surface, agentic-commerce | AAI-01, AAI-07, CONV-01 | full,amazon-walkthrough |
| `flights-work` | The agent, working. | surface, ranking, personalization, agentic-commerce | AAI-07, AAI-01, USR-06 | full,amazon-walkthrough,amazon-hook |
| `marketplace` | A two-sided agent marketplace. | two-sided-marketplace, agentic-commerce, ranking | AAI-01, AAI-12, AAI-03, AAI-17 | full,amazon-walkthrough |
| `agents-team` | Your team of agents. | two-sided-marketplace, personalization | AAI-02, AAI-12, USR-06 | full |
| `agents-deploy` | Deploy brands as your agents. | two-sided-marketplace | AAI-02, AAI-03 | full |
| `agents-multi` | Multi-category supply. | two-sided-marketplace | AAI-12 | full |
| `brand-agent-turkish` | A brand, running as an agent. | agentic-commerce, two-sided-marketplace, transact | AAI-02, AAI-04, LEAD-10 | full,amazon-walkthrough |
| `brand-agent-alaska` | Live fares, real traction. | agentic-commerce, two-sided-marketplace, experiments, monetization | AAI-02, AAI-17 | full,amazon-walkthrough |
| `brand-agent-marriott` | Hotels, as agents too. | agentic-commerce, two-sided-marketplace | AAI-02 | full |
| `checkout` | Safe agent checkout. | transact, monetization, agentic-commerce, trust | AAI-05, AAI-06, AAI-04 | full,amazon-walkthrough,amazon-hook |
| `hotels-search` | Hotels, same surface. | surface, ranking, agentic-commerce | AAI-07, USR-06 | full |
| `hotels-detail` | A hotel, in depth. | surface, agentic-commerce | AAI-01 | full |
| `watchers` | Agents that work while you don't. | autonomous, agentic-commerce, experiments | AAI-01 | full,amazon-walkthrough |
| `pref-declared` | Declared preferences. | personalization, ranking | USR-02, USR-05, USR-06 | full |
| `pref-inferred` | Declared + inferred, kept honest. | personalization, ranking, trust | USR-06, USR-02, DARC-02 | full,amazon-walkthrough |
| `data-ingest` | A profile that builds itself. | data-ingestion, personalization | USR-05, DATA-05, DATA-04 | full |
| `loyalty` | Loyalty, in one place. | data-ingestion, personalization | USR-06, USR-01 | full |
| `channels` | Meet the user where they are. | surface, trust | CONV-06, USR-04 | full |
| `control` | User-owned control. | trust | USR-03 | full |
| `trust` | Sensitive data, encrypted. | trust | USR-01, USR-03 | full |
| `trips` | Every trip in one place. | surface, data-ingestion | — | full |
| `social` | Travel is social. | social | PLG-04 | full |
| `pov-amazon` | The bet, and what's next. | judgment, single-threaded-owner, monetization | LEAD-02, LEAD-09, LEAD-10 | amazon-walkthrough,amazon-hook |

## Cuts

- **full** (`/`): opener → surface → marketplace → agents-team → agents-deploy → agents-multi → brand-agent-turkish → brand-agent-alaska → brand-agent-marriott → flights-work → checkout → hotels-search → hotels-detail → watchers → pref-declared → pref-inferred → data-ingest → loyalty → channels → control → trust → trips → social → close
- **amazon-walkthrough** (`/amazon/`): opener → surface → flights-work → marketplace → brand-agent-turkish → brand-agent-alaska → checkout → pref-inferred → watchers → pov-amazon → close
- **amazon-hook** (`/amazon/hook/`): opener → flights-work → checkout → pov-amazon → close
