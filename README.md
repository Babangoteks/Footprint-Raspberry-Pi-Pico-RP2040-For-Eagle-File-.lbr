# Raspberry Pi Pico (RP2040) EAGLE Library (.lbr)

Pustaka komponen (library `.lbr`) Autodesk EAGLE untuk **Raspberry Pi Pico / RP2040**. Didesain dengan presisi mengikuti spesifikasi dimensi resmi dari Raspberry Pi Trading Ltd.

## Fitur Footprint
* **Dual-mounting design:** Mendukung pemasangan mode *Through-Hole* (pin header 2.54mm) maupun *SMD Surface Mount* menggunakan *castellated holes*.
* **Presisi Tinggi:** Jarak antar pin dan ukuran pad disesuaikan untuk kemudahan *soldering* manual maupun pabrikasi PCB.
* **Pinout Lengkap:** Pemetaan nama pin pada simbol skematik sudah disesuaikan dengan dokumentasi resmi RP2040 (GPIO, UART, I2C, SPI, ADC, Power).

## Cara Penggunaan
1. Unduh atau *clone* repository ini.
2. Salin berkas `.lbr` ke dalam folder library EAGLE kamu (biasanya di `Documents/EAGLE/libraries`).
3. Buka Autodesk EAGLE, aktifkan library (`Use`), lalu cari komponen **Raspberry Pi Pico**.
