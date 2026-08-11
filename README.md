<p align="center">
  <h1 align="center">Do Debate Models Learn Human Spot-Check Habits</h1>
  <p align="center"><strong>Test whether debate setups let models learn and exploit human spot-checking patterns.</strong></p>
</p>

---

## Overview

This repository implements experimental profiles for **Do Debate Models Learn Human Spot-Check Habits**. Config, caching, hooks, metrics, ablations, reporting, and CI support local pilots on small open-weight models.

Hypothesis (one line): Test whether debate setups let models learn and exploit human spot-checking patterns.

## Status

Shared infrastructure is in place; domain stages must pass harness validation before any measured claim.

| Command | Purpose |
|---|---|
| `make install-dev` | editable install + pinned requirements |
| `make test` | full unit suite |
| `make ci` | lint + test + typecheck |
| `make pilot` | end-to-end pilot profile |
