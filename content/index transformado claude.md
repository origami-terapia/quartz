---
title: Bruno Ferraz | Psicólogo Clínico
description: Psicoterapia individual com escuta humanizada, criatividade e presença. Atendimento online e presencial no Rio de Janeiro.
tags:
  - psicologia
  - psicoterapia
  - origamiterapia
  - saúde mental
draft: false
---

<style>
:root {
  --sage: #7a9e87;
  --sage-dark: #4e7259;
  --sage-light: #b4cbb9;
  --cream: #f5f0e8;
  --stone: #8a8178;
  --ink: #1e1d1b;
  --gold: #c8a96e;
  --gold-light: #e8d5b0;
  --font-display: 'Cormorant Garamond', Georgia, serif;
}

/* Reset article padding para landing full-width */
.page-content, article.popover-hint {
  max-width: 100% !important;
  padding: 0 !important;
}

/* ── HERO ── */
.lp-hero {
  background: linear-gradient(135deg, #f5f0e8 0%, #faf8f4 60%, #eef4f0 100%);
  padding: 80px 40px 80px;
  text-align: center;
  position: relative;
  overflow: hidden;
  border-bottom: 1px solid rgba(122,158,135,0.2);
}

.lp-hero::before {
  content: '';
  position: absolute;
  top: -100px; left: 50%;
  transform: translateX(-50%);
  width: 600px; height: 600px;
  background: radial-gradient(circle, rgba(122,158,135,0.1) 0%, transparent 70%);
  border-radius: 50%;
  pointer-events: none;
}

.lp-eyebrow {
  font-size: 0.72rem;
  letter-spacing: 0.2em;
  text-transform: uppercase;
  color: var(--sage);
  margin-bottom: 20px;
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 10px;
}

.lp-eyebrow::before, .lp-eyebrow::after {
  content: '';
  display: block;
  width: 24px; height: 1px;
  background: var(--sage);
}

.lp-hero h1 {
  font-family: var(--font-display);
  font-size: clamp(2.2rem, 5vw, 3.8rem);
  font-weight: 400;
  line-height: 1.15;
  color: var(--ink);
  margin: 0 auto 24px;
  max-width: 700px;
  border: none !important;
}

.lp-hero h1 em {
  font-style: italic;
  color: var(--sage-dark);
}

.lp-hero-sub {
  font-size: 1.05rem;
  color: var(--stone);
  max-width: 500px;
  margin: 0 auto 40px;
  line-height: 1.75;
}

.lp-cta-group {
  display: flex;
  gap: 16px;
  justify-content: center;
  flex-wrap: wrap;
  margin-bottom: 48px;
}

.lp-btn {
  display: inline-flex;
  align-items: center;
  gap: 8px;
  background: var(--sage-dark);
  color: #fff !important;
  font-size: 0.85rem;
  font-weight: 500;
  letter-spacing: 0.08em;
  text-transform: uppercase;
  padding: 15px 30px;
  border-radius: 2px;
  text-decoration: none !important;
  transition: background 0.3s, transform 0.2s;
}

.lp-btn:hover { background: var(--sage); transform: translateY(-1px); }

.lp-btn-outline {
  display: inline-flex;
  align-items: center;
  gap: 8px;
  background: transparent;
  color: var(--stone) !important;
  font-size: 0.82rem;
  letter-spacing: 0.1em;
  text-transform: uppercase;
  padding: 15px 24px;
  border: 1px solid rgba(122,158,135,0.4);
  border-radius: 2px;
  text-decoration: none !important;
  transition: all 0.3s;
}

.lp-btn-outline:hover {
  border-color: var(--sage-dark);
  color: var(--sage-dark) !important;
}

.lp-trust {
  display: flex;
  gap: 28px;
  justify-content: center;
  flex-wrap: wrap;
  padding-top: 32px;
  border-top: 1px solid rgba(122,158,135,0.2);
}

.lp-trust-item {
  font-size: 0.8rem;
  color: var(--stone);
  display: flex;
  align-items: center;
  gap: 6px;
}

.lp-trust-item::before { content: '✓'; color: var(--sage); }

/* ── SECTIONS ── */
.lp-section {
  padding: 80px 40px;
  max-width: 1100px;
  margin: 0 auto;
}

.lp-section-cream {
  background: var(--cream);
  padding: 80px 40px;
}

.lp-section-cream > .lp-section-inner {
  max-width: 1100px;
  margin: 0 auto;
}

.lp-section-dark {
  background: var(--sage-dark);
  padding: 80px 40px;
  color: white;
}

.lp-section-dark > .lp-section-inner {
  max-width: 1100px;
  margin: 0 auto;
}

.lp-label {
  font-size: 0.72rem;
  letter-spacing: 0.18em;
  text-transform: uppercase;
  color: var(--sage);
  display: flex;
  align-items: center;
  gap: 10px;
  margin-bottom: 16px;
}

.lp-label::before {
  content: '';
  display: block;
  width: 20px; height: 1px;
  background: var(--sage);
}

.lp-label-light { color: var(--gold-light) !important; }
.lp-label-light::before { background: var(--gold-light) !important; }

.lp-h2 {
  font-family: var(--font-display);
  font-size: clamp(1.8rem, 3vw, 2.6rem);
  font-weight: 400;
  line-height: 1.2;
  color: var(--ink);
  margin-bottom: 20px !important;
  border: none !important;
}

.lp-h2 em { font-style: italic; color: var(--sage-dark); }
.lp-h2-light { color: white !important; }
.lp-h2-light em { color: var(--gold-light) !important; }

/* ── ABOUT GRID ── */
.lp-about-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 64px;
  align-items: start;
}

