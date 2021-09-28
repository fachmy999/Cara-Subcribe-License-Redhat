# Cara-Subcribe-License-Redhat
Tutorial subcribe license redhat

# Prosedur Subcribe License Redhat :

- Pastikan Red Hat anda terkoneksi ke internet dengan mencoba perintah : 

```
ping 8.8.8.8
```

- Check Subcription status : 

```
subscription-manager list
```

- Register Subcription dengam memasukan Username & Password Redhat : 

```
subscription-manager register
```

- Menampilkan Subscriptions yang tersedia (Available Subscriptions) dengan menjalankan perintah : 

```
subscription-manager list –-available
```

- Gunakan Pool ID yang muncul pada Available Subscriptions untuk melakukan pendaftaran. Jalankan Perintah : 

```
subscription-manager subscribe --pool=xxxxxxxxxxx
```

- Tampilkan kembali status subscription, untuk melihat apakah apakah RHEL Subscription sudah aktif atau belum. Untuk melihatnya jalankan perintah :

```
subscription-manager list
```

- Selesai Subcribtion RedHat License

# Prosedur Unregister Subscription Redhat
Cara Unregister Redhat Subscription Jika Anda ingin membatalkan registrasi sistem, Anda harus menggunakan perintah berikut:

- Menghapus semua Subscription dari sistem: 

```
subscription-manager remove --all
```

- Membatalkan registrasi sistem dari Customer Portal: 

```
subscription-manager unregister
```

- Bersihkan semua Subscription : 

```
subscription-manager clean
 ```
 
- Selesai Unregister Subcribtion RedHat License
 



