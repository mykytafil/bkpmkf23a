# Porovnanie transformerových architektúr pri detekcii nenávistného prejavu na sociálnych sieťach

Tento repozitár obsahuje zdrojové kódy k bakalárskej práci zameranej na porovnanie transformerových modelov pri detekcii nenávistného prejavu na sociálnych sieťach.

## Popis projektu

Cieľom práce je otestovať a porovnať vybrané NLP modely pri klasifikácii textových príspevkov do kategórií súvisiacich s nenávistným alebo urážlivým obsahom. Projekt využíva dataset zo sociálnej siete  X a modely založené na architektúre Transformer.

## Použité modely

- DeBERTa-v3
- T5-small
- BERT
- XLM-RoBERTa
- Llama-3.2 (1B)


## Použité technológie

- Python
- PyTorch
- Transformers
- Pandas
- Scikit-learn
- Jupyter Notebook

  
## Štruktúra repozitára

```text
├── bert.ipynb                    # Trénovanie a testovanie modelu BERT
├── xlm-roberta-base.ipynb         # Trénovanie a testovanie modelu XLM-RoBERTa
├── deberta.ipynb                  # Trénovanie a testovanie modelu DeBERTa-v3
├── t5-small.ipynb                 # Trénovanie a testovanie modelu T5-small
├── Llama.ipynb                    # Trénovanie a testovanie modelu Llama-3.2-1B
├── labeled_data.csv               # Dataset použitý v experimentálnej časti
├── Systémová príručka.pdf         # Technická dokumentácia systému
├── Používateľská príručka.pdf     # Návod na používanie riešenia
└── README.md                      # Popis projektu


