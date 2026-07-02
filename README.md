# plavida

## An ionic-angular mobile app for annotate media data in Africa language 
#  PLAVIDA — Platform for Audio and Video Data Annotation in African Languages

> Mobile application for annotating audio and video data in African local languages, including an accessible interface designed for illiterate users.

[![Ionic](https://img.shields.io/badge/Ionic-Angular-blue)](https://ionicframework.com)
[![Django](https://img.shields.io/badge/Backend-Django-green)](https://djangoproject.com)
[![PythonAnywhere](https://img.shields.io/badge/Deployed-PythonAnywhere-orange)](https://pythonanywhere.com)
[![DOI](https://img.shields.io/badge/DOI-10.1007/978--3--031--81573--7__11-red)](https://doi.org/10.1007/978-3-031-81573-7_11)

---

## Associated Publication

> **PLAVIDA, an Annotation Tool for Audio and Video in African Languages**
>
> Traoré G.I., Somé B.M.J., Ouédraogo O., **Kalmogo L.** (2025)
> In: *Towards new e-Infrastructure and e-Services for Developing Countries*
> AFRICOMM 2023 · Lecture Notes LNICST vol. 588 · Springer, Cham
> 🔗 DOI: [10.1007/978-3-031-81573-7_11](https://doi.org/10.1007/978-3-031-81573-7_11)

---

## Overview

African languages are severely underrepresented in AI and NLP research. Machine learning models for audio classification require large amounts of labelled data, but labelled audio/video datasets in African languages are nearly nonexistent.

PLAVIDA is a mobile platform that enables researchers and communities — including **illiterate users** — to annotate audio and video content in African local languages, building the datasets needed to train AI models.

---

##  Tech Stack

| Layer | Technology |
|-------|-----------|
| **Mobile Frontend** | Ionic Framework + Angular (TypeScript) |
| **Backend API** | Django + Django REST Framework (Python) |
| **Deployment** | PythonAnywhere |
| **Target Platform** | Android |

---

##  Installation & Usage

### Frontend (Ionic/Angular)

```bash
git clone https://github.com/YOUR_USERNAME/plavida.git
cd plavida/frontend
npm install
ionic serve
```

### Backend (Django)

```bash
cd plavida/backend
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

> **Live backend**: Deployed on PythonAnywhere.

---

##  Team

| Name | Role |
|------|------|
| Go Issa Traoré | Project Lead, Research |
| Borlli Michel Jonas Somé | Research & Design |
| Ousmane Ouédraogo | Backend Development contribution |
| **KALMOGO Zakir (Lucien)** | **Frontend (Ionic/Angular), Backend, Deployment, Data Collection Coordination** |

*Published at AFRICOMM 2023 — Bobo-Dioulasso, Burkina Faso*

---

##  Citation

```bibtex
@inproceedings{traore2025plavida,
  author    = {Traoré, Go Issa and Somé, Borlli Michel Jonas and
               Ouédraogo, Ousmane and Kalmogo, Lucien},
  title     = {PLAVIDA, an Annotation Tool for Audio and Video in African Languages},
  booktitle = {Towards new e-Infrastructure and e-Services for Developing Countries},
  series    = {Lecture Notes LNICST},
  volume    = {588},
  publisher = {Springer, Cham},
  year      = {2025},
  doi       = {10.1007/978-3-031-81573-7_11}
}
```

---

##  AI Usage

**No AI tools were used** to write the code of this application.

> This README was written with the assistance of Claude (Anthropic) for structure and English phrasing.

##Note

This repository contains the backend only (Django REST API). The mobile frontend (Ionic/Angular) was developed separately and is not included here.
---
