# Summary Design System

#### Design system itu apa ? 
- sebuah standaraisasi yang mengatur setiap elemen desain untuk menguragi redudansi. design system adalah kumpulan prinsip dan praktik bersama membantu menginfromasikan pekerjaan designer,product manager, dan developor, serta sales dan marketing.

#### Kenapa Harus design system?
- pekerjaan berlangsung cepat dan nmungkin bisa jadi seru
- mendapat pemahaman yang lebih baik tentang user base
- setiap anggota memiliki bagian yang dimainkan untuk mentusun produk pengalaman pengguna (user experience)(designer,front-end developer, product manager)

#### Perbedaan stke guide/UI kit, componene library dan design system
- Style guide/UI kit , dokumentiasi yang masih bersifat statis ( menyingkup color , typography, iconography dan masih bayak lagi)
- Component Library , bisa dikunakan dan dibagikan ketim , ini bisa jadi masukan dokumentasi koding dari setiap component
- Design System, dokumentasi kumpulan element, component, dan regions yang sudah ditentukan termasuk guidelinenya designer dan front-end developer

#### Kapan membutuhkan design system ?
- Umur dari perusahaan
- Ukuran Tim
- Beban pekerjaan

#### Tujuan adanya design system
- Brand bisa konsisten
- Menjadi company identity
- Mempunyai nilai yang sama antar pegawai

#### Bagaimana caranya membangun sebuah design system ?
- Atomic methodology
	- Atomic design , merupakan metodology perencanaan yang mengambil inspirasi dari bagaimana sebuah elemen atom membentuk molekul yang lebih kompleks hingga membentuk suatu organisme dan ini analogikan ke setiap antarmuka halaman situs atau aplikasi (Atoms , molecules, organisms , templates , pages)
	- Atom, komponen terkecil atomic design yang berupa tombol,input , label dst. ciri komponen ini adalah tidak bisa dipecah lagi, jika diurai fungsi dan maknanya akan rusak dan berbeda
	- Molekul , jika beberapa atom dikumpulkan mereka akan membetuk sebuah molekul . misalnya menggabukan atom tombol serach dan input search. ketua itu akan membentuk fitur pencarian yang utuh.
	- Organisme , kumpulan molekul. misalnya fitur search bar kamu tempel di header. selain itu ada tombol naviasi dan logo disana, itulah yang membentuk suatu organisme
	- Template, gabungan dari beberapa organisme. ia merupakan "blueprint" dari sebuah halaman web. ia sangat mirip dengan wireframe,ditampilkan berupa elemen dan belum punya data nyata.
	- Pages , merupakan produk akhir dari desain atomis , ia merupakan template yang diisi dengan data nyata

#### Best practice to build a design system
- langkah membangun desain sistem
	- Evaluasi inventasi UI Kamu saat ini dan catat inkonsistensi pada desain yang kamu buat
	- Bangun sebuah pattern library dari berbagai elemen desain yang sama. patter library adalah kumpulan komponen UI yang dapat digunakan kembali kemudian akan memudahkan pekerjaan desain dimasa mendatang.(ada dua jenis pola utama yaitu fungsional dan persepsi).
	- Dokumentasi aturan desain kamu , lalu atur juga bagaimana dan kapan elemen-elemen desain itu dapat diigunakan 
