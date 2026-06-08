<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>KARYA - Platform Karier Inklusif</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Lexend:wght@100..900&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&display=swap" rel="stylesheet">
    <style>
        body { font-family: 'Lexend', sans-serif; }
    </style>
</head>
<body class="bg-[#fcf9f8] text-[#1b1c1c]">

    <!-- Navbar -->
    <nav class="fixed top-0 w-full z-50 bg-white shadow-md">
        <div class="flex justify-between items-center px-8 py-4 max-w-screen-2xl mx-auto">
            <div class="text-2xl font-black text-[#001855] tracking-tighter">KARYA</div>
            <div class="hidden md:flex items-center gap-8">
                <a href="#lowongan" class="text-slate-600 hover:text-[#001855]">Lowongan</a>
                <a href="#tentang" class="text-slate-600 hover:text-[#001855]">Tentang</a>
                <a href="login.html" class="text-slate-600 hover:text-[#001855]">Masuk</a>
            </div>
            <div class="flex items-center gap-4">
                <a href="register.html" class="bg-[#001855] text-white px-4 py-2 rounded-xl font-bold hover:bg-[#001855]/90">Daftar</a>
            </div>
        </div>
    </nav>

    <!-- Hero -->
    <main class="pt-24">
        <section class="px-8 py-20 max-w-screen-2xl mx-auto text-center">
            <h1 class="text-5xl md:text-7xl font-black text-[#001855] leading-tight">Kesempatan Aksi <br><span class="text-[#002a84]">Ruang Yang Aksesibel</span></h1>
            <p class="text-xl text-[#43474f] max-w-2xl mx-auto mt-6">Platform inklusif yang menghubungkan talenta penyandang disabilitas dengan perusahaan yang menghargai keberagaman.</p>
            <div class="flex gap-4 justify-center mt-8">
                <a href="login.html" class="bg-[#001855] text-white px-6 py-3 rounded-xl font-bold hover:bg-[#001855]/90">Cari Kerja</a>
                <a href="login.html" class="border border-[#001855] text-[#001855] px-6 py-3 rounded-xl font-bold hover:bg-[#001855]/10">Pasang Lowongan</a>
            </div>
        </section>

        <!-- Fitur -->
        <section class="bg-[#f6f3f2] py-20 px-8">
            <div class="max-w-screen-2xl mx-auto grid md:grid-cols-3 gap-8 text-center">
                <div class="bg-white p-6 rounded-2xl shadow-sm">
                    <span class="material-symbols-outlined text-5xl text-[#001855]">verified</span>
                    <h3 class="text-xl font-bold mt-4">Lowongan Terverifikasi</h3>
                    <p class="text-[#43474f]">Semua perusahaan mitra telah diverifikasi komitmen inklusifnya.</p>
                </div>
                <div class="bg-white p-6 rounded-2xl shadow-sm">
                    <span class="material-symbols-outlined text-5xl text-[#001855]">accessibility_new</span>
                    <h3 class="text-xl font-bold mt-4">Aksesibilitas Penuh</h3>
                    <p class="text-[#43474f]">Informasi aksesibilitas fisik dan digital tersedia untuk setiap lowongan.</p>
                </div>
                <div class="bg-white p-6 rounded-2xl shadow-sm">
                    <span class="material-symbols-outlined text-5xl text-[#001855]">community</span>
                    <h3 class="text-xl font-bold mt-4">Komunitas & Mentoring</h3>
                    <p class="text-[#43474f]">Dukungan sesama anggota dan bimbingan karier.</p>
                </div>
            </div>
        </section>

        <!-- CTA -->
        <section class="py-20 px-8 text-center bg-[#001855] text-white">
            <h2 class="text-3xl font-bold">Siap memulai kariermu?</h2>
            <p class="mt-2">Bergabunglah dengan ribuan talenta dan perusahaan inklusif.</p>
            <a href="register.html" class="inline-block mt-6 bg-[#feb700] text-[#001855] font-bold px-8 py-3 rounded-xl hover:bg-[#feb700]/90">Daftar Sekarang</a>
        </section>
    </main>

    <footer class="bg-[#f6f3f2] py-8 px-8 text-center text-sm text-[#737780]">
        © 2026 KARYA. Memberdayakan Kemampuan.
    </footer>
</body>
</html>
