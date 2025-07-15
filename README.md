# The effect of lineup size on discriminability is dependent on filler similarity and independent of encoding strength

**How does the number and similarity of faces in a lineup impact an eyewitness's ability to discriminate the perpetrator from similar-looking fillers?**  
This project addresses this question through three behavioral experiments, using ROC analysis to evaluate identification performance.

---

## 🎯 Project Overview

Eyewitness identification often involves presenting a photo lineup, typically composed of one suspect and several visually similar fillers. While best practices encourage the use of fillers who resemble the suspect to reduce bias, this research shows that such similarity may reduce the eyewitness's ability to correctly identify the perpetrator, especially as the lineup grows in size.

We explored:
- How **filler similarity** (high vs. low) influences discriminability.
- How **lineup size** interacts with similarity to affect performance.
- Whether **encoding strength** (blurry vs. repeated faces) modulates these effects.

---

## 🧪 Experiments & R Code

- **Experiment 1**: Replication of prior findings showing opposite effects of lineup size for low- vs. high-similarity fillers.
- **Experiment 2**: Decreased encoding strength (blurry images) with low-similarity fillers.
- **Experiment 3**: Increased encoding strength (repeated images) with high-similarity fillers.

### 🔍 Analysis Method
- ROC (Receiver Operating Characteristic) analysis
- Calculation of **Adjusted Hit Rates** and **False Alarm Rates**
- Confidence-based cumulative performance modeling

Scripts:
- `Exp1_ROC.Rmd`
- `Exp2_ROC.Rmd`
- `Exp3_ROC.Rmd`

---

## 📈 Impact Statement

This research contributes a novel theoretical insight into how **set size** and **stimulus similarity** jointly affect human discriminability in visual decision-making. In applied settings like police lineups or facial recognition UIs, these findings challenge longstanding assumptions that "more context is better", especially when visual elements are too similar to be diagnostic. This has broader implications for fairness, usability, and trust in high-stakes human-computer interaction.

---

## 💡 Key Findings

- **Low-similarity fillers**: Larger lineups improved discriminability even under degraded encoding.
- **High-similarity fillers**: Larger lineups decreased discriminability even under enhanced encoding.
- The effect of **lineup size** is contingent not on overall task difficulty, but on **retrieval similarity** between items.

These results support a reinterpretation of the **Ensemble Model** in memory: attention may be biased toward shared (non-diagnostic) features in highly similar groups, interfering with identification of meaningful distinctions.

---

## 🚀 UX Implication

This project investigates how people process complex visual information under uncertainty, mirroring real-world constraints like poor visibility or over-crowded UI elements.

This project translates well to UX domains involving:
- **Visual search** in cluttered environments
- **Decision-making** under perceptual load
- **Cognitive modeling** of attention and recognition
- Designing systems where **false positives** and **misses** matter (e.g., facial recognition, surveillance, AI-driven selection interfaces)

---

## 🧩 Theoretical Implication

Increasing lineup size **isn't always helpful**. When all faces are highly similar, more faces  reinforce non-diagnostic patterns, reducing the ability to focus on what truly matters.

---

