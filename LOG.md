# UltraPay daily log

Newest entry on top. Copy the template, fill it in, and keep each entry short.

<!--
## YYYY-MM-DD (Day N)
**Time:** 30 min
**Covered:**
**Learned:**
**Added to repo:**
**Open questions:**
**Next:**
-->

## 2026-11-02 (Day 1)

**Time:** 30 min
**Covered:** The full manual, in a simplified guide: flow, setup and permissions, payee and bank rules, paying and fees, statuses and accounting, monitoring, error and edge-case reference.
**Learned:**
- UltraPay sends money through Modern Treasury (MT). It never talks to banks directly.
- Four rules: one payment per payee per batch, all-or-nothing, no double pay, outstanding balance in USD only.
- Banks are read from the carrier packet or vendor profile. A changed bank triggers a 48-hour cooling-off.
- A payment can settle in MT and still need attention if marking the bills paid fails. Retry posting fixes that.

**Added to repo:** README with topic tracker, this log.
**Open questions:**
- Is `FEE_EXCEEDS_AMOUNT` also checked when the broker bears the fee (`feeBearer = BROKER`)? The manual only describes it for the payee-bears case.

**Next:** Re-read the payee and bank rules (topic 3) and try to explain them without the guide.
