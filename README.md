# Semantik Kitab Taqrib

Pencarian semantik (*semantic search*) untuk **Matn al-Ghayah wa at-Taqrib** karya Abu Syuja' al-Ashfahani — kitab fikih madzhab Syafi'i. Sistem ini memungkinkan pencarian berdasarkan **makna**, bukan hanya kata kunci, di dalam teks kitab.

## Tujuan

- Memudahkan penuntut ilmu mencari pasal/bab berdasarkan makna dan pertanyaan dalam bahasa alami.
- Eksperimen NLP untuk teks Arab klasik: segmentasi teks, *embedding*, dan pencarian vektor.

## Rencana Teknis

- **Bahasa:** Python
- **Preprocessing** teks Arab (normalisasi, segmentasi per-bab/fasal)
- **Model embedding** multibahasa/Arab
- **Vector store:** FAISS / Chroma
- **Antarmuka:** CLI sederhana → API/web

## Struktur Proyek

```
data/        Teks kitab dan hasil olahan
src/         Kode utama: preprocessing, indexing, pencarian
notebooks/   Eksperimen dan eksplorasi
```

## Status

Proyek baru dimulai. Kontribusi dan saran dipersilakan.
