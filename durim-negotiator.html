<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Audi Dispute Negotiator — Durim</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@500;600&family=DM+Sans:wght@300;400;500&display=swap" rel="stylesheet" />
  <style>
    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

    :root {
      --navy: #0d1b2a;
      --navy-mid: #1a2e45;
      --navy-light: #243b55;
      --gold: #c9a84c;
      --gold-light: #e8c97a;
      --gold-pale: #f7edd3;
      --cream: #faf7f2;
      --text-dark: #1a1a1a;
      --text-mid: #4a4a4a;
      --text-muted: #8a8a8a;
      --border: rgba(201,168,76,0.2);
      --border-light: rgba(0,0,0,0.08);
      --red-soft: #fdf0ef;
      --red-mid: #c0392b;
      --green-soft: #f0f7f0;
      --green-mid: #2d7a3a;
    }

    html { scroll-behavior: smooth; }

    body {
      font-family: 'DM Sans', sans-serif;
      background: var(--cream);
      color: var(--text-dark);
      min-height: 100vh;
      overflow-x: hidden;
    }

    /* ── Hero header ── */
    .hero {
      background: var(--navy);
      padding: 3rem 2rem 2.5rem;
      text-align: center;
      position: relative;
      overflow: hidden;
    }
    .hero::before {
      content: '';
      position: absolute;
      inset: 0;
      background: radial-gradient(ellipse at 60% 0%, rgba(201,168,76,0.12) 0%, transparent 65%),
                  radial-gradient(ellipse at 20% 100%, rgba(201,168,76,0.07) 0%, transparent 55%);
      pointer-events: none;
    }
    .hero-eyebrow {
      display: inline-block;
      font-size: 11px;
      font-weight: 500;
      letter-spacing: 0.12em;
      text-transform: uppercase;
      color: var(--gold);
      border: 1px solid rgba(201,168,76,0.35);
      padding: 4px 14px;
      border-radius: 20px;
      margin-bottom: 1rem;
    }
    .hero h1 {
      font-family: 'Playfair Display', serif;
      font-size: clamp(26px, 5vw, 40px);
      font-weight: 600;
      color: #fff;
      line-height: 1.2;
      margin-bottom: 0.75rem;
    }
    .hero h1 span { color: var(--gold-light); }
    .hero p {
      font-size: 15px;
      color: rgba(255,255,255,0.6);
      max-width: 480px;
      margin: 0 auto;
      line-height: 1.6;
    }
    .hero-divider {
      width: 40px;
      height: 2px;
      background: var(--gold);
      margin: 1.5rem auto 0;
      opacity: 0.6;
    }

    /* ── Main layout ── */
    .main { max-width: 760px; margin: 0 auto; padding: 2rem 1.25rem 4rem; }

    /* ── Section labels ── */
    .section-label {
      font-size: 10px;
      font-weight: 500;
      letter-spacing: 0.1em;
      text-transform: uppercase;
      color: var(--gold);
      margin-bottom: 10px;
    }

    /* ── Cards ── */
    .panel {
      background: #fff;
      border: 1px solid var(--border-light);
      border-radius: 14px;
      padding: 1.5rem;
      margin-bottom: 1.25rem;
      box-shadow: 0 2px 12px rgba(0,0,0,0.04);
      animation: fadeUp 0.4s ease both;
    }
    @keyframes fadeUp {
      from { opacity: 0; transform: translateY(10px); }
      to   { opacity: 1; transform: translateY(0); }
    }
    .panel:nth-child(2) { animation-delay: 0.05s; }
    .panel:nth-child(3) { animation-delay: 0.1s; }
    .panel:nth-child(4) { animation-delay: 0.15s; }

    textarea {
      width: 100%;
      border: 1.5px solid var(--border-light);
      border-radius: 10px;
      padding: 12px 14px;
      font-family: 'DM Sans', sans-serif;
      font-size: 14px;
      color: var(--text-dark);
      background: var(--cream);
      resize: vertical;
      line-height: 1.65;
      outline: none;
      transition: border-color 0.2s;
    }
    textarea:focus { border-color: var(--gold); background: #fff; }
    textarea::placeholder { color: var(--text-muted); }

    /* ── Strategy buttons ── */
    .strategy-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(140px, 1fr));
      gap: 8px;
      margin-bottom: 1.25rem;
    }
    .strat-btn {
      padding: 12px 10px;
      border: 1.5px solid var(--border-light);
      border-radius: 10px;
      background: var(--cream);
      cursor: pointer;
      text-align: left;
      transition: all 0.18s;
    }
    .strat-btn:hover {
      border-color: rgba(201,168,76,0.4);
      background: #fff;
      transform: translateY(-1px);
      box-shadow: 0 4px 12px rgba(0,0,0,0.06);
    }
    .strat-btn.active {
      background: var(--navy);
      border-color: var(--gold);
      transform: translateY(-1px);
      box-shadow: 0 4px 16px rgba(13,27,42,0.18);
    }
    .strat-icon { font-size: 18px; display: block; margin-bottom: 6px; }
    .strat-name { display: block; font-weight: 500; font-size: 13px; margin-bottom: 3px; color: var(--text-dark); }
    .strat-desc { display: block; font-size: 11px; color: var(--text-muted); line-height: 1.4; }
    .strat-btn.active .strat-name { color: #fff; }
    .strat-btn.active .strat-desc { color: rgba(255,255,255,0.55); }

    /* ── Generate button ── */
    .gen-btn {
      width: 100%;
      padding: 14px;
      background: var(--navy);
      color: var(--gold-light);
      border: none;
      border-radius: 10px;
      font-family: 'DM Sans', sans-serif;
      font-size: 15px;
      font-weight: 500;
      cursor: pointer;
      letter-spacing: 0.02em;
      transition: all 0.2s;
      position: relative;
      overflow: hidden;
    }
    .gen-btn::after {
      content: '';
      position: absolute;
      inset: 0;
      background: linear-gradient(90deg, transparent, rgba(201,168,76,0.08), transparent);
      transform: translateX(-100%);
      transition: transform 0.6s;
    }
    .gen-btn:hover { background: var(--navy-mid); box-shadow: 0 6px 20px rgba(13,27,42,0.2); }
    .gen-btn:hover::after { transform: translateX(100%); }
    .gen-btn:disabled { background: #ccc; color: #888; cursor: not-allowed; box-shadow: none; }
    .gen-btn:disabled::after { display: none; }

    /* ── Result panel ── */
    .result-panel {
      border: 1.5px solid var(--border);
      border-radius: 14px;
      overflow: hidden;
      margin-top: 1.5rem;
      box-shadow: 0 4px 24px rgba(13,27,42,0.08);
      animation: fadeUp 0.35s ease both;
    }
    .result-header {
      background: var(--navy);
      padding: 14px 1.5rem;
      display: flex;
      align-items: center;
      justify-content: space-between;
      flex-wrap: wrap;
      gap: 8px;
    }
    .result-header-left { display: flex; align-items: center; gap: 8px; }
    .result-badge {
      background: rgba(201,168,76,0.15);
      color: var(--gold-light);
      font-size: 11px;
      font-weight: 500;
      padding: 3px 10px;
      border-radius: 20px;
      border: 1px solid rgba(201,168,76,0.3);
    }
    .result-header span.label { font-size: 13px; color: rgba(255,255,255,0.7); }
    .result-actions { display: flex; gap: 6px; }
    .act-btn {
      padding: 6px 14px;
      border-radius: 8px;
      font-family: 'DM Sans', sans-serif;
      font-size: 12px;
      font-weight: 500;
      cursor: pointer;
      transition: all 0.15s;
      border: 1px solid rgba(201,168,76,0.4);
      background: transparent;
      color: var(--gold-light);
    }
    .act-btn:hover { background: rgba(201,168,76,0.15); }
    .act-btn.primary { background: var(--gold); color: var(--navy); border-color: var(--gold); }
    .act-btn.primary:hover { background: var(--gold-light); }
    .result-body {
      padding: 1.75rem;
      background: #fff;
    }
    .draft-text {
      font-size: 14px;
      line-height: 1.85;
      white-space: pre-wrap;
      color: var(--text-dark);
      font-family: 'DM Sans', sans-serif;
    }

    /* Edit mode */
    .edit-textarea {
      width: 100%;
      min-height: 280px;
      border: 1.5px solid var(--border);
      border-radius: 10px;
      padding: 14px;
      font-family: 'DM Sans', sans-serif;
      font-size: 14px;
      line-height: 1.85;
      color: var(--text-dark);
      background: var(--cream);
      resize: vertical;
      outline: none;
    }
    .edit-textarea:focus { border-color: var(--gold); background: #fff; }
    .edit-save-btn {
      margin-top: 10px;
      padding: 8px 20px;
      background: var(--navy);
      color: var(--gold-light);
      border: none;
      border-radius: 8px;
      font-family: 'DM Sans', sans-serif;
      font-size: 13px;
      font-weight: 500;
      cursor: pointer;
    }
    .edit-save-btn:hover { background: var(--navy-mid); }

    /* Status banners */
    .banner {
      display: flex;
      align-items: flex-start;
      gap: 10px;
      padding: 12px 16px;
      border-radius: 10px;
      font-size: 13px;
      margin-top: 10px;
      line-height: 1.5;
    }
    .banner.success { background: var(--green-soft); color: var(--green-mid); border: 1px solid rgba(45,122,58,0.2); }
    .banner.error   { background: var(--red-soft);   color: var(--red-mid);   border: 1px solid rgba(192,57,43,0.2); }

    /* Loading */
    .loading {
      text-align: center;
      padding: 3rem 1rem;
      color: var(--text-muted);
    }
    .spinner {
      width: 32px; height: 32px;
      border: 2px solid var(--border-light);
      border-top-color: var(--gold);
      border-radius: 50%;
      animation: spin 0.7s linear infinite;
      margin: 0 auto 1rem;
    }
    @keyframes spin { to { transform: rotate(360deg); } }
    .loading p { font-size: 14px; }

    /* Florida lemon law callout */
    .law-callout {
      display: flex;
      gap: 10px;
      background: #fff8ed;
      border: 1px solid rgba(201,168,76,0.3);
      border-radius: 10px;
      padding: 12px 14px;
      font-size: 12.5px;
      color: #7a5c1e;
      line-height: 1.55;
      margin-bottom: 1.25rem;
    }
    .law-callout strong { display: block; margin-bottom: 3px; color: #5a3e0e; }

    /* Footer */
    .footer {
      text-align: center;
      padding: 2rem 1rem;
      font-size: 12px;
      color: var(--text-muted);
      border-top: 1px solid var(--border-light);
      margin-top: 3rem;
    }
    .footer a { color: var(--gold); text-decoration: none; }

    /* History */
    .history-section { margin-top: 2rem; }
    .history-title { font-size: 11px; font-weight: 500; letter-spacing: 0.1em; text-transform: uppercase; color: var(--text-muted); margin-bottom: 10px; }
    .hist-item {
      padding: 10px 14px;
      background: #fff;
      border: 1px solid var(--border-light);
      border-radius: 8px;
      font-size: 13px;
      color: var(--text-mid);
      margin-bottom: 6px;
      cursor: pointer;
      transition: all 0.15s;
    }
    .hist-item:hover { border-color: rgba(201,168,76,0.35); color: var(--text-dark); }
    .hist-item strong { color: var(--text-dark); display: block; margin-bottom: 2px; }

    @media (max-width: 520px) {
      .strategy-grid { grid-template-columns: 1fr 1fr; }
      .result-header { flex-direction: column; align-items: flex-start; }
    }
  </style>
</head>
<body>

<div class="hero">
  <div class="hero-eyebrow">Powered by Claude AI</div>
  <h1>Your <span>Audi Dispute</span><br>Negotiation Assistant</h1>
  <p>Paste their latest email. Pick your strategy. Get a professional draft in seconds — then review and send.</p>
  <div class="hero-divider"></div>
</div>

<div class="main">

  <!-- Lemon law callout -->
  <div class="law-callout">
    <span style="font-size:18px;flex-shrink:0;">⚖️</span>
    <div>
      <strong>Florida Lemon Law — know your rights</strong>
      3+ repair attempts for the same defect, OR 30+ cumulative days out of service within 24 months / 24,000 miles qualifies your vehicle. The manufacturer may owe you a replacement or full refund.
    </div>
  </div>

  <!-- Step 1 -->
  <div class="panel">
    <div class="section-label">Step 1 — Paste their email</div>
    <textarea id="emailInput" rows="8" placeholder="Paste the dealership or Audi customer care email here..."></textarea>
  </div>

  <!-- Step 2 -->
  <div class="panel">
    <div class="section-label">Step 2 — Choose your strategy</div>
    <div class="strategy-grid">
      <button class="strat-btn active" data-strat="firm" onclick="selectStrat(this)">
        <span class="strat-icon">⚖️</span>
        <span class="strat-name">Firm & Legal</span>
        <span class="strat-desc">Reference lemon law, escalate pressure</span>
      </button>
      <button class="strat-btn" data-strat="loaner" onclick="selectStrat(this)">
        <span class="strat-icon">🚗</span>
        <span class="strat-name">Demand Loaner</span>
        <span class="strat-desc">Require transportation while car is in shop</span>
      </button>
      <button class="strat-btn" data-strat="compensation" onclick="selectStrat(this)">
        <span class="strat-icon">💰</span>
        <span class="strat-name">Seek Compensation</span>
        <span class="strat-desc">Request refund, repair cost coverage, or discount</span>
      </button>
      <button class="strat-btn" data-strat="escalate" onclick="selectStrat(this)">
        <span class="strat-icon">📣</span>
        <span class="strat-name">Escalate to Corp</span>
        <span class="strat-desc">Threaten BBB, NHTSA report, or attorney</span>
      </button>
      <button class="strat-btn" data-strat="diplomatic" onclick="selectStrat(this)">
        <span class="strat-icon">🤝</span>
        <span class="strat-name">Diplomatic</span>
        <span class="strat-desc">Collaborative tone, seek mutual resolution</span>
      </button>
    </div>

    <div class="section-label" style="margin-top:0.5rem;">Step 3 — Add context (optional)</div>
    <textarea id="contextInput" rows="2" placeholder="e.g. Car has been in the shop 3 weeks, same issue occurred twice before, have all service invoices..."></textarea>
  </div>

  <button class="gen-btn" id="genBtn" onclick="generateDraft()">✦ Draft my response</button>

  <div id="resultArea"></div>
  <div id="historyArea"></div>
</div>

<div class="footer">
  Built with Claude AI &nbsp;·&nbsp; <a href="https://osvaldofabelo.github.io" target="_blank">Baseline Mind &amp; Wellness</a>
</div>

<script>
  let selectedStrat = 'firm';
  let draftHistory = [];

  const stratDesc = {
    firm:         'Firm & Legal — references Florida Lemon Law and consumer protection rights, demands concrete action',
    loaner:       'Demand transportation — insists on loaner vehicle or rental reimbursement for every day the car is unavailable',
    compensation: 'Compensation-focused — requests financial remedy for inconvenience, lost time, and repair costs',
    escalate:     'Escalation threat — references BBB complaint, NHTSA safety report, state attorney general, and legal counsel',
    diplomatic:   'Diplomatic — constructive and collaborative tone, seeking good-faith resolution while documenting everything'
  };

  function selectStrat(el) {
    document.querySelectorAll('.strat-btn').forEach(b => b.classList.remove('active'));
    el.classList.add('active');
    selectedStrat = el.dataset.strat;
  }

  async function generateDraft() {
    const email = document.getElementById('emailInput').value.trim();
    if (!email) {
      showResult(`<div class="banner error">⚠ Please paste their email in Step 1 first.</div>`);
      return;
    }
    const context = document.getElementById('contextInput').value.trim();
    const btn = document.getElementById('genBtn');
    btn.disabled = true;
    btn.textContent = 'Drafting…';

    showResult(`
      <div class="result-panel" style="margin-top:1.5rem;">
        <div class="loading">
          <div class="spinner"></div>
          <p>Claude is analyzing the email and crafting your response…</p>
        </div>
      </div>`);

    try {
      const response = await fetch('https://api.anthropic.com/v1/messages', {
        method: 'POST',
        headers: { 'Content-Type': 'application/json', 'x-api-key': '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', 'anthropic-version': '2023-06-01', 'anthropic-dangerous-direct-browser-access': 'true' },
        body: JSON.stringify({
          model: 'claude-sonnet-4-20250514',
          max_tokens: 1000,
          system: `You are an expert automotive consumer rights advocate and negotiation specialist. Your job is to help a car owner named Durim draft firm, professional email responses to an Audi dealership. His Audi has been in the shop for multiple weeks with recurring problems.

Strategy: ${stratDesc[selectedStrat]}

Rules:
- Write in first person as Durim
- Professional and assertive — never hostile or rude
- Reference Florida Lemon Law when relevant (3+ repair attempts same issue, or 30+ cumulative days out of service within 24 months/24,000 miles)
- Keep emails 200–350 words
- Include one clear, specific ask or demand
- End with a firm but reasonable deadline or next step
- Format: Subject line on first line, then blank line, then greeting, body paragraphs, sign-off as "Durim"
- Do NOT use placeholder brackets like [Your Name] or [Date] — use "Durim" as sender and today's date if needed`,
          messages: [{
            role: 'user',
            content: `Their email:\n${email}${context ? `\n\nMy situation context:\n${context}` : ''}\n\nDraft a strategic response for me to review and send.`
          }]
        })
      });

      const data = await response.json();
      if (!response.ok) throw new Error(data.error?.message || 'API error');
      const draft = data.content.map(b => b.text || '').filter(Boolean).join('');

      draftHistory.unshift({ strat: selectedStrat, preview: email.slice(0, 70) + '…', draft });
      renderDraft(draft);
      renderHistory();
    } catch (err) {
      showResult(`<div class="banner error" style="margin-top:1.5rem;">⚠ Something went wrong: ${err.message}. Please try again.</div>`);
    }

    btn.disabled = false;
    btn.textContent = '✦ Draft my response';
  }

  function renderDraft(draft) {
    document.getElementById('resultArea').innerHTML = `
      <div class="result-panel">
        <div class="result-header">
          <div class="result-header-left">
            <span class="result-badge">Draft ready</span>
            <span class="label">Review before sending</span>
          </div>
          <div class="result-actions">
            <button class="act-btn" onclick="enableEdit()">Edit</button>
            <button class="act-btn" onclick="copyOnly()">Copy</button>
            <button class="act-btn primary" onclick="approveDraft()">✓ Approve &amp; copy</button>
          </div>
        </div>
        <div class="result-body">
          <div class="draft-text" id="draftContent">${escHtml(draft)}</div>
        </div>
      </div>
      <div id="approvalMsg"></div>`;
  }

  function enableEdit() {
    const val = document.getElementById('draftContent').innerText;
    document.querySelector('.result-body').innerHTML = `
      <textarea class="edit-textarea" id="editArea">${escHtml(val)}</textarea>
      <button class="edit-save-btn" onclick="saveEdit()">Save edits</button>`;
  }

  function saveEdit() {
    const val = document.getElementById('editArea').value;
    if (draftHistory[0]) draftHistory[0].draft = val;
    document.querySelector('.result-body').innerHTML = `<div class="draft-text" id="draftContent">${escHtml(val)}</div>`;
  }

  function copyOnly() {
    const text = document.getElementById('draftContent')?.innerText || '';
    navigator.clipboard.writeText(text).catch(() => fallbackCopy(text));
    document.getElementById('approvalMsg').innerHTML = `<div class="banner success">✓ Copied to clipboard.</div>`;
    setTimeout(() => { const m = document.getElementById('approvalMsg'); if(m) m.innerHTML=''; }, 3000);
  }

  function approveDraft() {
    const text = document.getElementById('draftContent')?.innerText || '';
    navigator.clipboard.writeText(text).catch(() => fallbackCopy(text));
    document.getElementById('approvalMsg').innerHTML = `
      <div class="banner success">
        ✓ Email copied to clipboard — paste it into Gmail or your email client and hit send when ready.
      </div>`;
  }

  function fallbackCopy(text) {
    const ta = document.createElement('textarea');
    ta.value = text;
    document.body.appendChild(ta);
    ta.select();
    document.execCommand('copy');
    document.body.removeChild(ta);
  }

  function renderHistory() {
    if (draftHistory.length < 2) { document.getElementById('historyArea').innerHTML = ''; return; }
    let html = '<div class="history-section"><div class="history-title">Previous drafts this session</div>';
    draftHistory.slice(1).forEach((h, i) => {
      html += `<div class="hist-item" onclick="loadHistory(${i+1})">
        <strong>${stratDesc[h.strat].split('—')[0].trim()}</strong>
        Re: "${h.preview}"
      </div>`;
    });
    html += '</div>';
    document.getElementById('historyArea').innerHTML = html;
  }

  function loadHistory(idx) {
    renderDraft(draftHistory[idx].draft);
    window.scrollTo({ top: document.getElementById('resultArea').offsetTop - 20, behavior: 'smooth' });
  }

  function showResult(html) { document.getElementById('resultArea').innerHTML = html; }
  function escHtml(s) { return s.replace(/&/g,'&amp;').replace(/</g,'&lt;').replace(/>/g,'&gt;'); }
</script>
</body>
</html>
