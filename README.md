# BPD Check — Mind Monitor

A visual, interactive simulator of mental states for people with Borderline Personality Disorder (BPD). Built around DBT (Dialectical Behavior Therapy) concepts to help develop reality-checking skills.

**Languages:** EN / RU

---

## What it does

The simulator visualizes three core DBT mind states in real time:

- 🔴 **Emotion Mind** — feelings are driving, reality is distorted
- 🔵 **Reasonable Mind** — pure logic, no emotional input
- 🟢 **Wise Mind** — integration of both; where good decisions happen

As you adjust the parameters, three animated circles shift and pulse to show how your internal state changes. The goal is to build intuition: *what does it feel like when Wise Mind is accessible? What pushes me into Emotion Mind?*

---

## Parameters

| Slider | What it models |
|---|---|
| Emotion Intensity | Raw emotional activation (0–10) |
| Trigger Strength | How strong the external trigger is |
| Rational Control | Capacity for logical thinking right now |
| Reality Check | How actively you're applying DBT skills |

| Toggle | Effect |
|---|---|
| Splitting Active | Black-and-white thinking pattern (+distortion) |
| Dissociation | Detachment from reality (−Wise Mind access) |
| Grounding Active | Active grounding skill (−emotion load) |
| Sleep Deprived | Fatigue amplifier (+emotion load ~30%) |

---

## Metrics

- **Emotion Load** — combined emotional pressure on the system
- **Wise Mind Access** — how available the integrated state is
- **Reality Distortion** — how far perception is from objective reality
- **System Stability** — overall coherence of the mental state

---

## Stack

- Vanilla HTML / CSS / JS — zero dependencies, single file
- Canvas API for animation
- Bilingual: EN / RU (runtime switching)

---

## Project structure

```

index.html    # Entire app — markup, styles, logic
```

---


## Background

BPD is characterized by emotional dysregulation — the nervous system responds to triggers with high intensity and low return time. DBT (Marsha Linehan, 1991) teaches skills to widen the gap between trigger and reaction. Reality checking is one of those skills: stopping to ask *"is this a fact or a feeling?"* before acting.

This tool is **not** a medical device or therapy substitute. It's a visual aid for building intuition around internal states.

---

## License

This project is licensed under the **MIT License**.

Free to use, modify, and distribute. See [LICENSE](LICENSE) for full terms.

See [LICENSE](LICENSE) or [gnu.org/licenses/gpl-3.0](https://www.gnu.org/licenses/gpl-3.0.html) for full terms.
