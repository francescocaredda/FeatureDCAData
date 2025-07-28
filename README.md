# FeatureDCAData

This repository contains supporting data for the **FeatureDCA** project, organized into three main folders. Each folder contains data relevant to the evolutionary analysis and mutational scanning of protein families.

---

## 📁 Folder Structure

### `data/`
Contains multiple protein family datasets, originally sourced from the [ArDCAData](https://github.com/soedinglab/ArDCAData) repository.

- Multiple FASTA files and related sequence data.
- Used as reference for model training and comparison.

### `RR_homodimers/`
Data specific to the **Response Regulator (RR)** protein family.

- `*.hmm` files: Hidden Markov Models used for sequence alignment.
- `*.fasta`: Original and aligned sequences of the RR family.
- `*_generated_sequences.*`: Sequences generated through computational methods for analysis.

### `DMS_beta_lactamase/`
Contains data related to **Beta-lactamase** deep mutational scanning (DMS), originally curated by the Ostermeier lab.

- `*.fasta`: Wild-type and variant sequences.
- Preprocessed DMS dataset with mutational effects and associated metadata.

---

## 🧪 Usage

The data in this repository is intended for:

- Benchmarking statistical models (e.g., DCA, VAE, Transformer-based models).
- Protein fitness prediction and mutational effect analysis.
- Sequence generation and evaluation using models trained on evolutionary data.

---

## 📦 Source Acknowledgments

- `data/`: [ArDCAData repository](https://github.com/soedinglab/ArDCAData)
- `DMS_beta_lactamase/`: Ostermeier lab DMS dataset
- `RR_homodimers/`: Processed from PF00072 family data (Pfam)

---

## 📜 License

Please refer to the original sources for any restrictions or licensing requirements for reuse of the data. This repository aggregates and preprocesses data for academic and non-commercial research purposes.

---

## 🔧 Maintainer

Francesco Caredda  
For questions or suggestions, feel free to open an issue or contact directly.

