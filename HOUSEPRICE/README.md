# END to END ML PROJECT

### Created new environment
---
conda create -p mlenv python==3.8     OR  python3 -m venv mlenv
---
### Activate the environment
---
conda activate mlenv/                 OR  . mlenv/bin/activate
---
### Instal all necessary liberies
---
pip install -r requirements.txt
---
### install kernel
---
pip install ipykernel
---

### Run dockerfile
---
docker build -t diamondprediction:latest .
---