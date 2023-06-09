# Tickets
---

# Pre Development
---
## 1. Backend, Frontend, Mobile & Quality Assurance
<details>
  <summary>1.1. Research Package or Module or Application</summary>
  
  ### "Research Package or Module or Application :: Code=11"
  #### Deskripsi
  Menguji coba dan melakukan riset terhadap sebuah _package_, _module_ dan _application_ akan dilakukan oleh programmer Backend, Frontend dan Mobile serta Quality Assurance untuk membantu proses pengembangan _software_. Aktivitas ini dapat dilakukan dalam beberapa bentuk seperti : 

  1. Bertanya kepada teman kerja yang pernah mengerjakan dengan _case_ yang sama atau menyerupai
  2. Membaca dokumentasi melalui GitHub, NPM, Go Package ataupun website resmi aplikasi
  3. Melakukan uji coba terhadap _package_ dan _module_ untuk di implementasi
  4. Melakukan instalasi _application_ diperangkat kerja dan di uji coba

  #### Standar
  Aktivitas ini memiliki sebuah standar pengerjaan seperti :

  1. Membuat dokumentasi dari sebuah _package_ dan _module_ yang diuji coba serta rangkuman akhir apakah _package_ dan _module_ dapat digunakan.
  2. Membuat dokumentasi dari sebuah _application_ yang diinstall dan diuji coba beserta screenshot penggunaan dapat digunakan erta rangkuman akhir apakah _application_ dapat digunakan.

  #### Pembobotan
  Aktivitas ini memiliki pembobotan awal dan dapat berkembang dengan detail :
  
  1. **Research - 2 Story Point**
  <br>Aktivitas "Research Package or Module or Application" digolongkan _research_, apabila dibutuhkan waktu lebih untuk melaksanakan aktivitas ini dapat menghubungi PM dan EM produk terkait.

      Contoh :
        <code style="color : red">Research Face Detection on Nuxt</code>
        <code style="color : red">Research Face Detection on Swift</code>
        <code style="color : red">Research K9 for Analyze on Endpoint</code>
        <code style="color : red">Research Data Stream on Golang Avoid Create File</code>


</details>

# Development
---
## 2. Backend
<details>
  <summary>2.1. Create Endpoint</summary>

  ### "Create Endpoint :: Code=21"
  #### Deskripsi
  Membuat endpoint akan dilakukan oleh programmer Backend untuk memenuhi proses bisnis yang di butuhkan. Aktivitas ini dikategorikan sebagai :

  1. Membuat sebuah route baru yang belum pernah ada
  2. Membuat sebuah route yang sama dengan yang sudah ada namun berbeda HTTP method yang digunakan
  #### Standar
  Aktivitas ini memiliki sebuah standar pengerjaan seperti :
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

<details>
  <summary>2.2. Fixing Endpoint</summary>

  ### "Fixing Endpoint :: Code=22"
</details>

<details>
  <summary>2.3. Update Endpoint</summary>

  ### "Update Endpoint :: Code=23"
</details>

<details>
  <summary>2.4. Create Function</summary>

  ### "Create Function :: Code=24"
</details>

<details>
  <summary>2.5. Fixing Function</summary>

  ### "Fixing Function :: Code=25"
</details>

<details>
  <summary>2.6. Update Function</summary>

  ### "Update Function :: Code=26"
</details>

<details>
  <summary>2.7. Create Client</summary>

  ### "Create Client :: Code=27"
</details>

<details>
  <summary>2.8. Fixing Client</summary>

  ### "Fixing Client :: Code=28"
</details>

<details>
  <summary>2.9. Update Client</summary>

  ### "Update Client :: Code=29"
</details>

<details>
  <summary>2.10. Create API Contract</summary>

  ### "Create API Contract :: Code=210"
</details>

<details>
  <summary>2.11. Update API Contract</summary>

  ### "Update API Contract :: Code=211"
</details>