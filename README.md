# Embeddings Playground

[`embeddings_playground.py`](embeddings_playground.py) è una SPA streamlit per sperimentare con gli OpenAI embeddings.

## Installazione

`pip install -r requirements.txt`

Verifica l'installazione di streamlit con `streamlit hello`.

## Configurazione

Crea un file `.env`, prendi come esempio il file `.env_example`

## Uso

Esegui lo script:

`streamlit run embeddings_playground.py`

Nell'app scegli:
- distance metric (raccomandata: cosine)
- embedding model (raccomandato: `text-embedding-ada-002` per molti casi d'uso a Maggio 2023)

Dopo, inserisci un numero variabile di stringhe da comparare.
Click su `rank` per ottenere:
- la classifica delle stringhe, ordinate dalla distanza dalla prima stringa
- una heatmap che mostra la distanza tra ogni coppia di stringhe