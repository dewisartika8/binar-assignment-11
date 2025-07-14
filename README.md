# binar-assignment-11

## Cara Menjalankan Project & Test di MacBook

### 1. Clone Repository
```bash
git clone https://github.com/dewisartika8/binar-assignment-11.git
cd binar-assignment-11
```

### 2. Install Dependencies
```bash
npm install
```

### 3. Menjalankan Test & Coverage
```bash
npm test
```

### 4. Melihat Laporan Coverage
Setelah menjalankan test, buka file berikut untuk melihat laporan coverage dalam bentuk HTML:
```bash
open coverage/lcov-report/index.html
```

### 5. Catatan
- Pastikan Node.js & npm sudah terinstall di MacBook.
- Jika belum, install dengan:
  ```bash
  brew install node
  ```

### 6. Troubleshooting
- Jika ada error terkait `package.json` atau dependency, ulangi langkah install dependencies.
- Untuk menambah/mengedit test, buat file baru dengan akhiran `.test.js`.

---