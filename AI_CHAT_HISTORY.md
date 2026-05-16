# Rekap Prompting AI - Tugas 2 Build Your Service

Nama: Muhammad Al Faris  
NIM: 102022400152  
Repository: 102022400152_Kontrak-Sewa  
Framework: Laravel 11  
Database: SQLite/MySQL  
Dokumentasi API: Swagger / OpenAPI  

---

## Prompt 1
Membuat project API Laravel untuk sistem kontrak sewa.

## Hasil
Berhasil membuat project Laravel dan struktur folder API menggunakan Laravel 11.

---

## Prompt 2
Membuat migration tabel contracts.

## Hasil
Berhasil membuat tabel contracts dengan field:
- contract_number
- property_id
- tenant_id
- status
- start_date
- end_date
- monthly_rent
- deposit_amount
- terms_and_conditions
- signed_at
- signature_data
- created_by

Migration berhasil dijalankan menggunakan artisan migrate.

---

## Prompt 3
Membuat model Contract dan controller API.

## Hasil
Berhasil membuat:
- Contract.php
- ContractController.php

Controller digunakan untuk proses CRUD endpoint API.

---

## Prompt 4
Membuat endpoint API CRUD.

## Hasil
Berhasil membuat endpoint:
- GET /api/contracts
- GET /api/contracts/{id}
- POST /api/contracts
- PUT /api/contracts/{id}
- DELETE /api/contracts/{id}

Semua endpoint menggunakan format response JSON.

---

## Prompt 5
Menguji endpoint menggunakan terminal PowerShell dan browser.

## Hasil
Endpoint berhasil diuji menggunakan:
- GET
- POST
- PUT
- DELETE

Semua endpoint mengembalikan response JSON dengan status code yang sesuai.

---

## Prompt 6
Mengatasi error Method Not Allowed pada endpoint PUT.

## Hasil
Berhasil memperbaiki route API pada file routes/api.php sehingga endpoint PUT dapat dijalankan dengan benar.

---

## Prompt 7
Menginstall dan konfigurasi Swagger/OpenAPI menggunakan L5-Swagger.

## Hasil
Berhasil menginstall package:
- darkaonline/l5-swagger

Dan berhasil membuat dokumentasi Swagger/OpenAPI pada project Laravel.

---

## Prompt 8
Mengatasi error Swagger:
Required @OA\Info() not found

## Hasil
Berhasil membuat file OpenApi.php dan konfigurasi annotation OpenAPI untuk dokumentasi Swagger.

---

## Prompt 9
Mengatasi error:
Required @OA\PathItem() not found

## Hasil
Berhasil menambahkan dokumentasi endpoint pada ContractController menggunakan OpenAPI Attributes.

---

## Prompt 10
Mengatasi error:
@OA\Get() requires at least one @OA\Response()

## Hasil
Berhasil menambahkan response documentation pada endpoint GET sehingga Swagger dapat melakukan generate documentation dengan benar.

---

## Prompt 11
Membuat dokumentasi endpoint GET /api/contracts pada Swagger.

## Hasil
Swagger berhasil menampilkan:
- endpoint API
- response code
- request URL
- response JSON

---

## Prompt 12
Melakukan pengujian Swagger menggunakan fitur Try it out.

## Hasil
Swagger berhasil menjalankan endpoint dan menampilkan response JSON:
- status success
- message
- data contracts

Endpoint berhasil diakses melalui Swagger UI.

---

## Hasil Akhir

Dokumentasi Swagger berhasil diakses pada:

http://127.0.0.1:8000/api/documentation

API berhasil:
- menggunakan format JSON
- menjalankan endpoint CRUD
- menampilkan dokumentasi Swagger/OpenAPI
- menampilkan response API melalui fitur Try it out

Project berhasil memenuhi requirement dokumentasi API interaktif pada tugas Build Your Service.
```
