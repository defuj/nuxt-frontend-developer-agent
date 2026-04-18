# Mentor Weekly Assignments (Nuxt Ecosystem Track)

Dokumen tugas mingguan untuk learner track Nuxt ecosystem.

## Tujuan Dokumen

- Memberi tugas terstruktur per minggu
- Menyamakan ekspektasi hasil belajar
- Menyediakan rubrik penilaian yang objektif

## Skema Penilaian

Skor total per minggu: **100**

- Implementasi teknis: 35
- Arsitektur dan maintainability: 20
- UI consistency (Nuxt UI + Tailwind): 15
- Reliability (error handling/performance/a11y basics): 15
- Komunikasi reasoning teknis: 15

Nilai akhir rekomendasi:

- 85-100: Sangat baik (siap naik level)
- 70-84: Baik (perlu minor perbaikan)
- 55-69: Cukup (butuh penguatan area inti)
- <55: Perlu remedial terstruktur

---

## Week 1 Assignment - Runtime & Framework Context

### Brief
Bangun mini Nuxt app dengan minimal 3 halaman, 1 layout, dan 1 middleware dummy.

### Requirements
1. Minimal 3 route (`/`, `/catalog`, `/profile` atau setara)
2. 1 route dilindungi middleware check sederhana
3. Tunjukkan pemahaman server/client context pada minimal 1 komponen
4. Sertakan catatan kapan data sebaiknya di-fetch di SSR vs CSR

### Deliverables
- Source code feature minggu 1
- Dokumen singkat: `week1-decision-note.md`
- Demo 3-5 menit

### Rubrik Week 1
- Routing/layout/middleware benar (25)
- SSR/client context dipahami (25)
- Struktur folder rapi (20)
- Kejelasan decision note (15)
- Demo communication (15)

---

## Week 2 Assignment - Vue Architecture + Type Safety

### Brief
Bangun feature list-detail dengan komponen reusable + composable + TypeScript.

### Requirements
1. Minimal 2 komponen reusable (card/list item + detail section)
2. Gunakan 1 composable untuk data flow
3. Type-safe props, emits, dan response model
4. Handle loading/error/empty states

### Deliverables
- Source code feature minggu 2
- Dokumen singkat: `week2-architecture-note.md`
- Demo 5 menit

### Rubrik Week 2
- Component contract quality (25)
- Composable design quality (25)
- TypeScript correctness (20)
- State handling quality (15)
- Reasoning and clarity (15)

---

## Week 3 Assignment - Design System to Code

### Brief
Implement satu flow UI berdasarkan referensi desain (Figma/mock) dengan Nuxt UI + Tailwind.

### Requirements
1. Gunakan Nuxt UI sebagai basis komponen utama
2. Gunakan Tailwind class secara konsisten dan maintainable
3. Sertakan state visual: default, hover, focus, disabled, loading
4. Buat mapping table:
   - Figma component -> Nuxt UI component
   - Figma token -> Tailwind utility/theme

### Deliverables
- Source code UI flow minggu 3
- `week3-figma-to-code-mapping.md`
- Visual QA checklist
- Demo 5-7 menit

### Rubrik Week 3
- Nuxt UI adoption correctness (25)
- Tailwind consistency and cleanliness (20)
- Design fidelity with sensible trade-off (20)
- State completeness + accessibility basics (20)
- Mapping documentation quality (15)

---

## Week 4 Assignment - Production Fundamentals Capstone

### Brief
Final mini app: list + detail + create/update action dengan quality baseline production.

### Requirements
1. Data flow end-to-end (read + mutation)
2. Shared state strategy yang jelas
3. Error handling yang konsisten
4. Performance baseline improvement minimal 1 area
5. Test plan (unit/integration/E2E) untuk flow kritikal

### Deliverables
- Final mini app
- `week4-capstone-report.md`
- Test plan 8-12 test case
- Demo final 7-10 menit

### Rubrik Week 4
- End-to-end feature completeness (25)
- Architecture and state decisions (20)
- Reliability/error handling quality (20)
- Performance + accessibility baseline (15)
- Test plan + technical communication (20)

---

## Penyesuaian Berdasarkan Track

### Track Desainer (UI/UX + Figma)

Tambahan penilaian:

- Akurasi translasi design token (+10 bonus)
- Kelengkapan QA visual (+5 bonus)

Fokus feedback:

- Konsistensi komponen
- Fidelity desain yang realistis
- State interaction detail

### Track Profesional (Karyawan Umum)

Tambahan penilaian:

- Dokumentasi reasoning teknis (+10 bonus)
- Kualitas presentasi teknis (+5 bonus)

Fokus feedback:

- Kejelasan pilihan arsitektur
- Kedewasaan proses debugging
- Konsistensi kualitas implementasi

---

## Feedback Template (Per Minggu)

Gunakan format ini:

```markdown
Feedback Minggu [x]

Skor: [0-100]

Yang sudah bagus:
- ...
- ...

Yang perlu ditingkatkan:
- ...
- ...

Prioritas utama minggu depan:
- ...

Referensi yang direkomendasikan:
- ...
```

---

_Dokumen ini dipakai bersama roadmap 30 hari untuk memastikan proses belajar tetap terukur, praktis, dan relevan dengan kebutuhan Nuxt ecosystem._
