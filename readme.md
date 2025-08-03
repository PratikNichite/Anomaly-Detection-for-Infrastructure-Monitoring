# Task 1: Anomaly Detection for Infrastructure Monitoring

This project detects cracks in concrete infrastructure by modeling healthy surfaces with a Variational Autoencoder (VAE). The model is trained only on non-cracked images and detects anomalies by calculating reconstruction error on new images.

## Project Structure

- `data/` – Non-cracked and Cracked image data  
- `env/` – Virtual environment or dependencies folder  
- `code.ipynb` – Main notebook for training, evaluation, and visualization  
- `documentation.pdf` – Detailed explanation of strategy and results  
- `best_vae.pth` – Saved trained VAE model  
- `recon-error.png` – Reconstruction error distribution plot  
- `visualizations.png` – Other visualizations 
- `requirements.txt` – Python dependencies


## Getting Started

1. Install dependencies:
   ```bash
   pip install -r requirements.txt
    ```

2. Open code.ipynb in Jupyter Notebook.

3. Train the model or load best_vae.pth for inference:
    ```bash
    model.load_state_dict(torch.load('best_vae.pth'))
    ```

## Contributors:
1. Chandu Dadi | Matriculation Nr.: x
2. Pratik Nichite | Matriculation Nr.: 5123777
3. Nush | Matriculation Nr.: x
4. Anagha | Matriculation Nr.: x