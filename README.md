# Saoud Bumjaid — GitHub Pages

## ▶ JISRSEC Live App
**https://saoudbumjaid.github.io/JISRSEC/** — no install, any modern browser.

JISRSEC — Cybersecurity Test & Defense Platform: a Purple Team validation platform (graduation project) that
links every controlled Red Team test (Atomic Red Team, OWASP ZAP) to the Blue Team evidence it should have
produced in Wazuh (Sysmon, snoopy, nginx), and measures detection quality (TP / FP / FN / TN).

### What this live app is
- The **real JISRSEC user interface**, running entirely in your browser.
- **All data is real**, recorded from the JISRSEC lab (80 test executions, real Wazuh alerts, real verdicts,
  real PDF reports): a Linux endpoint, a web endpoint (OWASP Juice Shop behind nginx) and a Windows 11 VM with Sysmon.
- **Running a test replays a real recorded lab execution** of that test on that system, step by step
  (pre-checks → execution → waiting for Wazuh → correlation & verdict), with its real command output and
  its real Wazuh alerts. Each replay names the original execution ID and recording time.
- Actions that would change the lab configuration (users, systems, settings) are disabled in this public app.
  Adjudications and notes you add are kept in your browser only.

The platform itself (FastAPI, PostgreSQL, Wazuh, Docker runner) runs in the private lab; its source code is not
published here. No credentials, keys or secrets are included in this site.

---

## ▶ JISRSEC تطبيق مباشر
**https://saoudbumjaid.github.io/JISRSEC/**

واجهة جسرك الحقيقية تعمل في المتصفح، وكل البيانات حقيقية ومسجّلة من مختبر جسرك. تشغيل أي اختبار يعيد تنفيذًا
حقيقيًا مسجّلًا من المختبر خطوة بخطوة مع مخرجاته وتنبيهات Wazuh الحقيقية، ويذكر رقم التنفيذ الأصلي ووقت تسجيله.

## Other projects
- [LUNARIS](https://saoudbumjaid.github.io/LUNARIS/)
