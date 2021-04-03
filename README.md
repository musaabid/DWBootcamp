# MusaAbid - DumbWays Bootcamp
=========================
>Ini hasil dari gue ngikutin tes teknis bootcamp batch 5 di DumbWays

Disuruh naruh sini hasil kerjaannya

Jawaban dari soal Technical Test
--------------------
[Gue](https://me.birru.net/ "Propil ane")

## 1. Definisi DevOps, pentingnya DevOps serta gambaran flow DevOps dari Development sampai production

   * Definisi DevOps: alur praktik dan proses yang mempercepat serta mengautomasi berbagai proses pembangunan, testing dan juga pe-release-an sebauh software. Termasuk pula kelangsungan kerja sistem software tersebut dan juga updatenya.
   * Pentingnya DevOps: 
     - Menjadikan alur kerja dan infrastruktur pembangunan software yang mudah dan baik.
     - Memudahkan dalam membangun, mengoptimasi dan me-release software.
     - Memudahkan dalam pengujian code yang ditulis oleh pihak lain serta penganalisaannya.
     - Memastikan system yang aman dan terjaga dari ancaman cyber.
     - Mengidentifikasi permasalahan teknis, pembangunan system updates dan pembenahannya.
     - Menyingkronisasikan simponi kerja antara software developers dengan software engineers agar bekerja sesuai dengan proses yang sesuai dan diperlukan.
     - Menganalisa alur kerja proyek dan menjadi acuan dalam pengambilan keputusan dalam pembangunan software.
   * Gambaran flow DevOps dari Development sampai Production: 
     - Perencanaan
     - Penentuan Bahasa pemrograman yagn dipakai
     - Pembuatan
     - Testing hasil pemrograman prototype
     - Release software
     - Deploying
     - Operate

 *sumber*:
 - https://targetjobs.co.uk/careers-advice/job-descriptions/1043919-devops-engineer-job-description
 - https://www.simplilearn.com/devops-engineer-job-description-article

## 2. Gambarkan Docker & Kubernetes serta penjelasan persamaan dan perbedaanya!

   * Gambaran
     * Docker: system package deployment app yang membundle semua dependensi yang dibutuhkan, misal web server, database, dsb. Deployment cukup package aplikasi ke server. Dengan begitu penggunaan beberapa server tidak perlu menginstall dependensi berulang.
     * Kubernetes: system automation deployment (DevOps mengirim ke KM(Kubernetes Master) lalu KM ke KW(Kubernetes Worker) secara otomatis meski ke ribuan server), scaling dan manajemen berbasis container. Mendukung beberapa Container Manager seperti Docker.
                   Open Sources, perusahaan unicorn Indonesia menggunakannya, Open Source besutan Google berbasis go-lang yang dibangun dari pengalaman Borg dan Omega (sistem internal Google sebelum tahun 2014).
   * Persamaan: system Container.
   * Perbedaan:
     - Kubernetes Berawal dari Virtual Machine yang merubah arsitektur (Monolith menjadi Microservices). Kubernetes dapat melakukan auto-scaling saat jumlah container melunjak.
     - Docker murni dibangun sebagai system Container Manager. Docker membutuhkan kerja manual untuk deployment & managing container.

 *sumber* :
 - https://www.youtube.com/watch?v=DgkOjJf5M6I&t=301s
 - https://www.youtube.com/watch?v=KrcHmVzmFN8
 - https://www.youtube.com/watch?v=ZJ1eniYvoXE

## 3. Rekam sebuah Video cara menjalankan dua aplikasi dengan port yang sama secara berdampingan!

## 4. Mengapa Continous Integration/ Continous Development (CI/ CD) diperlukan DevOps? Berikan gambaran Workflow(diagram kerja) -nya!

 * CI: DevOps akan mengedit code dan tentu tidak hanya satu orang saja, kemudian juga diedit bersama. maka diperlukan adanya CI agar secara berkesinambungan tetap terjaga kualitas kerja software yang dikembangkan.
 * CD: 

## 5. Beri Contoh 5 beserta screenshot Penggunaan Git serta jelaskan perintah yang dijalankan!

![5 Perintah Git](https://raw.githubusercontent.com/musaabid/DWBootcamp/main/images/5-perintah-git.png)

  >  sudo apt-get install git
  * perintah untuk menginstall git di linux
  >  git config --global user.name "musaabid"
  * perintah untuk git agar mengenali user ini sebagai user secara global
  >  git config --global user.email "abidullahmusabirru@gmail.com"
  * perintah untuk git agar mengenali email ini sebagai user email secara global
  >  git init DumbWaysBootcamp
  * meng-init folder di local
  >  git push -u origin main
  * mengupload ke github


## 6. a

## 7. Apa itu Reverse Proxy? Bagaimana cara kerja serta gambarannya?

![Reverse Proxy](https://raw.githubusercontent.com/musaabid/DWBootcamp/main/images/Reverse-proxy.png)

Client tidak mengetahui server mana yang terkoneksi padanya.
Misal: Menggunakan google, google akan memilih server yang longgar untuk menghubungkannya kesana. Google yg memiliki ip address reverse proxy akan menanggapi server ini sebagai pihak yang akan membantu client.

## 8. a 







Penutup
-----
**sumber**:
* instalasi dan sebagainya:
    - https://docs.microsoft.com/en-us/windows/wsl/install-win10
    - https://www.howtoforge.com/tutorial/install-git-and-github-on-ubuntu/#-installing-git-for-linux
    - https://www.petanikode.com/git-install/
    - https://www.petanikode.com/git-vscode/
    - https://www.youtube.com/watch?v=j-WVc9HGCfI
    - https://www.petanikode.com/markdown-pemula/
    - https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one