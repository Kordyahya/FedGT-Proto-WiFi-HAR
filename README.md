# FedGT-Proto-WiFi-HAR
Federated few-shot prototypical learning with a graph–temporal encoder for WiFi CSI human activity 
recognition (FedAvg, FedProx, FedProto, FedGT-Proto).


## Authors
- Yahya Kord Tamandani — University of Sistan and Baluchestan  
- Hassan Rezaei — University of Sistan and Baluchestan  
Contact: Yahya.kord@gmail.com

## Methods
- FedAvg, FedProx, FedProto, FedGT-Proto

## Setup (Google Colab)
1. Upload CSI CSVs to `MyDrive/FedGTProto_WiFiHAR/raw_dataset/`  
   (filenames like `E1_S01_C1_A1_T1.csv`).
2. Open `FedGT_Proto_WiFi_HAR.ipynb` in Colab and run all cells.
3. If no CSVs are present, synthetic data is generated for a pipeline test.

## Outputs
- `results/summary.csv` — accuracy, F1, worst-client, params  
- `figures/` — learning curves, final accuracy, per-class F1  

## Citation
```bibtex
@article{YourName2026,
  title={...},
  author={...},
  year={2026}
}
