---
layout: default
---
<p align="center">
  <a href="https://crl-technologies.com/"><img src="/assets/img/logo.png" alt="CRL Technologies" width="80"></a>
</p>

# Incident — Replay / Idempotency
Sintomi: 409 replay; metriche crl_hmac_replay_total↑; x_origin_auth=replay.
Triage: skew ≤ ±300s; key N/N-1; header presenti.
Mitigazione: TTL/idempotency per /v1/order; retry+jitter; hmac_debug sampling.
<hr>
<p align="center"><strong>CRL TECHNOLOGIES, Inc.</strong><br>EIN 61-2277123</p>
