# LithoVault Architecture

## Control plane
- Web, mobile and CLI clients authenticate treasury operators.
- API enforces policy configuration, approval workflows and observability.
- Quantt pipelines evaluate treasury state and emit proposed actions.

## Data plane
- Vault and governance contracts settle on Lithosphere Makalu.
- MultX adapters handle cross-chain treasury instructions.
- DNNS registry maps agents to human-readable identities and zk commitments.

## Security controls
- Multi-sig approval thresholds
- Policy engine and circuit breakers
- Execution simulation and action attestations
- Segregated agent roles
