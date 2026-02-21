# 📻 Memory & Mixtapes: The Sounds of Albuquerque 1985 - 1988
[![Live on GitHub Pages](https://img.shields.io/badge/Live-Demo-brightgreen)](https://mdotslash.github.io/shirley-tapes/)

A high-fidelity, mobile-first web application designed to showcase archival audio from the **Shirley Ann Griffin-Martin Archive**. This player provides a curated journey through African American life in Albuquerque, NM, between 1985 and 1988.

---

## 🎨 User Experience
The interface is designed to bridge the gap between a 1980s mixtape aesthetic and modern mobile media players. 

* **Segmented Listening:** Instead of an overwhelming single track, the audio is presented as 45-second "exhibits."
* **Archival Context:** As the audio plays, the "Speaker Grill" section updates to show who is speaking and why the moment matters.
* **Media Deck Controls:** Monospaced counters and a simplified play/skip interface prioritize the content over the UI.

---

## 🛠 Features

- **Segmented Navigation**: The player treats a single long-form audio file as a series of thematic "excerpts," allowing users to skip through history track-by-track.
- **Dynamic Metadata**: Real-time updates of titles and historical context via a "Speaker Grill" UI component.
- **Media Deck Aesthetic**: Features a grouped monospaced timer (`0:00 / 0:45`) and a high-contrast progress bar.
- **Mobile-First Design**: Built with `100dvh` and safe-area-insets to feel like a native iOS/Android web app.

---

## 📂 Repository Structure

| File | Description |
| :--- | :--- |
| `index.html` | The core application (HTML5, CSS3, and Vanilla JS). |
| `audio.mp3` / `.webm` | The archival audio source file. |
| `bg-image.png` | Featured hero image of Shirley Ann Griffin-Martin. |

---

## 🚀 Quick Start & Deployment

1. **Clone the repository**:
   ```bash
   git clone [https://github.com/mdotslash/shirley-tapes.git](https://github.com/mdotslash/shirley-tapes.git)
