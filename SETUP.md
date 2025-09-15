# Setup Project Darat Farm

## Prerequisites
- Node.js (versi 18 atau lebih tinggi)
- npm atau yarn
- Akun Appwrite (untuk backend services)

## Langkah-langkah Setup

### 1. Install Dependencies
```bash
npm install --legacy-peer-deps
```

### 2. Konfigurasi Environment Variables
Salin file `.env.example` menjadi `.env` dan isi dengan nilai yang sesuai:

```bash
cp .env.example .env
```

Edit file `.env` dan isi dengan konfigurasi Appwrite Anda:
- `NEXT_PUBLIC_APPWRITE_ENDPOINT`: URL endpoint Appwrite
- `NEXT_PUBLIC_APPWRITE_PROJECT`: Project ID Appwrite
- `NEXT_PUBLIC_APPWRITE_DATABASE_ID`: Database ID
- `NEXT_APPWRITE_KEY`: API Key Appwrite
- Dan konfigurasi lainnya sesuai kebutuhan

### 3. Menjalankan Development Server
```bash
npm run dev
```

Aplikasi akan berjalan di `http://localhost:3000`

### 4. Build untuk Production
```bash
npm run build
npm start
```

## Catatan
- Project ini menggunakan Next.js 14 dengan App Router
- UI menggunakan Tailwind CSS dan Radix UI components
- Backend menggunakan Appwrite sebagai BaaS (Backend as a Service)
- Pastikan semua environment variables sudah dikonfigurasi dengan benar sebelum menjalankan aplikasi