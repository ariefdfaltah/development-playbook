# Tickets
---

# Pre Development
---

## 1. Backend, Frontend, Mobile & Quality Assurance
<details>
  <summary>1.1. Research Package or Module or Application</summary>
  
  ### "Research Package or Module or Application"
  #### Deskripsi
  Programmer Backend, Frontend dan Mobile serta Quality Assurance melakukan uji coba pada sebuah paket atau module atau aplikasi untuk mendukung pengembangan. Apabila dibutuhkan waktu lebih untuk melakukan aktivitas ini dapat koordinasi dengan PM dan EM produk terkait

  #### Standar
  Pada Programmer Backend yang menggunakan bahasa pemrograman Golang, NodeJS, Python dan PHP umunnya akan mencari di github.
  Pada Programmer Frontend yang menggunakan JavaScript umumnya akan mencari di npm.
  Pada Programmer Mobile dapat menyesuaikan dengan kebutuhan masing masing
  Pada Quality Assurance apabila membutuhkan tools untuk test seperti K9, Cypress dan lain lain memerlukan informasi dari website masing masing aplikasi. 

  #### Pembobotan
  Effort untuk melakukan aktivitas ini di sama ratakan sebesar 2 story point dan output berupa dokumen tertulis seperti notion, file text  dan dikirimkan via email perusahaan.


</details>

# Development
---
## 2. Backend
<details>
  <summary>2.1. Create Endpoint</summary>

  ### "Create Endpoint"
  #### Deskripsi
  Membuat endpoint akan dilakukan oleh programmer Backend untuk memenuhi proses bisnis yang di butuhkan. Aktivitas ini di kategorikan sebagai :

  1. Membuat sebuah route baru yang belum pernah ada
  2. Membuat sebuah route yang sama dengan yang sudah ada namun berbeda HTTP method yang digunakan
  #### Standar
  Aktivitas ini memiliki sebuah standar pengerjaan seperti
  1. Penerapan pengecekan _Value_ pada _URL Params_ dan _URL Query Params_ sesuasi kebutuhan dan mencakupi _negative case_ - GET Detail
  2. Penerapan pengecekan _Value_ pada _HTTP Body_ yang digunakan pada _HTTP Body Form-Data_, _HTTP Body Raw_ dan _HTTP x www url encoded_ sesuai kebutuhan dan mencakupi _negative case_ - POST data dan PUT data
  3. Penerapan pengecekan _Meta_ pada _HTTP Response_ dengan menyertakan informasi _page_, _per_page_, _total_ - GET list data
  #### Pembobotan
  Aktivitas ini memiliki pembobotan awal dan dapat berkembang yang dibagi tiga dengan detail :

  1. **Simple - 2 Story Point**
  <br>Aktivitas "Create Endpoint" digolongkan _simple_ apabila melakukan satu proses yang terhubung ke database untuk mengambil, merubah atau menambahkan suatu _value. Setiap endpoint diharuskan memiliki log baik internal ataupun di Datadog. Aktivitas harus memenuhi semua kriteria dibawah :
      1. Melakukan validasi _Value_ dari _URL Params_
      2. Melakukan validasi _Value_ dari _URL Query Params_
      3. Melakukan validasi _Value_ dari _HTTP Body_

      Contoh :
        <code style="color : red">Endpoint Activate Data</code>
        <code style="color : red">Endpoint Deactivate Data</code>
        <code style="color : red">Endpoint Get Detail Data</code>
        <code style="color : red">Endpoint Create Data</code>
  &nbsp;

  2. **Compound - 4 Story Point**
  <br>Aktivitas "Create Endpoint" digolongkan _compound_ apabila memenuhi semua aktivitas golongan _simple_ dan minimal satu dari aktivitas dibawah :
       1. Melakukan Proses Encrypt & Decrypt
       2. Terhubung ke layanan pendukung seperti Google Cloud Storage, Google Pub/Sub dan service lainnya
       3. Endpoint membutuhkan _route internal_ dan _route external_ agar bisa digunakan

      Contoh :
        <code style="color : red">Endpoint Create Data with Image</code>
        <code style="color : red">Endpoint Post Data Background Process</code>
        <code style="color : red">Endpoint Get Detail Data with Presigned Image</code>
        <code style="color : red">Endpoint Create Data</code>
  &nbsp;

  3. **Complex - 6 Story Point**
  <br>Aktivitas "Create Endpoint" digolongkan _complex_ apabila memenuhi semua aktivitas golongan _compound_ dan minimal satu dari aktivitas dibawah :
       1. Terhubung ke pihak ketiga secara langsung untuk melakukan pengiriman email, OTP dan kebutuhan lainnya
       2. Terhubug ke pihak ketiga antar produk di privy seperti PrivyTool, PrivySign, PrivyCarstenz dan service lainnya
       3. Melakukan proses yang membutuhkan _service_ lain untuk memastikan kebutuhan bisnis berjalan seperti _generate document_ ataupun hal yang setara dengan hal tersebut

      Contoh :
        <code style="color : red">Endpoint Submit Data and Generate Document</code>
        <code style="color : red">Endpoint Submit Data and Send Push Notification</code>
</details>
