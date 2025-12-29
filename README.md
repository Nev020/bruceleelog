# bruceleelog

## [▶️ Play](https://nev020.github.io/bruceleelog/)

> **“此表請勿攜出院外 — Please do not take it away.”**

BruceLeeLog is a digital reconstruction of a physical artifact. It is a deliberate, forensic recreation of the 1965 exercise program from the **Hak Keung Gymnasium**, specifically the regimen utilized by Bruce Lee.

---

## I. Heritage
Design is an act of preservation. The interface is a 1:1 digital twin of the original paper log utilized in Hong Kong. We have retained the tactile imperfections of the past:
* **The Forensic Fold**: A vertical center crease simulated through CSS gradients to evoke the feeling of a folded document kept in a gym bag.
* **Blue Ink Typography**: Utilizing the *Architects Daughter* typeface to simulate the pressure and flow of a ballpoint pen.
* **The Stamp of Authenticity**: A digital seal system to "verify" logs, honoring the traditional Chinese gym management style.

## II. Live Persistence
Technology should be invisible. BruceLeeLog is powered by **LocalStorage** and a zero-dependency JavaScript architecture.
* **Real-time Persistence**: Every character typed is instantly committed to the browser's memory. No save buttons are required.
* **Auto-Scaling Dynamics**: Exercise names, such as the `“CON” CURL`, utilize dynamic font-scaling to ensure the mathematical integrity of the table remains intact across all viewports.

## III. Precision Regimen
The data structure is rooted in the 1965 original. While the system allows for modern customization, it defaults to the researched point of Bruce Lee's physical development.

| Exercise | Original Sets | Original Lbs | Times |
| :--- | :--- | :--- | :--- |
| **SQUAT** | 3 | 95 | 10 |
| **FRENCH PRESS** | 4 | 64 | 6 |
| **"CON" CURL** | 4 | 35 | 6 |
| **PUSH UP** | 3 | 70–80 | 10 |

## IV. Technical Schema (The Backup System)
For long-term preservation, the **BACKUP DATA** feature distills the browser's internal storage into a single **JSON** (JavaScript Object Notation) string. This allows users to move their heritage data between devices or save it in a simple text file.

**Example Schema Structure:**
```json
{
  "hk-day-1-name": "USER NAME",
  "hk-day-1-date": "DEC 28 2025",
  "hk-day-1-row-0-ex": "\"CON\" CURL",
  "hk-day-1-row-0-sets": "4",
  "hk-day-1-row-0-lbs": "35",
  "hk-day-1-row-0-times": "6",
  "hk-day-1-stamp": "true"
}

V. Usage
Capture Intent: Use the STAMP LOG feature to mark completion.

Physical Translation: Utilize the TAKE PHOTO function to generate a high-fidelity .png of your log.

Data Integrity: Use the BACKUP system to copy your history to your clipboard and save it in a secure Note.

Restoration: Should the browser memory be cleared, use the restoreData() function with your saved JSON string to recover your logs.

