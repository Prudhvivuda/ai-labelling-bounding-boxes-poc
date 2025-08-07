## Replace with your path
- `cd "/ai-labelling"`

## Use python3.9 and create venv
- `python3.9 -m venv .venv`
- `source .venv/bin/activate`

## Upgrade pip and setuptools
- `pip install --upgrade pip setuptools wheel`

## Install torch and torchvision for Mac M2 (CPU wheels)
- `pip install torch torchvision torchaudio`

## Install core dependencies 
- `pip install opencv-python pillow matplotlib supervision`

## Clone and Install Grounding DINO
- `git clone https://github.com/IDEA-Research/GroundingDINO.git`
- `cd GroundingDINO`
- `pip install .`
- `cd ..`

## Download Model Weights
- `mkdir -p weights`
- `curl -Lo weights/groundingdino_swinb_cogcoor.pth https://github.com/IDEA-Research/GroundingDINO/releases/download/v0.1.0-alpha2/groundingdino_swinb_cogcoor.pth`

