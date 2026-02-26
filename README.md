# ppwl3

2. Praktikum 2
<!-- Code perbandingan untuk melihat perbedaan -->

<!-- <div class="p-4 space-y-4">
  <h1 class="text-xl font-bold">Perbedaan Tailwind v3 vs v4</h1>

  <!-- Class standar (ada di v3 & v4) -->
  <div class="p-4 bg-blue-300 text-white">Box with p-4 (v3 & v4)</div>

  <!-- Class baru di v4 -->
  <div class="mb-11.5 p-2 bg-green-300 text-white">Box with mb-11.5 (v4 only)</div>

  <!-- Dark mode variant baru -->
  <div class="p-2 bg-gray-400 dark:bg-gray-800 text-white">
    Dark mode variant (v4 only)
  </div>

  <!-- Variant baru not-dark -->
  <div class="not-dark:hidden p-2 bg-purple-300 text-white">
    not-dark:hidden (v4 only)
  </div>
</div> -->

perbedaan tailwind v3 vs v4
ver 3: 
    a. box green mb-11.5 tidak berjalan karena versi ini tidak tau apa itu nilai 11.5 sehingga dianggap default(0) akibatnya jarak box green with mb-11.5 sama rata spacingnya dengan box gray dark mode variant

    b. box not-dark:hidden tidak berjalan di kode tersebut sehingga saat customize mode dark dan light, box ungu not-dark:hidden tersebut tetap muncul

ver 4:
    a. box green mb-11.5 membaca kode tersebut dan menjalankannya sehingga nantinya box green with mb-11.5 akan berjarak(spacing) jauh dengan box gray dark mode variant akibat dari margin-bottom 11.5
    
    b.box not-dark:hidden berjalan di kode tersebut sehingga saat customize mode dark box ungu akan muncul dan jika customize mode light box ungu not-dark:hidden tersebut tidak akan muncul
    

4. Praktikum 4
Komponen box model yang terpengaruh warna latar pada bg-blue-600 adalah?
= content(isi) dan padding sehingga nanti latar belakangnya berwarna biru. 

7.Praktikum 7
link google drive: https://drive.google.com/file/d/1deRlAF3KzaO2GD2ih7Le3pTvM_X0rpxa/view?usp=sharing