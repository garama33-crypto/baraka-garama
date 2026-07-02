# Validation Approach

## Scenario 1

Incoming call routed to primary node.

Expected Result:
Successful call completion.

## Scenario 2

Primary node does not answer.

Expected Result:
Secondary node selected by the SBC.

## Scenario 3

Outgoing call originated from a SIP Application Server.

Expected Result:
Successful routing through SBC.

## Scenario 4

Primary node unavailable.

Expected Result:
Routing behavior validated according to configured failover policies.
