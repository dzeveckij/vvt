# LT-VLM Vilnius Bus Stop Recognition

Notebook for fine-tuning `unsloth/gemma-3-4b-it` with LoRA to describe Vilnius public transport stop images in Lithuanian.

- Dataset: https://huggingface.co/datasets/dzeveckij/autobusu-stoteles
- LoRA adapter: https://huggingface.co/dasfadsfasdfsafa/autobusu-stoteles-lora
- Report: `report.pdf`

## Files

- `train_and_demo.ipynb` - training and inference demo notebook
- `requirements-colab.txt` - packages used in the notebook
- `report.pdf` - project report

## Run

Use Google Colab or another CUDA GPU environment.

1. Open `train_and_demo.ipynb`.
2. Select a GPU runtime.
3. Run the notebook cells in order.
4. Log in to Hugging Face only if you want to push your own adapter.

Local setup:

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements-colab.txt
```

Generated model outputs, local caches, and credentials are ignored by Git.