.lp-about-text p {
  color: #3a3732;
  line-height: 1.8;
  margin-bottom: 16px;
  font-size: 1rem;
}

.lp-credentials {
  display: flex;
  flex-direction: column;
  gap: 16px;
}

.lp-cred {
  display: flex;
  gap: 14px;
  padding: 18px 20px;
  background: #faf8f4;
  border-left: 3px solid var(--sage);
  border-radius: 0 4px 4px 0;
  transition: transform 0.3s;
}

.lp-cred:hover { transform: translateX(4px); }

.lp-cred-icon { font-size: 1.3rem; flex-shrink: 0; }

.lp-cred h4 {
  font-family: var(--font-display);
  font-size: 1rem;
  font-weight: 500;
  color: var(--ink);
  margin: 0 0 4px !important;
}

.lp-cred p {
  font-size: 0.82rem;
  color: var(--stone);
  line-height: 1.5;
  margin: 0 !important;
}

/* ── CARDS ── */
.lp-cards {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 24px;
  margin-top: 48px;
}

.lp-card {
  padding: 32px 26px;
  border: 1px solid rgba(122,158,135,0.2);
  border-radius: 8px;
  background: #faf8f4;
  position: relative;
  overflow: hidden;
  transition: transform 0.3s, box-shadow 0.3s;
}

.lp-card::before {
  content: '';
  position: absolute;
  top: 0; left: 0; right: 0;
  height: 3px;
  background: linear-gradient(90deg, var(--sage), var(--sage-light));
  transform: scaleX(0);
  transform-origin: left;
  transition: transform 0.4s ease;
}

.lp-card:hover::before { transform: scaleX(1); }
.lp-card:hover { transform: translateY(-4px); box-shadow: 0 16px 48px rgba(0,0,0,0.08); }

.lp-card-num {
  font-family: var(--font-display);
  font-size: 2.8rem;
  font-weight: 300;
  color: var(--sage-light);
  line-height: 1;
  margin-bottom: 14px;
}

.lp-card h3 {
  font-family: var(--font-display);
  font-size: 1.15rem;
  font-weight: 500;
  color: var(--ink);
  margin-bottom: 10px !important;
  border: none !important;
}

.lp-card p {
  font-size: 0.88rem;
  color: var(--stone);
  line-height: 1.7;
  margin: 0 !important;
}

/* ── HIGHLIGHT (dark section) ── */
.lp-highlight-grid {
  display: grid;
  grid-template-columns: 1.2fr 1fr;
  gap: 64px;
  align-items: center;
}

.lp-highlight-text p {
  color: rgba(255,255,255,0.75);
  line-height: 1.8;
  margin-bottom: 14px;
  font-size: 0.98rem;
}

.lp-list {
  list-style: none;
  padding: 0;
  margin: 0;
  display: flex;
  flex-direction: column;
  gap: 12px;
}

.lp-list li {
  display: flex;
  align-items: flex-start;
  gap: 10px;
  font-size: 0.92rem;
  color: rgba(255,255,255,0.85);
}

.lp-list li::before { content: '◇'; color: var(--gold); flex-shrink: 0; margin-top: 2px; }

