# Mentor Curriculum Checklist (30 Days)

Checklist harian untuk menjalankan roadmap 30 hari Nuxt ecosystem track.

Gunakan status:

- `[ ]` belum dikerjakan
- `[~]` sedang dikerjakan
- `[x]` selesai

## Week 1 - Node.js + Nuxt Runtime Fundamentals

### Day 1 - Node.js Runtime
- [ ] Pahami event loop mental model
- [ ] Review `package.json` scripts (`dev/build/preview`)
- [ ] Jalankan app dan dokumentasikan lifecycle eksekusi
- [ ] Tulis 3 insight teknis

### Day 2 - Nuxt Server vs Client Context
- [ ] Jelaskan perbedaan kode yang jalan di server vs client
- [ ] Implement guard browser API (`localStorage/window`)
- [ ] Verifikasi tidak ada runtime error di SSR context
- [ ] Catat 2 potensi hydration issue

### Day 3 - Nuxt Structure
- [ ] Audit struktur `app/`, `pages/`, `components/`, `composables/`, `server/api/`
- [ ] Buat struktur folder feature kecil
- [ ] Pisahkan logic UI dan logic data
- [ ] Review naming consistency

### Day 4 - Routing, Layout, Middleware
- [ ] Buat minimal 2 route + 1 nested route
- [ ] Gunakan layout yang sesuai
- [ ] Implement middleware check sederhana
- [ ] Verifikasi redirect/guard flow

### Day 5 - Data Fetching Strategy
- [ ] Implement use case `useFetch`
- [ ] Implement use case `useAsyncData`
- [ ] Tulis kapan pakai masing-masing
- [ ] Dokumentasikan trade-off singkat

## Week 2 - Vue 3 + TypeScript Applied

### Day 6 - Reactivity
- [ ] Gunakan `ref` dan `computed` untuk derived state
- [ ] Hindari logic berat di template
- [ ] Verifikasi perubahan state memicu UI sesuai ekspektasi
- [ ] Catat 2 anti-pattern yang dihindari

### Day 7 - Component Contracts
- [ ] Definisikan props yang jelas
- [ ] Implement emits untuk interaction
- [ ] Gunakan slot untuk fleksibilitas
- [ ] Verifikasi komponen reusable di 2 konteks

### Day 8 - Composable Design
- [ ] Ekstrak logic dari component ke composable
- [ ] Kembalikan state `data/loading/error`
- [ ] Tambahkan typing return composable
- [ ] Uji composable pada minimal 1 halaman

### Day 9 - TypeScript in Nuxt/Vue
- [ ] Type props, emits, dan API response
- [ ] Gunakan union type atau narrowing di error flow
- [ ] Hindari `any` di code baru
- [ ] Catat 3 error TS yang berhasil diselesaikan

### Day 10 - Weekly Mini Build
- [ ] Build mini feature end-to-end
- [ ] Terapkan composable + typed flow
- [ ] Handle loading/error/empty states
- [ ] Demo singkat hasil minggu 2

## Week 3 - Nuxt UI + Tailwind Styling

### Day 11 - Nuxt UI Component-First
- [ ] Mapping Figma/custom blocks ke komponen Nuxt UI
- [ ] Gunakan `UCard/UButton/UInput/UBadge` sesuai kebutuhan
- [ ] Hindari custom HTML jika sudah ada padanan Nuxt UI
- [ ] Tulis daftar komponen yang dimigrasikan

### Day 12 - Nuxt UI Form Patterns
- [ ] Implement form dengan feedback error
- [ ] Handle submit/pending state
- [ ] Verifikasi UX state (default/error/success)
- [ ] Review konsistensi label dan hint

### Day 13 - Tailwind Fundamentals
- [ ] Terapkan spacing/typography scale konsisten
- [ ] Gunakan responsive modifiers
- [ ] Gunakan state modifiers (`hover/focus/disabled`)
- [ ] Buat token mapping mini dari design ke class

### Day 14 - Tailwind Maintainability
- [ ] Rapikan class yang terlalu panjang/duplikat
- [ ] Kelompokkan class secara konsisten
- [ ] Review readability komponen
- [ ] Catat 3 improvement maintainability

### Day 15 - UI Consistency Review
- [ ] Audit visual consistency lintas halaman
- [ ] Cek state UI utama (default/hover/focus/disabled/loading)
- [ ] Cek aksesibilitas dasar (kontras + keyboard)
- [ ] Susun backlog perbaikan prioritas

## Week 4 - Production Fundamentals

### Day 16 - API Integration Strategy
- [ ] Implement list endpoint + mutation endpoint
- [ ] Normalisasi error message
- [ ] Verifikasi success/error states konsisten
- [ ] Catat retry/fallback strategy sederhana

### Day 17 - State Management Strategy
- [ ] Tentukan local vs shared state boundary
- [ ] Gunakan `useState`, Pinia, atau composable sesuai kasus
- [ ] Dokumentasikan alasan pemilihan
- [ ] Verifikasi tidak ada state duplication yang tidak perlu

### Day 18 - Performance + A11y Baseline
- [ ] Terapkan lazy-loading atau split komponen berat
- [ ] Audit semantic structure
- [ ] Audit keyboard interactions dasar
- [ ] Dokumentasikan before/after improvement

### Day 19 - Testing Mindset
- [ ] Tulis test plan unit/integration/E2E
- [ ] Prioritaskan flow kritikal
- [ ] Definisikan expected behavior per test case
- [ ] Review risk area yang belum ter-cover

### Day 20 - Final Demo
- [ ] Demo mini app end-to-end
- [ ] Jelaskan keputusan arsitektur inti
- [ ] Presentasikan trade-off dan backlog
- [ ] Tulis rencana 2 minggu lanjutan

---

## Checklist Tambahan per Track

### Track Desainer (Figma -> Code)
- [ ] Buat component mapping table (Figma -> Nuxt UI)
- [ ] Buat token mapping table (Figma -> Tailwind/theme)
- [ ] Lakukan visual QA state-based
- [ ] Catat kompromi fidelity vs engineering constraints

### Track Profesional (Karyawan Umum)
- [ ] Kumpulkan weekly summary 1 halaman
- [ ] Lakukan presentasi teknis mingguan (5 menit)
- [ ] Dokumentasikan bug dan cara debug
- [ ] Simpan keputusan teknis penting (decision log)
