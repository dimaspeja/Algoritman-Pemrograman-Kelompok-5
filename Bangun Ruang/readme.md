# Bangun Ruang
Author : JOY SARY SITUMEANG

## Program java bangun ruang

1. Import Library
```
import java.util.Scanner;
```
Penjelasan:

Scanner digunakan untuk membaca input dari pengguna melalui keyboard, misalnya memasukkan panjang, lebar, jari-jari, atau tinggi.

2. Membuat Class Utama
```
public class BangunRuangLengkap {
```
Penjelasan:

class adalah wadah utama program Java.
Nama class di sini adalah BangunRuangLengkap yang berisi program untuk menghitung bangun ruang.

3. Method Main
```
public static void main(String[] args) {
```
Penjelasan:

main() adalah method utama yang pertama kali dijalankan saat program dijalankan.

4. Membuat Objek Scanner
```
Scanner input = new Scanner(System.in);
```
Penjelasan:

Kode ini membuat objek input yang digunakan untuk membaca data yang dimasukkan oleh pengguna.

5. Menampilkan Menu Program
```
System.out.println("=== PROGRAM MENGHITUNG BANGUN RUANG ===");
System.out.println("1. Kubus");
System.out.println("2. Balok");
System.out.println("3. Tabung");
System.out.println("4. Kerucut");
System.out.println("5. Bola");
```
Penjelasan:

Kode ini digunakan untuk menampilkan pilihan bangun ruang yang bisa dihitung oleh program.

6. Input Pilihan User
```
System.out.print("Pilih bangun ruang (1-5): ");
pilihan = input.nextInt();
```
Penjelasan:

Program meminta pengguna memilih jenis bangun ruang dengan memasukkan angka dari 1 sampai 5.

7. Percabangan Switch
```
switch (pilihan)
```
Penjelasan:
switch digunakan untuk menjalankan kode sesuai pilihan pengguna.

Contohnya:

1 → Kubus

2 → Balok

3 → Tabung

4 → Kerucut

5 → Bola

## penjelasan setiap bangun ruang

1. Kubus
```
double volumeKubus = sisi * sisi * sisi;
double luasKubus = 6 * sisi * sisi;
```
Penjelasan:

Program menghitung:

Volume Kubus
V = s³

Luas Permukaan Kubus
L = 6s²

2. Balok
```
double volumeBalok = p * l * t;
double luasBalok = 2 * (p*l + p*t + l*t);
```
Penjelasan:

Volume Balok
V = p × l × t

Luas Permukaan Balok
L = 2(pl + pt + lt)

3. Tabung
```
double volumeTabung = Math.PI * rTabung * rTabung * tTabung;
double luasTabung = 2 * Math.PI * rTabung * (rTabung + tTabung);
```
Penjelasan:

Volume Tabung
V = πr²t

Luas Permukaan Tabung
L = 2πr(r + t)

Math.PI digunakan untuk nilai π (3.14).

4. Kerucut
```
double s = Math.sqrt((rKerucut*rKerucut) + (tKerucut*tKerucut));
```
Penjelasan:
Digunakan untuk mencari garis pelukis (s) menggunakan rumus Pythagoras.

s = √(r² + t²)

Volume Kerucut
```
(1.0/3) * Math.PI * r * r * t
```
Luas Permukaan Kerucut
```
Math.PI * r * (r + s)
```

5. Bola
```
double volumeBola = (4.0/3) * Math.PI * rBola * rBola * rBola;
double luasBola = 4 * Math.PI * rBola * rBola;
```
Penjelasan:

Volume Bola
V = 4/3 πr³

Luas Permukaan Bola
L = 4πr²

Kesimpulan Program
Program ini dibuat untuk menghitung volume dan luas permukaan beberapa bangun ruang yaitu:
Kubus
Balok
Tabung
Kerucut
Bola

Program menggunakan:

. Input Scanner

. Percabangan Switch Case

. Rumus Matematika Bangun Ruang

## output
<img width="1919" height="450" alt="Screenshot 2026-03-11 121605" src="https://github.com/user-attachments/assets/a2eac676-1258-4023-8e06-83da6acc1927" />