.lp-btn-gold {
  display: inline-block;
  background: var(--gold);
  color: var(--ink) !important;
  font-size: 0.83rem;
  font-weight: 500;
  letter-spacing: 0.08em;
  text-transform: uppercase;
  padding: 14px 28px;
  border-radius: 2px;
  text-decoration: none !important;
  margin-top: 28px;
  transition: background 0.3s;
}

.lp-btn-gold:hover { background: var(--gold-light); }

/* ── ISSUES GRID ── */
.lp-issues {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 14px;
  margin-top: 44px;
}

.lp-issue {
  padding: 18px 14px;
  border: 1px solid rgba(122,158,135,0.25);
  border-radius: 8px;
  background: #faf8f4;
  text-align: center;
  font-size: 0.86rem;
  color: #3a3732;
  line-height: 1.4;
  transition: background 0.3s, color 0.3s;
  cursor: default;
}

.lp-issue:hover { background: var(--sage-dark); color: white; }
.lp-issue-icon { display: block; font-size: 1.4rem; margin-bottom: 8px; }

/* ── STEPS ── */
.lp-steps {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 24px;
  margin-top: 56px;
  text-align: center;
}

.lp-step-num {
  width: 52px; height: 52px;
  border: 2px solid var(--sage);
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: var(--font-display);
  font-size: 1.15rem;
  color: var(--sage-dark);
  margin: 0 auto 16px;
}

.lp-step h4 {
  font-family: var(--font-display);
  font-size: 1rem;
  font-weight: 500;
  color: var(--ink);
  margin-bottom: 8px !important;
}

.lp-step p {
  font-size: 0.82rem;
  color: var(--stone);
  line-height: 1.6;
  margin: 0 !important;
}

/* ── TESTIMONIALS ── */
.lp-testimonials {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 24px;
  margin-top: 52px;
}

.lp-testimonial {
  background: #faf8f4;
  border-radius: 8px;
  padding: 30px 26px;
  border: 1px solid rgba(122,158,135,0.15);
  position: relative;
}

.lp-testimonial::before {
  content: '\201C';
  font-family: var(--font-display);
  font-size: 4.5rem;
  color: var(--sage-light);
  line-height: 1;
  position: absolute;
  top: 10px; left: 18px;
  opacity: 0.4;
}

.lp-testimonial-text {
  font-size: 0.9rem;
  color: #3a3732;
  line-height: 1.75;
  margin-bottom: 18px;
  padding-top: 24px;
  font-style: italic;
}

.lp-author { display: flex; align-items: center; gap: 10px; }

.lp-avatar {
  width: 34px; height: 34px;
  background: var(--sage-light);
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 0.88rem;
  color: var(--sage-dark);
  font-weight: 500;
  flex-shrink: 0;
}

.lp-author-info strong { display: block; font-size: 0.82rem; color: var(--ink); }
.lp-author-info span  { font-size: 0.75rem; color: var(--stone); }

/* ── CTA FINAL ── */
.lp-cta-final {
  text-align: center;
  padding: 100px 40px;
  background: #faf8f4;
  position: relative;
  overflow: hidden;
}

.lp-cta-final::before {
  content: '';
  position: absolute;
  top: 50%; left: 50%;
  transform: translate(-50%, -50%);
  width: 500px; height: 500px;
  background: radial-gradient(circle, rgba(122,158,135,0.07) 0%, transparent 70%);
  border-radius: 50%;
  pointer-events: none;
}

.lp-cta-final h2 {
  font-family: var(--font-display);
  font-size: clamp(1.8rem, 3vw, 2.6rem);
  font-weight: 400;
  color: var(--ink);
  margin-bottom: 16px !important;
  border: none !important;
}

.lp-cta-final h2 em { font-style: italic; color: var(--sage-dark); }

.lp-cta-final p {
  color: var(--stone);
  max-width: 460px;
  margin: 0 auto 40px;
  line-height: 1.75;
  font-size: 1rem;
}

.lp-cta-buttons {
  display: flex;
  gap: 16px;
  justify-content: center;
  flex-wrap: wrap;
}

/* ── RESPONSIVE ── */
@media (max-width: 800px) {
  .lp-hero, .lp-section, .lp-section-cream, .lp-section-dark, .lp-cta-final {
    padding-left: 20px !important;
    padding-right: 20px !important;
  }
  .lp-about-grid, .lp-highlight-grid { grid-template-columns: 1fr; gap: 40px; }
  .lp-cards, .lp-testimonials { grid-template-columns: 1fr; }
  .lp-issues { grid-template-columns: repeat(2, 1fr); }
  .lp-steps { grid-template-columns: repeat(2, 1fr); }
  .lp-trust { gap: 16px; }
}

