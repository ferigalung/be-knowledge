### Goroutine
Mekanisme di Go dalam menjalankan multiple process secara concurrent (bukan pararel). Jika di Promise.All() JS, semua process dikerjakan secara bersamaan dalam 1 waktu menggunakan 1 thread, Goroutine tetap menjalankan 1 proses dalam 1 waktu tapi bisa bolak balik berpindah-pindah antara 1 process dengan process yang lain secara efisien dan memungkinkan menggunakan multi-thread

### Sync Mutex (Mutual Exclusion)
adalah mekanisme dalam goroutine yang bisa mencegah race condition saat mengakses/mengubah data yang sama secara bersamaan

### WaitGroup
package untuk menunggu semua proses di goroutine selesai dengan cara menambah counter (+1) di setiap prosesnya, dan akan mengurangi counter (-1) jika 1 process selesai, jika counter sudah 0, maka dianggap selesai dan output akhir akan dimunculkan (mirip await Promise.All di JS)

### Channel
mekanisme untuk komunikasi / mengirimkan data antar goroutine
