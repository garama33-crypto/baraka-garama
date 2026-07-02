# Lessons Learned

## Configuration Consistency

Maintaining identical configurations across SIP Application Servers reduced operational complexity.

## Centralized Routing

Keeping routing intelligence within the SBC simplified troubleshooting and failover validation.

## Provisioning Dependency

Routing behavior depended not only on SIP configuration but also on orchestration and provisioning policies.

## Validation Strategy

The most effective validation scenarios were:

- Incoming calls
- Outgoing calls
- No-answer scenarios
- Secondary node selection
- Primary node unavailable scenarios
