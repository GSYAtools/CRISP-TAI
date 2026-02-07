# Context Description — Federated Learning

## System overview
- System: Federated Learning with secure aggregation
- Purpose: Train shared models without centralising data
- Users: Model consumers and downstream services
- Deployment: Distributed, long-lived operational environment

## Organisational context
- Clients operated by independent entities
- Central coordinator operated by service provider
- Dedicated security and operations team

## Legal and regulatory context
- Privacy regulation: GDPR
- Constraints: Data minimisation, confidentiality, accountability

## Operational context
- Secure aggregation enabled
- Limited observability of client behaviour
- Continuous training rounds

## Trustworthiness priorities

| Dimension | Priority | Rationale |
|----------|----------|-----------|
| Robustness | High | Adversarial threat model |
| Security | High | Backdoor risk |
| Transparency | Medium | Limited observability |
| Fairness | Medium | Client heterogeneity |

## Revision triggers
- Detection alerts
- Client churn
- Model behaviour degradation
