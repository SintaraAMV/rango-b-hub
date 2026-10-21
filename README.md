# Rango B

Rango B is a collection of small, clearly scoped digital services focused on solving concrete technical problems with verifiable results.

The system is currently in pre-launch development and internal validation.

## Current Service

### Bugfix Express

A focused service for diagnosing and fixing a bounded software defect in an existing application.

Typical workflow:

`Reproduce → Isolate → Root Cause → Minimal Fix → Tests → Validation → Delivery`

The goal is not to rewrite an application, but to identify the actual cause of a specific defect, apply the smallest reasonable correction, and verify that the affected flow works correctly.

## Technical Demos

Two Bugfix Express demonstrations are currently available.

### Demo 01 — Basic

A small controlled case used to validate the fundamental Bugfix Express workflow.

**Problem:** order creation failed when an optional coupon code was omitted.

**Result:** the root cause was isolated, a minimal fix was implemented, and regression tests confirmed both the corrected case and the previously working coupon flow.

Repository:

https://github.com/SintaraAMV/rango-b-bugfix-demo-basic

---

### Demo 02 — Realistic

A more realistic application scenario designed to represent the type of debugging work that may occur in an actual client project.

The demo includes:

- frontend and backend interaction;
- persistent application state;
- a non-obvious defect;
- multiple initially plausible hypotheses;
- root-cause investigation;
- minimal code correction;
- regression testing;
- before/after evidence.

Repository:

https://github.com/SintaraAMV/rango-b-bugfix-demo-realistic

## Status

### Bugfix Express

- Operational workflow: developed
- Basic technical demo: completed
- Realistic technical demo: completed
- Full client simulation: pending final validation

### Other Rango B Services

Planned:

- Technical Diagnosis
- Deploy Express

These services will be added after their operational workflows, demos, and simulations are validated.

## Principles

Rango B is built around a few operating principles:

- clearly bounded scope;
- reproducible problems;
- evidence-based debugging;
- minimal reasonable changes;
- technical and functional validation;
- documented delivery;
- no unnecessary expansion of scope.

AI tools may assist analysis and implementation, but the final result is validated through execution, tests, logs, and observable application behavior.

## Repository Structure

This repository acts as the central index for Rango B.

Individual technical demos and future service examples are maintained in separate repositories to preserve independent Git history, tests, and evidence.

## Disclaimer

All current examples are technical demonstrations created for internal validation and portfolio evidence.

They do not represent real client projects or client data.