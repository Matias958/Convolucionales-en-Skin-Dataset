# Cómo reproducir

## 1. Dataset

Copiar la carpeta `Split_smol` provista por la cátedra dentro de `data/`, al lado del notebook:

```
.
├── CNN_en_Skin_Dataset.ipynb
├── requirements.txt
└── data/
    └── Split_smol/
        ├── train/   # una subcarpeta por clase (9)
        └── val/     # mismas 9 subcarpetas
```

## 2. Entorno (Python 3.10 o superior)

```bash
python -m venv .venv
source .venv/bin/activate        # Windows: .venv\Scripts\activate
pip install -r requirements.txt
```

Para usar GPU, instalar primero PyTorch con CUDA desde https://pytorch.org/get-started/locally/ y después correr `pip install -r requirements.txt`.

## 3. Ejecución

```bash
jupyter notebook CNN_en_Skin_Dataset.ipynb
```

Ejecutar todas las celdas en orden con **Kernel → Restart & Run All**, sin modificar las constantes de la sección 0.
