# Research arc figures

One figure per item in the research timeline. Every file in here is a placeholder right now —
replace each one with the real key figure from that paper, keeping the filename exactly as it is.
The timeline references these by name, so renaming a file breaks its card.

## Specs

- **Aspect ratio 16:10.** The cards crop to this, so anything taller gets cut off top and bottom.
  1200×750 is the placeholder size; 1600×1000 is fine too.
- **PNG**, under ~300 KB each. These load on the front page, so they are worth compressing.
- **Crop to one panel**, not the whole multi-panel figure. At card size (~215px wide on desktop,
  ~360px on a phone) a four-panel composite is unreadable. Pick the single panel that carries the point.
- **White or transparent background**, no figure caption baked in — the caption lives in the card text.
- Keep axis labels legible at card size. If they are not, crop tighter.

## The files

| File | Paper | Source for the figure |
|---|---|---|
| `health-life-course-trajectories.png` | Life-course trajectories and later-life health | `july3-health-traj.pdf` |
| `health-new-map-of-life.png` | A new map of life: measuring the whole trajectory | `july1-life-traj.pdf` |
| `careers-faculty-retention.png` | Gender and retention patterns among US faculty, *Science Advances* 2023 | publisher PDF needed |
| `careers-devaluation-departures.png` | Devaluation underlies gendered US faculty departures, *PNAS Nexus* 2026 | publisher PDF needed |
| `careers-book-bans.png` | Book bans in political context, *PNAS Nexus* 2024 | publisher PDF needed |
| `careers-elite-undergrad-backgrounds.png` | The elite undergraduate backgrounds of U.S. professors, in preparation | draft needed |
| `careers-dei-backlash.png` | Backlash to diversity, equity and inclusion efforts among faculty, in preparation | draft needed |
| `census-healthcare-access.png` | Measuring community-level risk of declining healthcare access, Census Bureau 2024 | is any of it public? |
| `careers-dissertation.png` | Quantifying systemic inequities in the training and retention of professors, 2025 | dissertation PDF needed |
| `ibm-transformer-accuracy.png` | Software-equivalent accuracy on transformers with analog memory, *Frontiers* 2021 | `assets/transformer_paper_2021.pdf` |
| `ibm-crossbar-acceleration.png` | Accelerating DNNs with analog memory devices, IEEE IMW 2020 | paper PDF needed |
| `ibm-pcm-chapter.png` | Accelerating DNNs with phase-change memory devices, book chapter 2022 | chapter PDF needed |
| `dyslexia-handwriting-detection.png` | Early detection of dyslexia from children's handwriting, ICML AISG 2019 | `dyslexia_icml_aisg_2019.pdf` |
| `dyslexia-early-warning.png` | Toward an early-warning system for dyslexia, NeurIPS AISG 2019 | `dyslexia_neurips_aisg_2019.pdf` |

## Letting Claude do the cropping instead

Four of these have PDFs already in the repo. For any PDF you drop in, say which paper and which
figure number and the crop can be done here — PyMuPDF renders the page, and the figure region gets
cut out at the right ratio. That is usually faster and more consistent than doing it by hand.

Say the word and the five publisher PDFs can be pulled down too.
