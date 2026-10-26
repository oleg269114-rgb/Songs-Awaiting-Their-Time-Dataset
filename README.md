# Songs Awaiting Their Time / «Пісні, що очікують на свій час»

[![Zenodo DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23621008.svg)](https://doi.org/10.5281/zenodo.23621008)
[![License: CC BY-NC-ND 4.0](https://img.shields.io/badge/License-CC_BY--NC--ND_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-nd/4.0/)

## 🎵 About the Dataset
**"The Trilogy of Fate, Awakening, and Hope"** offers a counter--manifesto to unstructured generative AI audio: a highly structured, semantically aligned 3-act Progressive Rock & Neo-Prog cycle engineered specifically for advanced Symbolic Music Information Retrieval (MIR), AI evaluation, and structural musicology.

Created by **Oleh Polishchuk**, this dataset demonstrates how complex polyphonic arrangements, dynamic modulation, and profound conceptual lyrics can be systematically mapped across MIDI, multitrack audio, and structured JSON manifests.

---

## 🏷️ Tags & Categories
* `Progressive Rock` • `Neo-Prog` • `Dataset` • `Ukrainian Music` • `Musicology` • `Artificial Intelligence` • `Metadata` • `Lyrics`

---

## 📂 Repository Structure & Sample Data
This repository serves as a technical showcase containing metadata manifests, structural documentation, and samples from the complete archive published on Zenodo.

### Structure of a Sample JSON Manifest (`Phoenix_Фенікс`)
Below is an excerpt demonstrating the structural parameter mapping used across the dataset tracks:

```json
{🔗 Official Archive & DOI
The complete, verified multi-modal archive (including audio stems, full MIDI files, complete JSON structures, cover art, and bilingual memoirs) is permanently archived and assigned a formal digital object identifier:

Zenodo DOI: 10.5281/zenodo.23621008

📜 License & Intellectual Property
This work is licensed under a Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International (CC BY-NC-ND 4.0).

Commercial use, redistribution for AI model training, or derivative works require explicit written authorization from the author.

📬 Contact & Commercial Licensing
For commercial licensing, B2B collaboration, custom AI audio/MIDI dataset creation, or inquiries regarding full multi-track rights, please contact the author directly:

Author: Oleh Polishchuk

Email: oleg269114@gmail.com

LinkedIn: Oleh Polishchuk

Location: Italy / Ukraine
  "tempo": 85,
  "editMode": 1,
  "fileType": "songName": "Phoenix_Фенікс",
  "composer": "Polishchuk Oleh",
  "sections": [
    {
      "name": "Intro 1-1 D Min 2/4",
      "keyRoot": "C",
      "keyMode": "Maj",
      "chords": [
        {"root": "D", "type": "Min", "duration": 2, "inversion": 0},
        {"root": "D", "type": "Min", "duration": 1, "inversion": 1, "bass": "C"},
        {"root": "A", "type": "Sus4", "duration": 3}
      ]
    }
  ]
}
