# MeatOptix — AI Meat-to-Fat Ratio Analyzer (by Mehdi Dahlouk)

## EN
Estimate meat:fat ratio from RGB images (OpenCV baseline) with NIR/hyperspectral hooks.
## FR
Estimation du ratio viande/graisse (base OpenCV) + intégration NIR/hyperspectral.
## AR
تقدير نسبة اللحم إلى الدهون باستخدام OpenCV مع دعم NIR.

### Quick start
```
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
uvicorn meatoptix.api:app --reload
```
