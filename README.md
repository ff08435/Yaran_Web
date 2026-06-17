# Yaran Web

Web frontend for **Burushaski Yaran**, a speech-to-English translation system for Burushaski — an endangered language isolate spoken in northern Pakistan (Hunza, Nagar, and surrounding regions).

This interface lets users record or upload Burushaski speech and receive an English translation, powered by a fine-tuned Whisper model served through a backend inference API.

## About the Project

Burushaski Yaran was built as a Final Year Project at Habib University. The broader project includes:

- A custom dataset of 511 sentences across 16 grammatical categories, collected via a dedicated data-elicitation PWA
- Data augmentation (pitch shifting, speed perturbation, RIR) to improve model robustness on limited training data
- A Whisper model fine-tuned for Burushaski speech recognition and translation
- A backend inference API serving the fine-tuned model
- This web client, providing the public-facing interface

The accompanying dataset paper was accepted at **CHiPSAL 2026** (co-located with LREC-COLING), and the project placed **3rd for Best Oral Presentation** at the DURS 2026 Symposium at Habib University.

## Tech Stack

- React
- JavaScript

## Getting Started

```bash
npm install
npm start
```

The app expects a running instance of the backend inference API. Configure the API endpoint via the `BASE_URL` environment variable / config before starting the app.

```bash
npm run build
```

builds the app for production to the `build` folder.

## Team

Built by Mahrukh Yousuf, Adina Mansoor, Azkaa Nasir, and Fatima Faisal, under the advisory of Tauqeer Saleem and Abdul Samad.

This repository is a fork maintained for frontend/API integration work as part of the project.
