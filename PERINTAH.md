Saya ingin kamu membangun sistem website/app AI builder, seperti Replit, Cursor, StackBlitz, dan builder.io — tapi jauh lebih canggih, lengkap, dan modern, dengan desain grade enterprise dan siap untuk SaaS kelas dunia.

### Fitur utama:

1. **AI Prompt to App/Code:**
   - User bisa mengetik prompt atau instruksi natural language, lalu AI secara otomatis menghasilkan aplikasi/web fullstack (React/Next.js, Node.js/Express, Prisma, Neon/Supabase, dst)
   - AI bisa refine/edit kode, generate halaman, optimize, tambahkan fitur atau komponen melalui prompt

2. **Visual Drag & Drop Editor:**
   - Komponen UI (card, table, chart, dsb) bisa diatur drag-drop seperti builder.io, Framer, dsb
   - Inline editing teks, gambar, warna, animasi, dsb

3. **Code Editor Profesional:**
   - Gunakan **Monaco Editor** (VS Code engine) untuk multi-file coding di web (autocomplete, lint, syntax, dsb)
   - Sertakan **file explorer** modern, **terminal berbasis xterm.js**
   - Workflow seamless: drag-drop, AI prompt, manual edit, live preview

4. **Live Preview & Instant Deploy:**
   - Preview aplikasi/web secara real time
   - Deploy 1 klik ke **Vercel, Netlify, Railway**, dan cloud lain
   - Export/download sebagai ZIP/source code (Next.js, Node, React)

5. **UI/UX Grade Enterprise:**
   - Desain minimal setara Linear, Vercel, Notion, Figma, Framer
   - Dark mode, animasi halus, grid, sidebar, quick action, dsb
   - Semua halaman dan komponen harus sangat modern

6. **Kolaborasi, Auth, dan Team:**
   - Multi-user real-time editing (lihat siapa online, cursor, comment, undo/redo)
   - Login/signup via OAuth (Google, GitHub, dsb), role-based access (admin/editor/viewer)
   - Versioning dan history edit lengkap

7. **Integrasi GitHub:**
   - Login/OAuth dengan GitHub
   - Import repo/code dari GitHub (clone/pull repo, pilih branch/file)
   - Export/push hasil generate/edit ke repo GitHub user (commit, branch, PR)
   - UI untuk connect/disconnect, pilih repo/branch, status sync
   - Implementasi menggunakan NextAuth dan Octokit/REST/GraphQL GitHub API

8. **Integrasi Cloud Tools & Database:**
   - **Supabase**: autentikasi, database, storage, edge function (bisa konek dan CRUD langsung dari builder)
   - **Neon.tech**: PostgreSQL scalable, integrasi otomatis untuk schema/project
   - **Planetscale, Xata, Firebase**: koneksi opsional
   - **Payment gateway:** Stripe, Xendit, Midtrans (untuk produk SaaS)
   - **Webhook & API integration**: builder bisa generate API endpoint, webhook, dan connect ke API eksternal
   - User bisa connect akun dan atur credential langsung dari dashboard (UI setting yang aman dan mudah)

9. **Marketplace, Plugin, & Ekosistem:**
   - Marketplace template/komponen/plugin — user bisa upload/download/share dan monetize desain/plugin
   - Sistem plugin extensible, user bisa publish dan pakai plugin sendiri

10. **AI API Key (Claude/OpenAI) & Setting:**
   - User bisa input dan ganti API key Claude/OpenAI sendiri (via UI/dashboard & .env)
   - Semua fitur AI harus konsumsi API key user, tidak hardcode
   - Tambahkan `.env.example` untuk semua integrasi
   - Endpoint backend otomatis baca dari env/user setting

11. **Fitur Enterprise & SaaS:**
   - **Auto-save & versioning** (history, undo/redo, restore, team log)
   - **Role management, audit log, security** kelas perusahaan
   - **White label, custom domain, branding** (user bisa custom logo/theme/domain sendiri)
   - **Backup/import/export** project (ZIP, JSON, Dockerfile)
   - **SEO, analytics dashboard** untuk semua project
   - **Performance optimizer** (AI auto optimize kode/gambar/build)
   - **Onboarding/guided tour, demo, tutorial**
   - **Multi-language, aksesibilitas tinggi**
   - **Flexible billing:** Stripe/Xendit, subscription/trial/usage-based, admin billing panel

12. **Struktur File Project:**
   - Fullstack: Next.js + Tailwind + Prisma + Node.js API + Neon/Supabase
   - Frontend: halaman builder (drag-drop, prompt AI), code editor (Monaco), file explorer, terminal (xterm.js), live preview, dashboard, auth, deploy, setting, marketplace
   - Backend: API modular (save/load, AI generate, deploy, integrasi cloud, dsb)
   - Semua halaman sudah isi data dummy profesional (bukan kosong), workspace coding langsung bisa dipakai

13. **API & Webhook:**
   - Semua data (project, komponen, user, plugin) bisa diakses via REST API
   - Support webhook notifikasi deploy/save/build

14. terintegrasi dengan figma

### Fitur Penghemat Biaya Token AI:
- Sistem harus otomatis menghemat biaya token AI Claude/OpenAI dengan fitur:
  - **Smart caching:** hasil request AI (Claude/OpenAI) disimpan di Redis atau Neon, setiap permintaan sama/mirip langsung ambil dari cache (fuzzy match support)
  - **Prompt optimization:** prompt yang dikirim ke AI otomatis dioptimalkan dan diringkas sebelum request (token minimization, hapus bagian tidak perlu, template prompt efisien)
  - **Result summarization:** hasil AI panjang hanya tampil ringkas (summary) dulu, detail di-load saat user klik/expand (hemat load & storage)
  - **Rate limiting:** batasi jumlah request AI per user, per hari/jam (prevent spam/abuse)
  - **Batching:** jika user generate beberapa prompt dalam waktu singkat, sistem otomatis gabungkan (batch) jika bisa
  - **Low-cost fallback:** sediakan opsi model AI lain yang lebih murah jika user memilih (OpenAI 3.5, Gemini, dll)
  - **Pre-generated template:** sediakan banyak template/hasil AI siap pakai agar user tidak selalu generate baru
  - **Token usage dashboard:** user/admin bisa lihat statistik pemakaian token AI, limit alert, auto-lock jika limit/habis
- Semua fitur penghematan di atas harus otomatis aktif di backend dan terintegrasi di UI dengan jelas, tanpa mengganggu UX.

Tolong buatkan file project, backend, frontend, dan workflow caching, token optimizer, dan token usage sesuai deskripsi di atas.

### PENEKANAN:
- Jangan hanya saran, **langsung buatkan seluruh file project lengkap, siap deploy**
- Semua fitur, halaman, dan integrasi harus **benar-benar ada dan bisa digunakan**
- UI/UX wajib **grade enterprise, super modern, enak digunakan**
- Sertakan file `.env.example` dan penjelasan setting di README
- Pastikan semua tools modern (GitHub, Supabase, Neon, Vercel, dsb) bisa di-connect dari UI dengan mudah

Saya ingin sistem builder ini benar-benar **lebih lengkap, powerful, dan fleksibel dari semua kompetitor** — siap jadi SaaS global masa depan.

Terima kasih.