@media (max-width: 480px) {
  .lp-issues { grid-template-columns: 1fr 1fr; }
  .lp-cta-buttons, .lp-cta-group { flex-direction: column; align-items: center; }
  .lp-steps { grid-template-columns: 1fr 1fr; }
}
</style>

<!-- ═══════════════════════════════════════ -->
<!--  HERO                                  -->
<!-- ═══════════════════════════════════════ -->
<div class="lp-hero">
  <div class="lp-eyebrow">Psicólogo Clínico · CRP 05/xxxxx · Rio de Janeiro</div>
  <h1 class="lp-hero-h1" style="font-family:'Cormorant Garamond',Georgia,serif;font-size:clamp(2.2rem,5vw,3.8rem);font-weight:400;line-height:1.15;color:#1e1d1b;margin:0 auto 24px;max-width:700px;border:none;">
    Um espaço para <em style="font-style:italic;color:#4e7259;">cuidar</em> de quem você é
  </h1>
  <p class="lp-hero-sub">Psicoterapia individual com escuta humanizada, criatividade e presença.<br>Atendimento online e presencial no Rio de Janeiro.</p>
  <div class="lp-cta-group">
    <a href="https://wa.me/5521994668971?text=Ol%C3%A1%2C%20Bruno.%20Vim%20pelo%20seu%20site%20e%20gostaria%20de%20saber%20mais%20sobre%20seu%20trabalho." class="lp-btn" target="_blank">Agendar primeira conversa →</a>
    <a href="#sobre" class="lp-btn-outline">Conhecer o trabalho ↓</a>
  </div>
  <div class="lp-trust">
    <div class="lp-trust-item">Psicólogo registrado CRP</div>
    <div class="lp-trust-item">Atendimento online</div>
    <div class="lp-trust-item">Sigilo garantido</div>
    <div class="lp-trust-item">Autor publicado</div>
  </div>
</div>

<!-- ═══════════════════════════════════════ -->
<!--  SOBRE                                 -->
<!-- ═══════════════════════════════════════ -->
<div class="lp-section-cream" id="sobre">
<div class="lp-section-inner">
<div class="lp-about-grid">

<div class="lp-about-text">
  <div class="lp-label">Quem sou</div>
  <div class="lp-h2">Psicologia com <em>técnica e sensibilidade</em></div>
  <p>Sou <strong>Bruno Ferraz</strong>, psicólogo clínico, autor e professor. Ao longo da minha trajetória, venho construindo uma prática que integra psicologia clínica com recursos expressivos — especialmente por meio da origamiterapia.</p>
  <p>Acredito que o cuidado psicológico pode ser profundo e, ao mesmo tempo, humano, acessível e criativo. Em alguns percursos, isso acontece pela palavra; em outros, também pelo gesto, pela imagem, pelo símbolo e pela experiência.</p>
  <p>É dessa visão que nasce meu trabalho: um espaço onde clínica, arte e desenvolvimento podem dialogar com seriedade, acolhimento e sentido.</p>
</div>

<div class="lp-credentials">
  <div class="lp-cred">
    <div class="lp-cred-icon">🎓</div>
    <div>
      <h4>Formação em Psicologia</h4>
      <p>Psicólogo clínico com formação sólida e atuação contínua em psicoterapia individual.</p>
    </div>
  </div>
  <div class="lp-cred">
    <div class="lp-cred-icon">📚</div>
    <div>
      <h4>Autor Publicado</h4>
      <p>Livros sobre origamiterapia, psicologia e desenvolvimento humano disponíveis ao grande público.</p>
    </div>
  </div>
  <div class="lp-cred">
    <div class="lp-cred-icon">🏫</div>
    <div>
      <h4>Professor e Palestrante</h4>
      <p>Cursos, workshops e formações para profissionais e pessoas interessadas em crescimento pessoal.</p>
    </div>
  </div>
  <div class="lp-cred">
    <div class="lp-cred-icon">🌿</div>
    <div>
      <h4>Abordagem Integrativa</h4>
      <p>Reunindo neuropsicologia, arteterapia, psicomotricidade e psicologia humanista.</p>
    </div>
  </div>
</div>

</div>
</div>
</div>

