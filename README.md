# ⚔️ MTPQI Memory Game — 14 Realms

[![Portuguese](https://img.shields.io/badge/Português-🇧🇷-blue)](README.md)
[![English](https://img.shields.io/badge/English-🇺🇸-blue)](README.en.md)
[![中文](https://img.shields.io/badge/中文-🇨🇳-blue)](README.zh.md)

**Interactive memory game for learning quantitative research methods** — Métodos e Técnicas de Pesquisa Quantitativa I (MTPQI), Federal University UNINOVE, Brazil.

🎮 **[Play Online](https://leovils.github.io/Memory-Game-MTPQI/)** — Fully playable, no dependencies, runs offline!

---

## 📖 About

A Nordic-styled memory card game featuring **14 educational realms** covering the complete MTPQI curriculum:

| Realms | Topics |
|--------|--------|
| 🌍 **Basic** | Quantitative Research, Descriptive Statistics, Probability, Sampling |
| ⚖️ **Intermediate** | Hypothesis Testing, t-test, TOST, ANOVA (1-way) |
| 👑 **Advanced** | Factorial ANOVA, Repeated Measures, ANCOVA, MANOVA, MANCOVA, Non-parametric |

### 🎯 Features

✅ **3 Languages** — Portuguese 🇧🇷 · English 🇺🇸 · 中文 🇨🇳 (toggle via button)  
✅ **14 Realms** — 24 question-answer pairs per realm  
✅ **3 Difficulty Levels** — Easy (4 pairs) · Normal (6) · Hard (8)  
✅ **Concept-Based Matching** — Pairs question ↔ answer, not identical cards  
✅ **Offline-First** — Works without internet, localStorage for best times  
✅ **Nordic Aesthetic** — Grimório Odin Dinho palette (gold #d4a017, Cinzel font)  
✅ **Responsive Design** — Mobile-friendly (4×3 grid)  

---

## 🚀 Quick Start

### Play Online
Visit **https://leovils.github.io/Memory-Game-MTPQI/** — opens instantly, no setup needed.

### Run Locally
1. Clone or download this repo
2. Double-click `index.html`
3. Select realm, difficulty, play!

---

## 🎮 How to Play

1. **Choose Realm** — Select from 14 realms organized by difficulty
2. **Pick Difficulty** — Easy (4 pairs), Normal (6), or Hard (8 pairs)
3. **Click Start** — Cards flip face-down
4. **Flip Pairs** — Match each **question to its answer**
5. **Beat Your Time** — Best times saved in browser

**Goal:** Find all pairs in shortest time!

### Realms Overview

#### 🌍 Basic Realms
- **📜 Quantitative Research** — Research design, variables, hypotheses, validity, measurement error
- **🏔️ Descriptive Statistics** — Mean, median, mode, SD, outliers, distributions, histograms
- **🏛️ Probability** — Events, distributions, independence, conditional probability, Bayes
- **🏘️ Sampling** — Population, sample, random selection, sampling error, confidence intervals

#### ⚖️ Intermediate Realms
- **⚖️ Hypothesis Testing** — H₀/H₁, Type I/II errors, α, power, effect size, p-values
- **🗡️ T-test** — One-sample, independent, paired; Cohen's d; assumptions; CIs
- **🌈 TOST** — Equivalence testing, SESOI, two one-sided tests, negative results
- **🍖 ANOVA (1-way)** — SST, SSM, F-ratio, post-hoc (Tukey), effect size η²

#### 👑 Advanced Realms
- **🧪 Factorial ANOVA** — Main effects, interactions, simple effects, cell means
- **⏳ ANOVA MR** — Repeated measures, sphericity, Greenhouse-Geisser, within-subjects
- **📚 ANCOVA** — Covariate adjustment, homogeneity of slopes, adjusted means
- **🏛️ MANOVA** — Multiple DVs, Wilks' Lambda, Pillai trace, Box M test
- **👑 MANCOVA** — MANOVA + covariates, adjusted centroid comparisons
- **❄️ Non-parametric** — Mann-Whitney, Wilcoxon, Kruskal-Wallis, Friedman, Spearman ρ

---

## 🌐 Languages

Click the flag buttons at the top to switch:
- 🇧🇷 **Português** — UI and pairs in Portuguese
- 🇺🇸 **English** — UI and pairs in English  
- 🇨🇳 **中文** — UI and pairs in Simplified Chinese

Language preference saves automatically.

---

## 📋 Technology Stack

- **Pure HTML5** — No build tools, no dependencies
- **Vanilla JavaScript** — Event-driven game logic, localStorage for persistence
- **CSS3** — Responsive grid, animations, Cinzel font from Google Fonts
- **Accessibility** — ARIA labels, semantic HTML, keyboard-navigable

---

## 📊 Content Coverage

**344 unique pairs** (14 realms × 24 pairs) covering:

- Quantitative research paradigm (NHST vs Estimation)
- New statistics (effect sizes, confidence intervals, meta-analysis)
- Research integrity (QRPs, HARKing, p-hacking, replication crisis)
- Statistical tests (t, ANOVA, MANOVA, non-parametric)
- Practical interpretation (clinical vs statistical significance)

Aligned with **Cumming (2012), Gigerenzer & Marsh (2004), and APA reform guidelines**.

---

## ⚙️ Customization

### Add More Realms
Edit the `reinos` array in `index.html`:

```javascript
const reinos = [
    {
        nome: "🔬 Your Realm Name",
        emoji: "🔬",
        pares: [
            { id: 1, pt: "Question...", en: "Question...", zh: "问题..." },
            { id: 2, pt: "Answer...", en: "Answer...", zh: "答案..." },
            // ... 24 pairs total
        ]
    },
    // ...
];
```

### Change Colors
Modify CSS variables in `<style>`:

```css
--gold: #d4a017;
--light-gold: #f0c419;
--dark-bg: #0d1117;
```

### Adjust Difficulty Levels
Change `paresTotal` calculations:

```javascript
{ facil: 4, normal: 6, dificil: 8 }
```

---

## 📱 Responsive Design

- **Desktop** — 3-column grid, full features
- **Tablet** — 3 columns, touch-optimized
- **Mobile** — 3 columns, larger hit area, swipe-friendly

---

## ♿ Accessibility

- Semantic HTML (`<button>`, `<section>`)
- Color contrast ≥ 4.5:1 (WCAG AA)
- Keyboard navigation (Tab, Enter, Esc)
- No flashing or animation >3Hz

---

## 📜 License

MIT License — Free to use, modify, and distribute. See LICENSE file.

---

## 👨‍🎓 Author

**Prof. Dr. Leonardo Vils**  
Full Professor, UNINOVE (Universidade Nove de Julho)  
Graduate Programs: PPGA (Administration) & PPGP (Project Management)  
Research: Consumer Behavior, Quantitative Methods, MCDM

📧 [leovils@gmail.com](mailto:leovils@gmail.com)  
🔗 [GitHub](https://github.com/leovils)  
🌐 [UNINOVE](https://www.uninove.br)

---

## 🙏 Acknowledgments

- **Saga Estatística Odin Dinho** — Narrative framework and Norse aesthetics
- **MTPQI Students (2020–2026)** — Feedback and use cases
- **Cinzel Font** — Google Fonts

---

## 📞 Support

Found a bug? Missing content? Want to suggest a realm?  
[Open an issue](https://github.com/leovils/Memory-Game-MTPQI/issues) or email me!

---

## 🗺️ Roadmap

- [ ] Analytics dashboard (play times, completion rates by realm)
- [ ] Leaderboard (local + cloud sync)
- [ ] Import custom realms via JSON
- [ ] Spaced repetition algorithm
- [ ] Mobile app (React Native)
- [ ] Teacher dashboard (student progress tracking)

---

**Happy learning! ⚔️🎮**  
*Métodos com prazer, estatística com estilo!*
