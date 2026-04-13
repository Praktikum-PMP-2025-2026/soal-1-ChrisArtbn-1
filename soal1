/** EL2008 Praktikum Pemecahan Masalah dengan Pemrograman 2024/2025
 *   Modul               : 01 - Overview of C Language
 *   Hari dan Tanggal    : Senin, 13 Mei 2026
 *   Nama (NIM)          : 13224043
 *   Nama File           : soal1.c
 *   Deskripsi           : Implementasi fungsi if else untuk melakukan pengecekan terhadap
 *                         izin, suhu, radiasi, dan jam untuk menentukan apakah 
 *                         seseorang dapat masuk, ditolak, atau dikarantina
 */

#include <stdio.h>
#include <math.h>

int main(){
    int izin;
    double suhu;
    unsigned int radius;
    double suhu_temp;
    int jam;

    printf("Masukkan izin, suhu, radiasi, dan jam :" );
    scanf("%d %lf %u %d", &izin, &suhu, &radius, &jam);

    suhu_temp = suhu * 0.1;

    if (radius >= 6){
    printf("TOLAK");}

    else if(suhu >= 390){
    printf("KARANTINA");}

    else if(izin == 1 && (jam < 6 || jam > 20)){
    printf("TOLAK");}

    else if(izin == 1){
    printf("MASUK");}

    else if(izin == 2 && (radius <= 2 && jam >= 8 && jam <= 18)){
    printf("MASUK");}

    else if(izin == 2){
    printf("PEMERIKSAAN");}

    else if(izin == 3 && radius == 0 && suhu < 380){
    printf("MASUK");}

    else{
    printf("TOLAK");}

    return 0;
}