<!-- ═══════════════════════════════════════ -->
<!--  ABORDAGEM                             -->
<!-- ═══════════════════════════════════════ -->
<div class="lp-section" id="abordagem">
  <div class="lp-label">Como trabalho</div>
  <div class="lp-h2">Uma psicoterapia que <em>respeita quem você é</em></div>
  <p style="color:#8a8178;max-width:560px;line-height:1.75;font-size:1.02rem;">Cada pessoa carrega uma história singular. Minha prática clínica parte dessa escuta — sem pressa, sem julgamento — para criar um espaço de transformação genuína.</p>

  <div class="lp-cards">
    <div class="lp-card">
      <div class="lp-card-num">01</div>
      <h3>Escuta Qualificada</h3>
      <p>Presença plena e atenção às suas palavras, silêncios e emoções. O processo terapêutico começa pela qualidade do encontro.</p>
    </div>
    <div class="lp-card">
      <div class="lp-card-num">02</div>
      <h3>Abordagem Criativa</h3>
      <p>Além da linguagem verbal, uso recursos expressivos e artísticos que ampliam o acesso ao mundo interno — de forma segura e acolhedora.</p>
    </div>
    <div class="lp-card">
      <div class="lp-card-num">03</div>
      <h3>Processo Personalizado</h3>
      <p>Não existe receita única. Cada percurso terapêutico é construído a partir das necessidades, ritmo e objetivos de cada pessoa.</p>
    </div>
  </div>
</div>

<!-- ═══════════════════════════════════════ -->
<!--  ORIGAMITERAPIA                        -->
<!-- ═══════════════════════════════════════ -->
<div class="lp-section-dark" id="origamiterapia">
<div class="lp-section-inner">
<div class="lp-highlight-grid">

<div class="lp-highlight-text">
  <div class="lp-label lp-label-light">Diferencial</div>
  <div class="lp-h2 lp-h2-light" style="font-family:'Cormorant Garamond',Georgia,serif;font-size:clamp(1.8rem,3vw,2.6rem);font-weight:400;color:white;line-height:1.2;margin-bottom:20px;">O que é a <em style="font-style:italic;color:#e8d5b0;">Origamiterapia?</em></div>
  <p>A origamiterapia é uma proposta terapêutica pioneira que integra psicologia clínica, origami, arteterapia, neuropsicologia e psicomotricidade em um único processo de cuidado.</p>
  <p>Pela dobra do papel, acessamos processos internos, emoções e potencialidades que nem sempre chegam até as palavras. É psicologia com presença, criatividade e sentido.</p>
  <a href="https://wa.me/5521994668971?text=Ol%C3%A1%2C%20Bruno.%20Tenho%20interesse%20na%20origamiterapia." class="lp-btn-gold" target="_blank">Saber mais sobre a abordagem</a>
</div>

<ul class="lp-list">
  <li>Integra neuropsicologia e recursos expressivos</li>
  <li>Facilita o acesso a emoções e processos internos</li>
  <li>Útil no autoconhecimento, desenvolvimento e cura</li>
  <li>Aplicável em atendimento individual e grupos</li>
  <li>Abordagem criada e desenvolvida por Bruno Ferraz</li>
  <li>Respaldada por formação clínica e publicações</li>
</ul>

</div>
</div>
</div>

<!-- ═══════════════════════════════════════ -->
<!--  PARA QUEM                             -->
<!-- ═══════════════════════════════════════ -->
<div class="lp-section-cream" id="para-quem">
<div class="lp-section-inner">
  <div class="lp-label">Para quem é</div>
  <div class="lp-h2">A psicoterapia pode te ajudar <em>com</em></div>

  <div class="lp-issues">
    <div class="lp-issue"><span class="lp-issue-icon">😔</span>Ansiedade e preocupação excessiva</div>
    <div class="lp-issue"><span class="lp-issue-icon">🌧️</span>Tristeza e depressão</div>
    <div class="lp-issue"><span class="lp-issue-icon">🔄</span>Baixa autoestima</div>
    <div class="lp-issue"><span class="lp-issue-icon">💼</span>Estresse e burnout</div>
    <div class="lp-issue"><span class="lp-issue-icon">💔</span>Luto e perdas</div>
    <div class="lp-issue"><span class="lp-issue-icon">🤝</span>Dificuldades nos relacionamentos</div>
    <div class="lp-issue"><span class="lp-issue-icon">🧭</span>Falta de propósito</div>
    <div class="lp-issue"><span class="lp-issue-icon">🌱</span>Autoconhecimento e crescimento</div>
  </div>
