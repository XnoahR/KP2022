# Perulangan Menggunakan For Statement

Perulangan (atau dalam bahasa inggris disebut dengan **loop**) adalah instruksi kode program yang bertujuan untuk mengulang beberapa baris perintah. Pada materi sebelumnya telah dipelajari tentang perulangan menggunakan **while statement**, kali ini kita akan mempelajari perulangan menggunakan for statement.

## For Statement
For Statement adalah salah satu jenis **Counted Loop**, artinya perulangan ini sudah jelas berapa banyak perulangannya akan dilakukan. For Statemen memiliki tiga komponen yaitu inisialisasi, kondisi, dan update.

## Syntax
Berikut merupakan syntax untuk For Statement.
```c
for(/* inisialisasi */ ; /* kondisi */ ; /* update */){
    /* program yang ingin diulang... */
}
```
- Inisialisasi: menentukan kondisi awal perulangan. Biasanya kondisi awal ini berisi perintah untuk memberikan nilai kepada variabel counter. Variabel counter sendiri adalah sebuah variabel yang akan menentukan berapa banyak perulangan dilakukan (biasanya variabel bertipe `int` dan bernama `i`,`j`,`k`, dll. Namun, kalian tetap bebas akan memakai tipe data / nama apa saja)
- Kondisi: merupakan kondisi yang harus dipenuhi agar perulangan berjalanakan. Perulangan akan dilakukan apabila kondisi adalah BENAR atau TRUE dan berhenti apabila kondisi adalah SALAH atau FALSE
- Update: digunakan untuk meng-update nilai dari pencacah (biasanya berupa increment/decrement). Proses ini akan dieksekusi setelah isi dari `for statement` habis

**CATATAN!!!**

Perhatikan urutan dalam penulisan ketiga komponen karena ketiganya harus berurutan dan perhatikan pula tanda pemisah antara komponen yaitu menggunakan `;` bukan `,`!

## Contoh Penggunaan
```c
for (int i = 0; i < 3; i++){
  printf("Ini adalah perulangan For ke-%d\n", i);
}
```
Output:
```
Ini adalah perulangan For ke-0
Ini adalah perulangan For ke-1
Ini adalah perulangan For ke-2
```

## Catatan Penting
