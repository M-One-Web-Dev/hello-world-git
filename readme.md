1. clone dulu branch ini dengan git clone
2. setelah clone jangan lupa untuk buat branch baru, disini saya pakai checkout

untuk penamaan branch baru saya saranin menggunakan prefix seperti ini

- feat/new-feature ( kalau fitur baru, example feat/login-api, feat/slicing-login )
- fix/bugfix ( kalau branch ini untuk fix bug, example fix/error-login-api, fix/responsive-login )

<p align="center">
  <img src="./img/Screenshot 2025-09-04 at 07.07.37.png" width="650" title="hover text">
</p>

3. Setelah buat branch baru tinggal buat perubahan aja, bisa kerjain fitur baru atau bug fix, tetapi untuk di contoh ini saya hanya akan menambahkan baris baru di kode html-nya.
<p align="center">
  <img src="./img/Screenshot 2025-09-04 at 07.14.07.png" width="650" title="hover text">
</p>

4. Setelah membuat perubahan jangan lupa untuk commit perubahan tersebut

- Add perubahan terlebih dahulu
<p align="center">
  <img src="./img/Screenshot 2025-09-04 at 07.15.02.png" width="650" title="hover text">
</p>

- kemudian commit perubahan tersebut
  untuk commit kalau bisa kasih prefix lagi ya :>

  - "feat: add new line in html file" ( prefix feat: kalau perubahan kamu lebih ke menambahkan fitur )
  - "fix: error login api" ( prefix fix: kalau perubahan kamu lebih ke memperbaiki bug )
  <p align="center">
    <img src="./img/Screenshot 2025-09-04 at 07.15.44.png" width="650" title="hover text">
  </p>

- kemudian setelah setelah commit jangan lupa untuk check dulu commit-nya, disini saya menggunakan git log, dan ternyata commit terakhir saya sudah berhasil, yeee :>
<p align="center">
  <img src="./img/Screenshot 2025-09-04 at 07.16.04.png" width="650" title="hover text">
</p>

- kemudian tinggal push deh branch kamu ke remote repository
<p align="center">
  <img src="./img/Screenshot 2025-09-04 at 07.21.45.png" width="650" title="hover text">
</p>

5. tinggal buat pull request ke branch main, staging atau dev, sesuain aja dengan alur kerja tim
<p align="center">
  <img src="./img/Screenshot 2025-09-04 at 07.24.55.png" width="650" title="hover text">
</p>

sebelah kiri untuk pilih kode kamu nanti digabung di branch mana, dan sebelah kanan branch yang ingin kamu gabung

<p align="center">
  <img src="./img/Screenshot 2025-09-04 at 07.25.03.png" width="650" title="hover text">
</p>

6. buat judul Pull Request
<p align="center">
  <img src="./img/Screenshot 2025-09-04 at 07.25.33.png" width="650" title="hover text">
</p>

7. jangan kabarin senior, atau reviewer kalau udah buat pr, nanti mereke tinggal review
<p align="center">
  <img src="./img/Screenshot 2025-09-04 at 07.26.04.png" width="650" title="hover text">
</p>

<p align="center">
  <img src="./img/Screenshot 2025-09-04 at 07.26.14.png" width="650" title="hover text">
</p>

8. kalau udah approve tinggal kamu merge, tetapi buat jaga jaga , sebelum merge kamu pull dulu dari branch tujuan ya, dan pastikan branch tujuan sudah up to date dengan branch kamu saat ini

9. dan yee, akhirnya kode kita sudah gabung di branch tujuan, tinggal kabarin ke rekan tim kita untuk pull dari branch tujuan ( dev, staging, main, nama branch tujuan tadi )

Happy Coding :>
