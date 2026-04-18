# Mentor Curriculum 30 Days (Nuxt Frontend Beginner)

Dokumen ini adalah roadmap belajar frontend 1 bulan untuk developer pemula dengan fokus **Nuxt 4 + Vue 3 + TypeScript + Nuxt UI**.

## Format Program

- Durasi: **4 minggu**
- Hari aktif: **5 hari kerja per minggu (Senin-Jumat)**
- Total hari belajar: **20 hari**
- Waktu per hari: **60-120 menit**
- Komposisi: **30% teori + 70% praktik**

## Learning Outcomes

Setelah menyelesaikan program ini, peserta diharapkan mampu:

1. Memahami fondasi web: browser, HTML, CSS, JavaScript
2. Membangun UI responsive dan semantic
3. Memahami konsep reactive UI di Vue dan struktur aplikasi Nuxt
4. Mengintegrasikan API dengan pola error/loading state yang baik
5. Menulis kode yang lebih aman, terstruktur, dan mudah dikembangkan

---

## Minggu 1 - Fondasi Web

**Tujuan minggu:** memahami cara kerja web dan membuat halaman statis yang rapi serta responsive dasar.

### Hari 1 (Senin): Internet & Browser Basics
- Materi: request/response, DNS, HTTP/HTTPS, render pipeline browser
- Praktik: inspeksi tab Network di DevTools
- Output: catatan alur dari URL sampai halaman tampil

### Hari 2 (Selasa): HTML Semantik
- Materi: struktur dokumen, semantic tags, hierarchy heading
- Praktik: buat landing page sederhana dengan semantic HTML
- Output: 1 halaman HTML semantik

### Hari 3 (Rabu): Form & Accessibility Dasar
- Materi: form element, label-input relation, validasi native dasar
- Praktik: buat form pendaftaran
- Output: form valid dengan label dan pesan error dasar

### Hari 4 (Kamis): CSS Basics & Box Model
- Materi: selector, specificity dasar, box model, spacing
- Praktik: styling halaman hari 2-3
- Output: layout lebih rapi dengan sistem spacing sederhana

### Hari 5 (Jumat): Flexbox & Responsive Dasar
- Materi: flex container/item, breakpoint dasar
- Praktik: ubah layout agar mobile-friendly
- Output: 1 halaman responsive (mobile + desktop)

---

## Minggu 2 - JavaScript Dasar ke Menengah

**Tujuan minggu:** memahami data manipulation, event, dan async flow di browser.

### Hari 6 (Senin): Variabel, Function, Scope
- Materi: `let`, `const`, function, scope
- Praktik: buat utility functions sederhana
- Output: 5 fungsi utility dasar

### Hari 7 (Selasa): Array & Object Operations
- Materi: `map`, `filter`, `find`, destructuring
- Praktik: olah data dummy menjadi data siap tampil
- Output: data transformation script

### Hari 8 (Rabu): DOM & Event
- Materi: query DOM, event listener, UI update
- Praktik: mini to-do app vanilla JS
- Output: to-do tambah/hapus item

### Hari 9 (Kamis): Async JavaScript
- Materi: Promise, async/await, try/catch
- Praktik: fetch data dari API publik
- Output: list data + error handling dasar

### Hari 10 (Jumat): Mini Project JavaScript
- Materi: penguatan konsep minggu 2
- Praktik: gabungkan DOM + fetch + state sederhana
- Output: mini dashboard tanpa framework

---

## Minggu 3 - Vue 3 & Nuxt 4 Fundamentals

**Tujuan minggu:** memahami reactive component architecture dan struktur Nuxt.

### Hari 11 (Senin): Vue Reactivity
- Materi: `ref`, `reactive`, `computed`, `watch`
- Praktik: counter + filtered list
- Output: komponen reactive sederhana

### Hari 12 (Selasa): Component Basics
- Materi: props, emits, parent-child communication
- Praktik: pecah UI ke beberapa komponen
- Output: komponen reusable dasar

### Hari 13 (Rabu): Nuxt Structure & Routing
- Materi: `pages/`, `components/`, `layouts/`, auto-import
- Praktik: buat 3 halaman dengan navigasi
- Output: app Nuxt multi-page dasar

### Hari 14 (Kamis): Nuxt Data Fetching
- Materi: `useFetch`, `useAsyncData`, SSR vs CSR
- Praktik: tampilkan data API di halaman Nuxt
- Output: halaman data dengan loading/error state

### Hari 15 (Jumat): Nuxt UI Integration
- Materi: `UCard`, `UButton`, `UInput`, `UForm`
- Praktik: bangun form + card list memakai Nuxt UI
- Output: mini feature page konsisten dengan Nuxt UI

---

## Minggu 4 - Engineering Essentials & Project

**Tujuan minggu:** menyelesaikan mini app dengan praktik engineering dasar.

### Hari 16 (Senin): TypeScript Frontend Basics
- Materi: interface/type, union, typing API response
- Praktik: tipekan data model dan props
- Output: komponen Nuxt typed dengan baik

### Hari 17 (Selasa): Form Validation & Error Handling
- Materi: validasi input, feedback error UX
- Praktik: create/edit form dengan validasi
- Output: form dengan validasi dan pesan error jelas

### Hari 18 (Rabu): Accessibility & Performance Basics
- Materi: semantic structure, keyboard, contrast, lazy loading dasar
- Praktik: audit ringan halaman sendiri
- Output: checklist a11y + daftar perbaikan

### Hari 19 (Kamis): Testing Mindset
- Materi: unit/integration/E2E overview
- Praktik: susun skenario test untuk mini app
- Output: 5-10 test cases tertulis

### Hari 20 (Jumat): Final Review Day
- Materi: recap, refactor ringan, quality checklist
- Praktik: demo mini app + jelaskan keputusan teknis
- Output: mini app siap demo + next iteration list

---

## Weekly Evaluation Rubric (Skor 1-5)

Nilai tiap akhir minggu pada aspek berikut:

1. Pemahaman konsep
2. Kualitas implementasi
3. Konsistensi latihan
4. Kemandirian debugging
5. Kesiapan naik level

Wajib tulis:
- 2 hal yang sudah bagus
- 2 hal yang perlu diperbaiki
- 1 fokus utama minggu berikutnya

## Daily Session Template

Gunakan template ini setiap hari:

```markdown
Hari ke-[x]

1) Teori (15-30 menit)
- [konsep inti]

2) Praktik (40-80 menit)
- [task coding kecil]

3) Refleksi (5-10 menit)
- Apa yang saya pahami hari ini?
- Apa yang masih membingungkan?
- Apa target besok?
```

## Rekomendasi Progression Setelah 30 Hari

Lanjutkan ke salah satu jalur:

1. Build 2-3 mini projects Nuxt tambahan
2. Mulai testing implementation nyata (Vitest + Playwright)
3. Dalami state management dan architecture patterns
4. Pelajari deployment dan observability dasar

---

_Dokumen ini dipakai oleh agent mentor untuk membimbing belajar frontend secara bertahap, praktis, dan konsisten._
