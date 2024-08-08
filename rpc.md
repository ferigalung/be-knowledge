### RPC (Remote Procedural Call) 
Istilah untuk metode memanggil function dari komputer / server lain, singkatnya RPC adalah sebutan untuk fetching data dari API

- JSON-RPC
    - fetching data dari API yang me-return data dalam bentuk JSON (API yang biasa dipake selama ini atau REST-API)
    - memakai protocol HTTP/1.1
    - hanya mendukung unary (request-response)
- gRPC
    - fetching data menggunakan framework buatan google, return berupa binary yang di-serializasi/decode otomatis dari sisi server dan client sesuai kebutuhan bahasa pemrograman yang dipake
    - memakai protocol HTTP/2 yang support multiplexing (komunikasi 2 arah), header compression, dan server push.
    - mendukung unary (request-response), server streaming, client streaming, dan bi-directional streaming.
- tRPC
    - JSON-RPC biasa, cuma pake typescript.
    - client dan server harus sama-sama pake TS
    - jika server mengubah contract API, client bakal munculin error di codingan, supaya tau kalau contractnya sudah berubah