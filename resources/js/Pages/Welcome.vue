<script setup>
import { Head, Link } from '@inertiajs/vue3';
</script>

<template>
    <Head title="SIKARA - Sistem Informasi Karir Mahasiswa">
        <link rel="preconnect" href="https://fonts.googleapis.com" />
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
        <link
            href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap"
            rel="stylesheet"
        />
        <link
            href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&display=swap"
            rel="stylesheet"
        />
    </Head>

    <div class="min-h-screen bg-[#f8f9ff] font-['Poppins'] text-[#0b1c30] antialiased">
        <header class="fixed top-0 z-50 w-full border-b border-slate-100 bg-white/90 shadow-sm backdrop-blur-md">
            <div class="mx-auto flex max-w-7xl items-center justify-between px-5 py-4 md:px-8">
                <div class="text-2xl font-bold tracking-tight text-blue-600">
                    <img
                        alt="SIKARA Logo"
                        class="h-14 w-auto object-contain"
                        src="https://lh3.googleusercontent.com/aida/ADBb0uhofiGVEP6GK3rKZi71d9s66U7hgpiUyVcxfmZCD0YwHCRU2bG6C6XnTTIGW6O8yiLY08HoAnBX3YzNgF8iwQGqYctS-pKAjaeEU9i0uJjGOJrrP2FWxJf5SZuve1IXHqjzdxSaT4UOZqy-n-zRNhxJtNGq1bDXGafAur-gUfoh2zRYXNYdtX3Ag91N44mSij2W1R3V0jUbPjW5XIUhpUZsb73ZXccg0zxFN0C-i6U6i0AZQOjEz0GOO6r62WhHsrwkMWpy_m0mtKA"
                    />
                </div>

                <nav class="hidden items-center gap-8 md:flex">
                    <a class="border-b-2 border-blue-600 font-semibold text-blue-600" href="#features">Features</a>
                    <a class="font-semibold text-slate-600 transition-colors hover:text-blue-600" href="#internships">Internships</a>
                    <a class="font-semibold text-slate-600 transition-colors hover:text-blue-600" href="#training">Training</a>
                </nav>

                <div class="flex gap-3 md:gap-4">
                    <Link
                        :href="route('login')"
                        class="rounded-md px-4 py-2 font-semibold text-[#004ac6] transition-all duration-150 hover:bg-slate-50 active:scale-95"
                    >
                        Login
                    </Link>
                    <Link
                        :href="route('register')"
                        class="rounded-lg bg-[#2563eb] px-5 py-2 font-semibold text-white shadow-[0_4px_12px_rgba(37,99,235,0.2)] transition-all duration-150 hover:opacity-90 active:scale-95 md:px-6"
                    >
                        Register
                    </Link>
                </div>
            </div>
        </header>

        <main class="pt-[100px]">
            <section class="relative mx-auto grid max-w-7xl grid-cols-1 items-center gap-12 overflow-hidden px-5 py-16 md:px-8 lg:grid-cols-2">
                <div class="absolute right-0 top-0 -z-10 h-[500px] w-[500px] translate-x-1/3 -translate-y-1/3 rounded-full bg-gradient-to-br from-[#dbe1ff] to-[#6ffbbe] opacity-30 blur-3xl"></div>

                <div class="relative z-10 space-y-8">
                    <div class="inline-flex items-center gap-2 rounded-full border border-[#c3c6d7] bg-[#e5eeff] px-3 py-1">
                        <span class="material-symbols-outlined text-[16px] text-[#004ac6]">rocket_launch</span>
                        <span class="text-xs font-semibold uppercase tracking-wider text-[#434655]">Platform Karir Resmi</span>
                    </div>

                    <h1 class="max-w-3xl text-4xl font-bold leading-tight text-[#0b1c30] md:text-5xl">
                        Mulai Langkah Karirmu Lebih Awal Bersama
                        <span class="text-[#004ac6]">SIKARA</span>
                    </h1>

                    <p class="max-w-xl text-lg leading-8 text-[#434655]">
                        Sistem Informasi Karir Mahasiswa. Platform terpusat untuk mengelola profil profesional,
                        menemukan peluang magang terbaik, dan mengikuti pelatihan berstandar industri.
                    </p>

                    <div class="flex flex-wrap gap-4 pt-4">
                        <Link
                            :href="route('register')"
                            class="flex items-center gap-2 rounded-lg bg-[#2563eb] px-8 py-4 font-semibold text-white shadow-[0_8px_24px_rgba(37,99,235,0.25)] transition-opacity hover:opacity-90"
                        >
                            Daftar Sekarang
                            <span class="material-symbols-outlined">arrow_forward</span>
                        </Link>
                        <a
                            href="#features"
                            class="rounded-lg border-2 border-[#004ac6] bg-transparent px-8 py-4 font-semibold text-[#004ac6] transition-colors hover:bg-[#eff4ff]"
                        >
                            Pelajari Selengkapnya
                        </a>
                    </div>
                </div>

                <div class="relative z-10">
                    <div class="relative overflow-hidden rounded-xl border border-[#d3e4fe] shadow-[0_20px_40px_rgba(37,99,235,0.1)]">
                        <img
                            alt="Student collaboration"
                            class="aspect-[4/3] h-auto w-full object-cover"
                            src="https://lh3.googleusercontent.com/aida-public/AB6AXuBFlBWar7XeVYuycKmtbVhqx1FPDlNkxrmI4MVUblCo7qCnCUvc6VSqRHgvZJgaLj2hh2Lbl3RkA6-h885QA-oXvtixl4AZxoPitHyoyoAJaI09019-4NtSHKtlQZjXrL7EL9CrWTe7oGBn_VNc-bGYxdaQPzVg1FKTnidp-hu9Ii3-O1FinNY7pAd-bicGmm4_asJZo9CiUtS_4YUZIiyQumJUkq-EQ24WiVkzhqR9n9SMjvE0yt1LNhBFhMW-Z8B46t4QcuqG7ecz"
                        />
                    </div>
                </div>
            </section>

            <section id="features" class="border-y border-[#c3c6d7]/30 bg-white py-16">
                <div class="mx-auto max-w-7xl px-5 md:px-8">
                    <div class="mx-auto mb-16 max-w-2xl space-y-4 text-center">
                        <h2 class="text-4xl font-bold leading-tight text-[#0b1c30]">Layanan Terintegrasi</h2>
                        <p class="leading-7 text-[#434655]">
                            Tiga pilar utama SIKARA untuk memastikan transisi yang mulus dari dunia akademik ke
                            industri profesional.
                        </p>
                    </div>

                    <div class="grid grid-cols-1 gap-6 md:grid-cols-3">
                        <article class="group rounded-xl border border-[#c3c6d7]/50 bg-[#eff4ff] p-8 shadow-sm transition-transform hover:-translate-y-1">
                            <div class="mb-6 flex h-14 w-14 items-center justify-center rounded-lg bg-[#004ac6]/10">
                                <span class="material-symbols-outlined text-[28px] text-[#004ac6]">person</span>
                            </div>
                            <h3 class="mb-3 text-2xl font-semibold text-[#0b1c30]">Career Management</h3>
                            <p class="mb-6 text-sm leading-6 text-[#434655]">
                                Bangun profil profesional Anda. Upload CV, portofolio, dan sertifikasi untuk menarik
                                perhatian rekruter.
                            </p>
                            <Link :href="route('register')" class="inline-flex items-center font-semibold text-[#004ac6] transition-all group-hover:gap-2">
                                Mulai Bangun Profil
                                <span class="material-symbols-outlined text-[18px]">chevron_right</span>
                            </Link>
                        </article>

                        <article id="internships" class="group relative overflow-hidden rounded-xl border border-[#c3c6d7]/50 bg-[#eff4ff] p-8 shadow-sm transition-transform hover:-translate-y-1">
                            <div class="absolute right-0 top-0 -z-0 h-32 w-32 rounded-bl-full bg-[#6cf8bb]/20"></div>
                            <div class="relative z-10 mb-6 flex h-14 w-14 items-center justify-center rounded-lg bg-[#006c49]/10">
                                <span class="material-symbols-outlined text-[28px] text-[#006c49]">work</span>
                            </div>
                            <h3 class="relative z-10 mb-3 text-2xl font-semibold text-[#0b1c30]">Internship Search</h3>
                            <p class="relative z-10 mb-6 text-sm leading-6 text-[#434655]">
                                Temukan ribuan peluang magang tersertifikasi dari mitra industri terkemuka di seluruh
                                Indonesia.
                            </p>
                            <Link :href="route('login')" class="relative z-10 inline-flex items-center font-semibold text-[#006c49] transition-all group-hover:gap-2">
                                Cari Lowongan
                                <span class="material-symbols-outlined text-[18px]">chevron_right</span>
                            </Link>
                        </article>

                        <article id="training" class="group rounded-xl border border-[#c3c6d7]/50 bg-[#eff4ff] p-8 shadow-sm transition-transform hover:-translate-y-1">
                            <div class="mb-6 flex h-14 w-14 items-center justify-center rounded-lg bg-[#4d556b]/10">
                                <span class="material-symbols-outlined text-[28px] text-[#4d556b]">school</span>
                            </div>
                            <h3 class="mb-3 text-2xl font-semibold text-[#0b1c30]">Career Training</h3>
                            <p class="mb-6 text-sm leading-6 text-[#434655]">
                                Tingkatkan skill melalui modul pelatihan interaktif dan webinar eksklusif dari praktisi
                                industri.
                            </p>
                            <a class="inline-flex items-center font-semibold text-[#4d556b] transition-all group-hover:gap-2" href="#dashboard-preview">
                                Lihat Modul
                                <span class="material-symbols-outlined text-[18px]">chevron_right</span>
                            </a>
                        </article>
                    </div>
                </div>
            </section>

            <section id="dashboard-preview" class="mx-auto max-w-7xl px-5 py-16 md:px-8">
                <div class="relative overflow-hidden rounded-2xl border border-[#c3c6d7]/50 bg-[#e5eeff] p-8 lg:p-12">
                    <div class="relative z-10 grid grid-cols-1 items-center gap-12 lg:grid-cols-2">
                        <div class="space-y-6">
                            <h2 class="text-4xl font-bold leading-tight text-[#0b1c30]">Monitor Status Lamaran dalam Satu Dasbor</h2>
                            <p class="leading-7 text-[#434655]">
                                Tidak perlu lagi membuka banyak email. Pantau setiap tahapan seleksi magang Anda secara
                                real-time, dari seleksi berkas hingga offering.
                            </p>

                            <ul class="mt-6 space-y-4">
                                <li class="flex items-start gap-3">
                                    <span class="material-symbols-outlined mt-1 text-[#004ac6]">check_circle</span>
                                    <div>
                                        <h4 class="text-lg font-semibold text-[#0b1c30]">Notifikasi Real-time</h4>
                                        <p class="text-sm text-[#434655]">Update langsung dari rekruter.</p>
                                    </div>
                                </li>
                                <li class="flex items-start gap-3">
                                    <span class="material-symbols-outlined mt-1 text-[#004ac6]">timeline</span>
                                    <div>
                                        <h4 class="text-lg font-semibold text-[#0b1c30]">Timeline Transparan</h4>
                                        <p class="text-sm text-[#434655]">Ketahui estimasi waktu setiap tahapan.</p>
                                    </div>
                                </li>
                            </ul>
                        </div>

                        <div class="rounded-xl border border-[#c3c6d7] bg-white p-6 shadow-lg transition-transform duration-300 hover:rotate-0 lg:rotate-1">
                            <div class="mb-6 flex items-center justify-between border-b border-[#c3c6d7]/50 pb-4">
                                <h3 class="text-xl font-semibold text-[#0b1c30]">Lamaran Aktif</h3>
                                <Link :href="route('login')" class="text-xs font-semibold text-[#004ac6]">LIHAT SEMUA</Link>
                            </div>

                            <div class="space-y-4">
                                <div class="flex flex-col gap-4 rounded-lg border border-[#c3c6d7]/30 bg-[#f8f9ff] p-4 sm:flex-row sm:items-center sm:justify-between">
                                    <div class="flex items-center gap-4">
                                        <div class="flex h-10 w-10 items-center justify-center rounded bg-[#004ac6]/10 font-bold text-[#004ac6]">T</div>
                                        <div>
                                            <p class="font-semibold text-[#0b1c30]">UI/UX Designer Intern</p>
                                            <p class="text-xs text-[#434655]">TechCorp Indonesia</p>
                                        </div>
                                    </div>
                                    <div class="w-fit rounded-full bg-[#006c49]/10 px-3 py-1 text-[10px] font-semibold text-[#006c49]">
                                        WAWANCARA
                                    </div>
                                </div>

                                <div class="flex flex-col gap-4 rounded-lg border border-[#c3c6d7]/30 bg-[#f8f9ff] p-4 sm:flex-row sm:items-center sm:justify-between">
                                    <div class="flex items-center gap-4">
                                        <div class="flex h-10 w-10 items-center justify-center rounded bg-[#4d556b]/10 font-bold text-[#4d556b]">F</div>
                                        <div>
                                            <p class="font-semibold text-[#0b1c30]">Data Analyst Intern</p>
                                            <p class="text-xs text-[#434655]">FinData Solutions</p>
                                        </div>
                                    </div>
                                    <div class="w-fit rounded-full bg-[#d3e4fe] px-3 py-1 text-[10px] font-semibold text-[#434655]">
                                        SELEKSI BERKAS
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </section>
        </main>

        <footer class="mt-auto w-full border-t border-slate-200 bg-slate-50 py-12">
            <div class="mx-auto grid max-w-7xl grid-cols-1 gap-8 px-5 md:grid-cols-4 md:px-8">
                <div class="space-y-4">
                    <div class="text-xl font-bold text-slate-900">SIKARA</div>
                    <p class="text-sm font-medium leading-relaxed text-slate-500">
                        © 2026 SIKARA. Structured Ascent for Student Success.
                    </p>
                </div>
            </div>
        </footer>
    </div>
</template>

<style scoped>
.material-symbols-outlined {
    font-variation-settings:
        'FILL' 0,
        'wght' 400,
        'GRAD' 0,
        'opsz' 24;
}
</style>
