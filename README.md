# TIC-ASR-Streaming-Accesibilidad 🎙️⚡

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.24090013.svg)](https://doi.org/10.5281/zenodo.24090013)
[![License: Apache 2.0](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Python 3.10+](https://img.shields.io/badge/python-3.10+-brightgreen.svg)](https://www.python.org/)

Repositorio oficial del **Trabajo de Integración Curricular (TIC)** de la **Universidad Nacional de Loja (UNL)**: *Análisis comparativo de modelos ASR en streaming para la accesibilidad comunicativa de personas con discapacidad auditiva*.

---

## 📌 Descripción del Proyecto
Este proyecto evalúa y compara el desempeño de las arquitecturas ASR **Whisper-small** (`openai/whisper-small`) y **Wav2Vec2 XLS-R 300M** (`facebook/wav2vec2-xls-r-300m`) sometidas a *fine-tuning* eficiente mediante adaptadores **LoRA** (PEFT) sobre habla en español latinoamericano (`es_419`) y escenarios de degradación acústica sintética (ruido de aula).

---

## 📂 Estructura del Repositorio

```text
TIC-ASR-Streaming-Accesibilidad/
├── notebooks/
│   ├── whisper_colab_rapido.ipynb   # Fine-tuning e inferencia de Whisper-small
│   └── wav2vec2_colab.ipynb         # Fine-tuning e inferencia de Wav2Vec2 XLS-R 300M
├── scripts/                         # Scripts auxiliares de procesamiento y servidor backend
├── README.md                        # Guía de replicabilidad técnica y documentación
└── requirements.txt                 # Archivo congelado de dependencias del entorno
