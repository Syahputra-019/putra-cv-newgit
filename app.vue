<template>
  <div class="flex flex-col min-h-screen bg-gray-100">
    <header class="bg-gray-800 text-white p-6">
      <h1 class="text-4xl font-bold text-center">CV Syahputra Tirta Wijaya</h1>
    </header>
    
    <main class="flex-grow container mx-auto p-6">
      <section class="bg-white shadow-lg rounded-lg p-6 mb-6">
        <h2 class="text-3xl font-semibold text-gray-800">Tentang Saya</h2>
        <p class="mt-2 text-gray-600">
          Mahasiswa Fokasi Universitas Brawijaya Jurusan Teknologi Informasi.
        </p>
      </section>

      <section class="bg-white shadow-lg rounded-lg p-6 mb-6">
        <h2 class="text-3xl font-semibold text-gray-800">Pengalaman Kerja</h2>
        <ul class="list-disc list-inside mt-2 text-gray-600">
          <li>Penanting, di TNI AL</li>
          <li>Karyawan di Toko Bangunan</li>
          <li>Karyawan di Bengkel Motor</li>
        </ul>
      </section>

      <section class="bg-white shadow-lg rounded-lg p-6 mb-6">
        <h2 class="text-3xl font-semibold text-gray-800">Pendidikan</h2>
        <ul class="list-disc list-inside mt-2 text-gray-600">
          <li>SMA N 9 Malang (2019 - 2023)</li>
          <li>Universitas Brawijaya (2023 - Sekarang)</li>
        </ul>
      </section>

      <section class="bg-white shadow-lg rounded-lg p-6 mb-6">
        <h2 class="text-3xl font-semibold text-gray-800">Keahlian</h2>
        <p class="mt-2 text-gray-600">
          Komunikatif, Kerja Sama Tim, Disiplin.
        </p>
      </section>

      <section class="bg-white shadow-lg rounded-lg p-6 mb-6">
        <h2 class="text-3xl font-semibold text-gray-800">Media Sosial</h2>
        <p class="mt-2 text-gray-600">
          Instagram: <a href="https://instagram.com/syhptraaaaaaaaa" class="text-blue-500 hover:underline">syhptraaaaaaaaa</a>
        </p>
      </section>
    </main>

    <footer class="bg-gray-800 text-white text-center p-4">
      <p>&copy; 2024 Syahputra Tirta Wijaya. Semua hak dilindungi.</p>
    </footer>
  </div>
</template>

<script>
export default {
  head() {
    return {
      title: 'CV Syahputra Tirta Wijaya',
    }
  }
}
</script>

<style>
/* Tambahkan CSS kustom jika diperlukan */
</style>
