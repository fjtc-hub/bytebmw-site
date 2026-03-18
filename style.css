:root {
  --bg: #080c11;
  --panel: rgba(255, 255, 255, 0.045);
  --panel-2: rgba(255, 255, 255, 0.06);
  --line: rgba(255, 255, 255, 0.08);
  --text: #eef4fb;
  --muted: #92a3b9;
  --muted-2: #66778f;
  --cyan: #58cfff;
  --blue: #3b82f6;
  --indigo: #5b6cff;
  --ok: #34d399;
  --shadow: 0 28px 90px rgba(0, 0, 0, 0.42);
  --radius: 26px;
  --max: 1120px;
}

* {
  box-sizing: border-box;
}

html {
  scroll-behavior: smooth;
}

body {
  margin: 0;
  min-width: 320px;
  font-family:
    Inter, ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont,
    "Segoe UI", sans-serif;
  color: var(--text);
  -webkit-font-smoothing: antialiased;
  text-rendering: optimizeLegibility;
  background-color: #080c11;
}

a {
  color: inherit;
  text-decoration: none;
}

/* Fondo fibra de carbono */
.bg-layer {
  position: fixed;
  inset: 0;
  overflow: hidden;
  pointer-events: none;
  background:
    linear-gradient(27deg, rgba(255,255,255,0.022) 5px, transparent 5px) 0 5px,
    linear-gradient(207deg, rgba(255,255,255,0.022) 5px, transparent 5px) 10px 0,
    linear-gradient(27deg, rgba(255,255,255,0.012) 5px, transparent 5px) 0 10px,
    linear-gradient(207deg, rgba(255,255,255,0.012) 5px, transparent 5px) 10px 5px,
    linear-gradient(90deg, rgba(255,255,255,0.015) 10px, transparent 10px),
    linear-gradient(
      #0b1016 25%,
      #090d12 25%,
      #090d12 50%,
      #0b1016 50%,
      #0b1016 75%,
      #090d12 75%,
      #090d12
    );
  background-size: 20px 20px;
}

.bg-layer::before {
  content: "";
  position: absolute;
  inset: 0;
  background:
    radial-gradient(circle at 20% 18%, rgba(59,130,246,0.16), transparent 28%),
    radial-gradient(circle at 82% 22%, rgba(34,211,238,0.12), transparent 24%),
    linear-gradient(180deg, rgba(8,12,17,0.18), rgba(8,12,17,0.38));
}

.container {
  width: min(var(--max), calc(100% - 28px));
  margin: 0 auto;
}

.site-header {
  position: sticky;
  top: 0;
  z-index: 30;
  border-bottom: 1px solid var(--line);
  background: rgba(8, 12, 17, 0.82);
  backdrop-filter: blur(16px);
  box-shadow: 0 8px 30px rgba(0, 0, 0, 0.16);
}

.header-row {
  min-height: 74px;
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 18px;
}

.brand {
  display: inline-flex;
  align-items: center;
  gap: 12px;
  min-width: 0;
  position: relative;
  z-index: 2;
}

