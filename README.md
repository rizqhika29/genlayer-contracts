# GenLayer Intelligent Contracts

Repo ini sebelumnya berisi dua Intelligent Contract GenLayer sekaligus. Sekarang
tiap kontrak punya repo sendiri, lengkap dengan test dan CI-nya:

| Repo | Kontrak | Isi |
|---|---|---|
| [genlayer-freelance-escrow](https://github.com/rizqhika29/genlayer-freelance-escrow) | `FreelanceEscrow` | Escrow pekerjaan freelance per milestone; hasil kerja dinilai validator lewat web + LLM |
| [genlayer-prediction-market](https://github.com/rizqhika29/genlayer-prediction-market) | `PredictionMarket` | Prediction market biner yang hasilnya diselesaikan dari halaman sumber di web |

Keduanya memakai header yang sama:

```py
# { "Depends": "py-genlayer:1jb45aa8ynh2a9c9xn3b7qqh8sm5q93hwfp7jqmwsfhh8jpz09h6" }
```

Kode, test, dan workflow lama tetap ada di riwayat git repo ini, tapi tidak lagi
dipakai. Silakan arsipkan atau hapus repo ini di GitHub; yang aktif adalah dua
repo di atas.
