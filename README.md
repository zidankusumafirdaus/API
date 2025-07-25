### Home Page
```json
[
  {
    "HomeDeskripsi": <string>,
  }
]
```
Statis: Tentang Komunitas & Dibimbing oleh Pakirwan 

### About Us Page
```json
[
  {
    "AboutDeskripsiKomunitas": <string>,
    "AboutDeskripsiVisi": <string>,
    "AboutDeskripsiMisi": <string>,
  }
]
```
Statis: Judul (tentang komunitas kami, Visi & Misi)

### Member Page
```json
{
  PEMBIMBING [
    {
      "NamaLengkap": <string>,
      "PhotoProfile": <ngga tau>,
      "Jabatan": pembimbing,
      "MemberDeskripsi": <string>,
      "GitHub": <string>,
      "LinkedIn": <string>,
      "Email": <string>,
      "Instagram": <string>,
    }
  ]

  GENERASI-1 [
    {
      "NamaLengkap": <string>,
      "PhotoProfile": <ngga tau>,
      "Jabatan": member,
      "Generasi": <enum>,
      "MemberDeskripsi": <string>,
      "GitHub": <string>,
      "LinkedIn": <string>,
      "Email": <string>,
      "Instagram": <string>,
    }
  ]

  GENERASI-2 [
    {
      "NamaLengkap": <string>,
      "PhotoProfile": <ngga tau>,
      "Jabatan": member,
      "Generasi": <enum>,
      "MemberDeskripsi": <string>,
      "GitHub": <string>,
      "LinkedIn": <string>,
      "Email": <string>,
      "Instagram": <string>,
    }
  ]

  GENERASI-3 [
    {
      "NamaLengkap": <string>,
      "PhotoProfile": <ngga tau>,
      "Jabatan": member,
      "Generasi": <enum>,
      "MemberDeskripsi": <string>,
      "GitHub": <string>,
      "LinkedIn": <string>,
      "Email": <string>,
      "Instagram": <string>,
    }
  ]

  ...
}
```
Statis: Judul (tentang komunitas kami, Visi & Misi)

### Project Page
```json
{
  OnGoing [
    {
      "Judul": <string>,
      "Status": <enum>,
      "DeskripsiSingkatProject": <string>,
      "Kontributor": <ngga tau>,
    }
  ]

  Finish [
    {
      "Judul": <string>,
      "Status": <enum>,
      "DeskripsiSingkatProject": <string>,
      "Kontributor": <ngga tau>,
    }
  ]
}
```
Statis: Judul & Deskripsi </br>
Addition: Filter (OnGoing & Finish), Live Search

### Project Page byID
```json
[
  {
    "Judul": <string>,
    "DeskripsiLengkapProject": <string>,
    "Preview": <ngga tau>,
    "PhotoProfile": <ngga tau>,
    "NamaLengkap": <string>,
    "LinkOutput": <string>,
  }
]
```

### Dashboard Page
```json
[
  {
    "PhotoProfile": <ngga tau>,
    "NamaLengkap": <string>,
    "Username": <string>,
    "DashboardDeskripsi": <ngga tau>,
    "Generasi": <enum>,
    "NamaLengkap": <string>,
    "LinkOutput": <string>,
  }
]
```
Addition: Edit Data Diri, Pengaturan Akun, & Tambah Project
