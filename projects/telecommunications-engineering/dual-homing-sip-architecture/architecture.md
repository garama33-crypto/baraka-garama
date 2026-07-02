# Architecture

                IMS Network
                     |
                     |
                    SBC
                  /     \
                 /       \
          SIP-AS-1     SIP-AS-2

## Design Principle

The SBC controls routing decisions.

Application Servers process calls but do not perform failover decisions.
