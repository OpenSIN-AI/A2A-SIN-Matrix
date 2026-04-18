# A2A-SIN-Matrix Boundaries

## Role
`A2A-SIN-Matrix` owns Matrix messaging integration, encrypted chat workflows, and Matrix-specific contracts.

## This repo should own
- Matrix messaging routing, coordination, and automation flows
- Matrix evidence, recovery, auth, and session handling
- Matrix contracts used by downstream automation agents
- runbooks tied to encrypted chat-platform automation and monitoring

## This repo must not own
- unrelated messaging platform logic
- organization SSOT docs or architecture canon
- downstream business logic unrelated to Matrix ownership

## Hard rules
- Keep changes scoped to Matrix messaging integration and monitoring.
- Move non-Matrix behavior back to the repos that own it.
- Keep reusable contracts focused on encrypted chat coordination and monitoring.