.brand-mark {
  position: relative;
  width: 42px;
  height: 42px;
  border-radius: 14px;
  border: 1px solid rgba(100, 116, 139, 0.82);
  background: linear-gradient(180deg, #0c1117, #05080c);
  box-shadow:
    0 0 0 3px rgba(255, 255, 255, 0.02),
    0 8px 24px rgba(0, 0, 0, 0.22);
  flex: 0 0 auto;
  overflow: hidden;
}

.brand-core {
  position: absolute;
  inset: 8px;
  border-radius: 8px;
  background:
    linear-gradient(135deg, transparent 0 28%, var(--cyan) 28% 40%, transparent 40% 52%, var(--indigo) 52% 64%, transparent 64%),
    linear-gradient(180deg, rgba(255,255,255,0.12), rgba(255,255,255,0));
}

.brand-text {
  display: grid;
  line-height: 1;
}

.brand-text strong {
  font-size: 16px;
  font-weight: 800;
  letter-spacing: 0.08em;
}

.brand-text small {
  margin-top: 5px;
  color: var(--muted);
  font-size: 10px;
  letter-spacing: 0.18em;
  text-transform: uppercase;
}

/* Acento limpio en barra, sin 3 rayas M */
.header-accent {
  flex: 1;
  max-width: 240px;
  display: flex;
  justify-content: flex-end;
  align-items: center;
}

.header-accent span {
  display: block;
  width: 100%;
  max-width: 180px;
  height: 3px;
  border-radius: 999px;
  background: linear-gradient(
    90deg,
    rgba(88, 207, 255, 0) 0%,
    rgba(88, 207, 255, 0.35) 18%,
    rgba(91, 108, 255, 0.55) 52%,
    rgba(88, 207, 255, 0.2) 100%
  );
  box-shadow:
    0 0 14px rgba(59, 130, 246, 0.14),
    0 0 30px rgba(88, 207, 255, 0.08);
}

.main-shell {
  position: relative;
}

.hero {
  padding: 78px 0 34px;
}

.hero-inner {
  text-align: center;
}

.eyebrow {
  margin: 0;
  color: var(--muted-2);
  font-size: 10px;
  letter-spacing: 0.3em;
  text-transform: uppercase;
}

.hero h1 {
  margin: 18px 0 0;
  font-size: clamp(54px, 11vw, 112px);
  line-height: 0.92;
  letter-spacing: -0.065em;
  font-weight: 900;
  color: #f5f8fd;
  text-shadow:
    0 10px 30px rgba(0, 0, 0, 0.26),
    0 0 30px rgba(59, 130, 246, 0.05);
}

.hero-sub {
  margin: 14px 0 0;
  color: #c8d5e5;
  font-size: 12px;
  letter-spacing: 0.24em;
  text-transform: uppercase;
}

.hero-actions {
  margin-top: 24px;
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  gap: 12px;
}

.btn {
  min-height: 46px;
  padding: 0 18px;
  border-radius: 16px;
  display: inline-flex;
  align-items: center;
  justify-content: center;
  font-size: 13px;
  font-weight: 700;
  transition:
    transform 0.2s ease,
    background 0.2s ease,
    border-color 0.2s ease,
    box-shadow 0.2s ease;
}

.btn:hover {
  transform: translateY(-1px);
}

.btn-primary {
  background: linear-gradient(180deg, var(--blue) 0%, #1d4ed8 100%);
  color: #fff;
  box-shadow:
    0 14px 34px rgba(29, 78, 216, 0.26),
    0 0 0 1px rgba(255, 255, 255, 0.03) inset;
}

.btn-secondary {
  border: 1px solid rgba(255, 255, 255, 0.12);
  background: rgba(255, 255, 255, 0.05);
  color: var(--text);
}

.panel-section {
  padding: 18px 0 28px;
}

.contact-section {
  padding-bottom: 76px;
}

.panel {
  position: relative;
  border: 1px solid var(--line);
  background:
    linear-gradient(180deg, rgba(255, 255, 255, 0.05), rgba(255, 255, 255, 0.036));
  border-radius: var(--radius);
  box-shadow: var(--shadow);
  padding: 24px;
  overflow: hidden;
}

.panel::before {
  content: "";
  position: absolute;
  inset: 0;
  background: linear-gradient(180deg, rgba(255, 255, 255, 0.05), transparent 28%);
  pointer-events: none;
}

.status-panel {
  padding-top: 22px;
}

.panel-head {
  position: relative;
  z-index: 1;
  display: flex;
  align-items: flex-start;
  justify-content: space-between;
  gap: 18px;
}

.panel h2 {
  margin: 10px 0 0;
  font-size: clamp(26px, 4vw, 42px);
  line-height: 1.02;
  letter-spacing: -0.05em;
  font-weight: 760;
}

.status-badge {
  display: inline-flex;
  align-items: center;
  gap: 9px;
  padding: 9px 13px;
  border-radius: 999px;
  border: 1px solid rgba(52, 211, 153, 0.18);
  background: rgba(52, 211, 153, 0.08);
  color: #b8f2de;
  font-size: 12px;
  white-space: nowrap;
}

.status-badge span {
  width: 8px;
  height: 8px;
  border-radius: 999px;
  background: var(--ok);
  box-shadow: 0 0 14px rgba(52, 211, 153, 0.7);
}

.status-list {
  position: relative;
  z-index: 1;
  margin-top: 22px;
  display: grid;
  gap: 12px;
}

.status-item {
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 16px;
  min-height: 58px;
  padding: 0 18px;
  border-radius: 17px;
  border: 1px solid rgba(255, 255, 255, 0.055);
  background:
    linear-gradient(180deg, rgba(255, 255, 255, 0.06), rgba(255, 255, 255, 0.04));
}

.status-item span {
  color: var(--muted);
  font-size: 14px;
}

.status-item strong {
  font-size: 14px;
  font-weight: 700;
  color: #eaf1fb;
}

.contact-panel {
  min-height: 170px;
}

.contact-links {
  position: relative;
  z-index: 1;
  margin-top: 22px;
  display: grid;
  gap: 14px;
}

.contact-links a {
  width: fit-content;
  color: var(--text);
  font-size: 15px;
  border-bottom: 1px solid rgba(255, 255, 255, 0.12);
  padding-bottom: 3px;
}

.site-footer {
  border-top: 1px solid var(--line);
  background: rgba(0, 0, 0, 0.14);
}

.footer-row {
  min-height: 62px;
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 16px;
  color: var(--muted);
  font-size: 13px;
}

.reveal {
  opacity: 0;
  transform: translateY(18px);
  transition:
    opacity 0.55s ease,
    transform 0.55s ease;
}

.reveal.is-visible {
  opacity: 1;
  transform: translateY(0);
}

@media (max-width: 900px) {
  .panel-head {
    flex-direction: column;
    align-items: flex-start;
  }

  .hero {
    padding: 68px 0 26px;
  }

  .header-accent {
    max-width: 160px;
  }

  .header-accent span {
    max-width: 120px;
  }
}

@media (max-width: 640px) {
  .container {
    width: min(var(--max), calc(100% - 20px));
  }

  .header-row {
    min-height: 66px;
  }

  .brand-mark {
    width: 40px;
    height: 40px;
  }

  .hero {
    padding: 56px 0 18px;
  }

  .hero h1 {
    font-size: 58px;
  }

  .hero-sub {
    font-size: 11px;
    letter-spacing: 0.18em;
  }

  .panel {
    padding: 20px;
    border-radius: 22px;
  }

  .panel h2 {
    font-size: 24px;
  }

  .status-item {
    min-height: 54px;
    padding: 0 14px;
  }

  .status-item span,
  .status-item strong {
    font-size: 13px;
  }

  .contact-links a {
    font-size: 14px;
  }

  .header-accent {
    max-width: 90px;
  }

  .header-accent span {
    max-width: 72px;
  }

  .footer-row {
    min-height: 56px;
    font-size: 12px;
  }
}