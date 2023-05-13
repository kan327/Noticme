# Noticme

## Noticme Features

### `Noticme.any()`
Metode utama Noticme yang dapat menampilkan notifikasi dengan berbagai pilihan opsi. Berikut adalah opsi yang tersedia:

* `text` (string): Text yang ingin ditampilkan pada notifikasi.
* `type` (string): Jenis notifikasi yang ingin ditampilkan. Nilai yang diterima hanya bisa `"success"`, `"danger"`, atau `"info"`.
* `color` (string): Warna yang ingin digunakan pada notifikasi. Nilai yang diterima adalah `"default"` atau dapat diganti dengan warna pilihan Anda.
* `icon` (string): Font ikon yang ingin ditampilkan pada notifikasi. Nilai yang diterima adalah `"default"` atau dapat diganti dengan font ikon dari Material Icons yang tersedia.
* `multiple` (boolean): Menentukan apakah notifikasi yang muncul dapat ditampilkan lebih dari satu atau tidak. Nilai yang diterima adalah `true` atau `false`.
* `confirm` (boolean): Menentukan apakah notifikasi yang muncul membutuhkan konfirmasi dari pengguna atau tidak. Nilai yang diterima adalah `true` atau `false`.
* `input` (boolean): Menentukan apakah notifikasi yang muncul memerlukan input dari pengguna atau tidak. Nilai yang diterima adalah `true` atau `false`.
* `timer` (boolean): Menentukan apakah notifikasi yang muncul akan hilang secara otomatis setelah waktu tertentu atau tidak. Nilai yang diterima adalah `true` atau `false`.
* `message` (boolean): Menentukan apakah teks pesan notifikasi ingin ditampilkan atau tidak. Nilai yang diterima adalah `true` atau `false`.
* `button` (boolean): Menentukan apakah tombol aksi notifikasi ingin ditampilkan atau tidak. Nilai yang diterima adalah `true` atau `false`.

Contoh penggunaan: 

```js
Noticme.any({
  text: "Ini adalah pesan notifikasi",
  type: "success",
  color: "default",
  icon: "default",
  multiple: false,
  confirm: false,
  input: false,
  timer: true,
  message: true,
  button: true
})
