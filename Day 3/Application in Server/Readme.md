# Application in Server
### by Rahmad Subagiyo

## Perbandingan Monolith dengan Microservice

| Category | Monolith | Microservices |
| ----------- | ----------- | ----------- |
| Design | Single Basic Code dengan fungsi yang saling bergantung satu sama lain. | Komponen independen yang berkomunikasi satu sama lain menggunakan API. |
| Development | Sedikit Perencanaan di Awal | Banyak Perencanaan di Awal |
| Deployment | Seluruh aplikasi diterapkan sebagai satu kesatuan | Aplikasi dipecah menjadi beberapa wadah tersendiri |
| Debugging | Tracing di environment yang sama | Butuh DeBugging tools yang lebih Advance untuk tracing data diantara banyak microservices |
| Modification | Berpengaruh terhadap keseluruhan script | Tidak mempengaruhi keseluruhan script karena dapat memodifikasi satu persatu microservices secara terpisah |
| Scale | Scalling secara keseluruhan, meski hanya fungsi tertentu yg dibutuhkan | Dapat scalling microservices tertentu saja yang dibutuhkan |
| Investment | Investasi di awal yang rendah dengan peningkatan di biaya maintenance ke depannya | Investasi di awal yang cukup tinggi dengan menekan biaya jangka panjang dan maintenance di masa yang akan datang |

## Deploy Aplikasi wayshub-frontend (NodeJS)
## Deploy Golang & Python