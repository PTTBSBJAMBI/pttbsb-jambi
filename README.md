
<html lang="id" class="scroll-smooth">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>PT TBSB | Pegadaian & Properti Jambi</title>

<script src="https://cdn.tailwindcss.com"></script>
<link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" rel="stylesheet">
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,700;1,900&family=Plus+Jakarta+Sans:wght@300;400;600;800&display=swap" rel="stylesheet">

<style>
:root{--gold:#D4AF37;--dark:#050505}
body{font-family:'Plus Jakarta Sans',sans-serif;background:var(--dark);color:white}
.serif{font-family:'Playfair Display',serif}
.gold-gradient{background:linear-gradient(135deg,#BF953F,#FCF6BA,#B38728);-webkit-background-clip:text;-webkit-text-fill-color:transparent}
.nav-blur{background:rgba(5,5,5,.85);backdrop-filter:blur(12px)}
.premium-border{border:1px solid rgba(212,175,55,.15);transition:.4s}
.premium-border:hover{border-color:#D4AF37;background:rgba(212,175,55,.05);transform:translateY(-6px)}
.reveal{opacity:0;transform:translateY(30px);transition:.8s}
.reveal.active{opacity:1;transform:none}
input{background:#0f0f0f;border:1px solid #333;padding:12px;border-radius:10px;width:100%}
</style>
</head>

<body>

<!-- TOP BAR -->
<div class="bg-[#D4AF37] text-black py-1 text-[9px] font-black uppercase tracking-[0.3em] text-center sticky top-0 z-50">
PT TUJUH BERSAUDARA SUKSES BERSAMA — JAMBI
</div>

<!-- NAVBAR -->
<nav class="fixed top-6 left-0 right-0 z-40 px-6">
<div class="max-w-6xl mx-auto nav-blur border border-white/10 rounded-2xl px-8 py-4 flex justify-between items-center">
<span class="serif italic text-xl font-black gold-gradient">PT TBSB</span>
<div class="hidden md:flex gap-8 text-[10px] uppercase tracking-widest font-bold">
<a href="#tentang">Tentang</a>
<a href="#layanan">Layanan</a>
<a href="#simulasi">Simulasi</a>
<a href="#proses">Proses</a>
<a href="#admin" class="text-[#D4AF37]">Kontak</a>
</div>
</div>
</nav>

<!-- HERO -->
<section class="min-h-screen flex items-center px-6">
<div class="max-w-6xl mx-auto pt-32 reveal">
<h1 class="text-6xl lg:text-8xl font-black serif italic leading-[0.9] mb-8">
Solusi Pegadaian<br>
<span class="gold-gradient">Cepat • Aman • Legal</span>
</h1>
<p class="text-gray-400 max-w-2xl mb-10 leading-relaxed">
Website resmi PT Tujuh Bersaudara Sukses Bersama untuk layanan pegadaian
dan pembiayaan berbasis jaminan aset & properti di Kota Jambi.
</p>
<a href="#admin" class="px-10 py-5 bg-[#D4AF37] text-black font-black rounded-xl uppercase text-xs">
Konsultasi Gratis
</a>
</div>
</section>

<!-- TENTANG -->
<section id="tentang" class="py-28 px-6 bg-white/[0.02]">
<div class="max-w-4xl mx-auto reveal">
<h2 class="text-4xl font-black serif italic gold-gradient mb-8">
Tentang Perusahaan
</h2>
<p class="text-gray-400 text-sm leading-relaxed mb-4">
PT Tujuh Bersaudara Sukses Bersama (PT TBSB) merupakan perusahaan yang bergerak
di bidang jasa pegadaian dan pembiayaan berbasis jaminan aset.
</p>
<p class="text-gray-400 text-sm leading-relaxed mb-4">
Perusahaan ini hadir untuk memberikan solusi pendanaan yang cepat, aman,
dan transparan bagi masyarakat Kota Jambi dan sekitarnya dengan tetap
mengutamakan perlindungan terhadap aset nasabah.
</p>
<p class="text-gray-400 text-sm leading-relaxed">
Jenis jaminan meliputi kendaraan bermotor, emas, barang elektronik,
serta properti berupa rumah dan tanah bersertifikat.
</p>
</div>
</section>

<!-- LAYANAN -->
<section id="layanan" class="py-28 px-6">
<div class="max-w-6xl mx-auto reveal">
<h2 class="text-center text-4xl font-black serif italic gold-gradient mb-16">
Layanan & Jaminan
</h2>

<div class="grid md:grid-cols-2 lg:grid-cols-4 gap-8 text-center">
<div class="premium-border p-8 rounded-3xl">
<i class="fas fa-car text-4xl text-[#D4AF37] mb-4"></i>
<h4 class="font-black uppercase text-sm">Kendaraan</h4>
<p class="text-gray-400 text-xs mt-2">Mobil & motor (BPKB / STNK)</p>
</div>

<div class="premium-border p-8 rounded-3xl">
<i class="fas fa-ring text-4xl text-[#D4AF37] mb-4"></i>
<h4 class="font-black uppercase text-sm">Emas</h4>
<p class="text-gray-400 text-xs mt-2">Logam mulia & perhiasan</p>
</div>

<div class="premium-border p-8 rounded-3xl">
<i class="fas fa-laptop text-4xl text-[#D4AF37] mb-4"></i>
<h4 class="font-black uppercase text-sm">Elektronik</h4>
<p class="text-gray-400 text-xs mt-2">Laptop, HP, kamera</p>
</div>

<div class="premium-border p-8 rounded-3xl">
<i class="fas fa-home text-4xl text-[#D4AF37] mb-4"></i>
<h4 class="font-black uppercase text-sm">Properti</h4>
<p class="text-gray-400 text-xs mt-2">Rumah & tanah bersertifikat</p>
</div>
</div>
</div>
</section>

<!-- SIMULASI -->
<section id="simulasi" class="py-28 px-6 bg-white/[0.02]">
<div class="max-w-xl mx-auto reveal">
<h2 class="text-center text-4xl font-black serif italic gold-gradient mb-10">
Simulasi Pegadaian
</h2>

<input id="jaminan" type="number" placeholder="Nilai Jaminan (Rp)">
<input id="tenor" type="number" placeholder="Tenor (bulan)" class="mt-4">

<button onclick="hitung()" class="mt-6 w-full py-4 bg-[#D4AF37] text-black font-black rounded-xl">
Hitung Simulasi
</button>

<p id="hasil" class="mt-6 text-center text-sm text-gray-300"></p>
</div>
</section>

<!-- PROSES -->
<section id="proses" class="py-28 px-6">
<div class="max-w-6xl mx-auto reveal">
<h2 class="text-center text-4xl font-black serif italic gold-gradient mb-16">
Alur Proses Pegadaian
</h2>

<div class="grid md:grid-cols-4 gap-6 text-center">
<div class="premium-border p-6 rounded-2xl">Konsultasi</div>
<div class="premium-border p-6 rounded-2xl">Penilaian</div>
<div class="premium-border p-6 rounded-2xl">Kesepakatan</div>
<div class="premium-border p-6 rounded-2xl">Pencairan</div>
</div>
</div>
</section>

<!-- ALAMAT -->
<section class="py-28 px-6 bg-white/[0.02]">
<div class="max-w-2xl mx-auto reveal text-center">
<h2 class="text-4xl font-black serif italic gold-gradient mb-6">
Alamat Kantor
</h2>
<p class="text-gray-400 text-sm">
Jeramba Bolong, Kota Jambi<br>Provinsi Jambi, Indonesia
</p>
</div>
</section>

<!-- KONTAK (SEMUA NOMOR TETAP ADA) -->
<section id="admin" class="py-28 px-6">
<div class="max-w-6xl mx-auto reveal">
<h2 class="text-center text-4xl font-black serif italic gold-gradient mb-16">
Konsultan WhatsApp Resmi
</h2>

<div class="grid md:grid-cols-2 lg:grid-cols-4 gap-6 text-center">
<div class="premium-border p-8 rounded-3xl">
<h4 class="font-black">Senior Advisor</h4>
<p class="text-[#D4AF37] font-black">0852-1227-7775</p>
<a href="https://wa.me/6285212277775" class="block mt-4 py-2 bg-[#D4AF37] text-black rounded-xl">Hubungi</a>
</div>

<div class="premium-border p-8 rounded-3xl">
<h4 class="font-black">Advisor Team 1</h4>
<p class="text-[#D4AF37] font-black">0878-3803-4487</p>
<a href="https://wa.me/6287838034487" class="block mt-4 py-2 border border-[#D4AF37] rounded-xl text-[#D4AF37]">Chat</a>
</div>

<div class="premium-border p-8 rounded-3xl">
<h4 class="font-black">Advisor Team 2</h4>
<p class="text-[#D4AF37] font-black">0895-3264-85982</p>
<a href="https://wa.me/62895326485982" class="block mt-4 py-2 border border-[#D4AF37] rounded-xl text-[#D4AF37]">Chat</a>
</div>

<div class="premium-border p-8 rounded-3xl">
<h4 class="font-black">Support Team</h4>
<p class="text-[#D4AF37] font-black">0831-9272-7388</p>
<a href="https://wa.me/6283192727388" class="block mt-4 py-2 border border-white/20 rounded-xl">Chat</a>
</div>
</div>
</div>
</section>

<footer class="py-16 text-center text-xs text-gray-600">
© 2026 PT Tujuh Bersaudara Sukses Bersama — Pegadaian & Properti Jambi
</footer>

<script>
function hitung(){
let j=+jaminan.value,t=+tenor.value;
let pin=j*0.7,tot=pin+(pin*0.02*t);
hasil.innerText="Estimasi Pinjaman: Rp "+pin.toLocaleString()+" | Total Pengembalian: Rp "+tot.toLocaleString();
}
function reveal(){
document.querySelectorAll(".reveal").forEach(e=>{
if(e.getBoundingClientRect().top<innerHeight-100)e.classList.add("active");
});
}
addEventListener("scroll",reveal);reveal();
</script>

</body>
</html>