</div>
</div>

<!-- ═══════════════════════════════════════ -->
<!--  COMO FUNCIONA                         -->
<!-- ═══════════════════════════════════════ -->
<div class="lp-section" style="text-align:center;" id="como-funciona">
  <div class="lp-label" style="justify-content:center;">Como funciona</div>
  <div class="lp-h2" style="max-width:500px;margin:0 auto 8px;">Seu caminho começa <em>aqui</em></div>

  <div class="lp-steps">
    <div class="lp-step">
      <div class="lp-step-num">1</div>
      <h4>Primeiro contato</h4>
      <p>Envie uma mensagem pelo WhatsApp. Respondo pessoalmente, sem intermediários.</p>
    </div>
    <div class="lp-step">
      <div class="lp-step-num">2</div>
      <h4>Conversa inicial</h4>
      <p>Uma sessão de acolhimento para entendermos o que você busca e se fazemos sentido juntos.</p>
    </div>
    <div class="lp-step">
      <div class="lp-step-num">3</div>
      <h4>Início do processo</h4>
      <p>Sessões semanais, online ou presenciais, construídas para o seu ritmo e necessidades.</p>
    </div>
    <div class="lp-step">
      <div class="lp-step-num">4</div>
      <h4>Transformação real</h4>
      <p>Com consistência e presença, o processo terapêutico gera mudanças duradouras.</p>
    </div>
  </div>
</div>

<!-- ═══════════════════════════════════════ -->
<!--  DEPOIMENTOS                           -->
<!-- ═══════════════════════════════════════ -->
<div class="lp-section-cream">
<div class="lp-section-inner">
  <div class="lp-label">Experiências</div>
  <div class="lp-h2">O que dizem <em>quem passou por aqui</em></div>

  <div class="lp-testimonials">
    <div class="lp-testimonial">
      <p class="lp-testimonial-text">A terapia com o Bruno foi transformadora. Ele tem uma capacidade rara de escutar com presença e de criar um espaço onde me sinto segura para ser quem sou.</p>
      <div class="lp-author">
        <div class="lp-avatar">A</div>
        <div class="lp-author-info">
          <strong>Ana P.</strong>
          <span>2 anos de acompanhamento</span>
        </div>
      </div>
    </div>
    <div class="lp-testimonial">
      <p class="lp-testimonial-text">A origamiterapia me surpreendeu. Nunca imaginei que dobrar papel pudesse me colocar em contato com emoções tão profundas. Uma experiência única e muito significativa.</p>
      <div class="lp-author">
        <div class="lp-avatar">R</div>
        <div class="lp-author-info">
          <strong>Ricardo M.</strong>
          <span>Participante de workshop</span>
        </div>
      </div>
    </div>
    <div class="lp-testimonial">
      <p class="lp-testimonial-text">O Bruno tem uma escuta muito diferenciada. Ele não impõe nada — caminha junto com a gente. Minha autoestima e meu senso de direção mudaram completamente.</p>
      <div class="lp-author">
        <div class="lp-avatar">C</div>
        <div class="lp-author-info">
          <strong>Carla S.</strong>
          <span>18 meses de acompanhamento</span>
        </div>
      </div>
    </div>
  </div>
</div>
</div>

<!-- ═══════════════════════════════════════ -->
<!--  CTA FINAL                             -->
<!-- ═══════════════════════════════════════ -->
<div class="lp-cta-final" id="contato">
  <div class="lp-label" style="justify-content:center;">Próximo passo</div>
  <h2>Pronto para <em>começar?</em></h2>
  <p>O primeiro passo é o mais importante. Fale diretamente comigo pelo WhatsApp — sem formulários, sem espera, sem burocracia.</p>
  <div class="lp-cta-buttons">
    <a href="https://wa.me/5521994668971?text=Ol%C3%A1%2C%20Bruno.%20Vim%20pelo%20seu%20site%20e%20gostaria%20de%20saber%20mais%20sobre%20seu%20trabalho." class="lp-btn" target="_blank">Falar com Bruno no WhatsApp →</a>
    <a href="mailto:contato@origami.psc.br" class="lp-btn-outline">Enviar e-mail</a>
  </div>
</div>

---

*© 2025 Bruno Ferraz · Psicologia Clínica · [origami.psc.br](https://origami.psc.br) · Rio de Janeiro, RJ*
