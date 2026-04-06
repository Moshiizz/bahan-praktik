<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <title>Challenge NIM Lengkap</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-100 p-6">

  <h1 class="text-2xl font-bold mb-4">Challenge_NIM Lengkap</h1>

  <!-- TABEL -->
  <div class="w-[500px] border border-gray-400">
    <div class="bg-orange-400 text-center font-semibold p-2">
      Daftar Buku
    </div>

    <div class="grid grid-cols-3 border-t border-gray-400">
      <!-- Gambar -->
      <div class="border-r border-gray-400 p-2">
        <img src="https://via.placeholder.com/120x160" alt="Buku">
      </div>

      <!-- Label -->
      <div class="border-r border-gray-400">
        <div class="border-b p-2">judul</div>
        <div class="border-b p-2">harga</div>
        <div class="p-2">pengarang</div>
      </div>

      <!-- Isi -->
      <div>
        <div class="border-b p-2">Web Programming</div>
        <div class="border-b p-2">Rp. 245.000,00</div>
        <div class="p-2">John Dean</div>
      </div>
    </div>
  </div>

  <!-- FORM -->
  <div class="mt-8 w-[500px]">
    <h2 class="font-semibold mb-2">Isilah formulir dibawah ini</h2>

    <form class="space-y-3">

      <div class="flex items-center">
        <label class="w-32">Nama:</label>
        <input type="text" placeholder="Nama Kamu"
          class="border px-2 py-1 w-full">
      </div>

      <div class="flex items-center">
        <label class="w-32">Password:</label>
        <input type="password"
          class="border px-2 py-1 w-full">
      </div>

      <div class="flex items-center">
        <label class="w-32">Jenis Kelamin:</label>
        <div class="flex gap-3">
          <label><input type="radio" name="jk"> Laki - Laki</label>
          <label><input type="radio" name="jk"> Perempuan</label>
        </div>
      </div>

      <div class="flex items-center">
        <label class="w-32">Hobi:</label>
        <div class="flex gap-3">
          <label><input type="checkbox"> Membaca Buku</label>
          <label><input type="checkbox"> Menulis</label>
          <label><input type="checkbox"> Memancing</label>
        </div>
      </div>

      <div class="flex items-center">
        <label class="w-32">Asal Kota:</label>
        <select class="border px-2 py-1 w-full">
          <option>Semarang</option>
          <option>Jakarta</option>
          <option>Bandung</option>
        </select>
      </div>

      <div class="flex">
        <label class="w-32">Komentar Anda:</label>
        <textarea rows="4"
          class="border px-2 py-1 w-full">Silahkan katakan isi hati anda</textarea>
      </div>

      <button type="submit"
        class="bg-gray-300 px-4 py-2 border border-gray-500 hover:bg-gray-400">
        Mulai Proses!
      </button>

    </form>
  </div>

</body>
</html># bahan-praktik
