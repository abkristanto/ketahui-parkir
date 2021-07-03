<template>
    <div class="body">
        <section id="title">
            <div class="container-fluid">
                <HomeCard />
            </div>
        </section>
        <section id="faq">
            <h1 class="text-center">Frequently Asked Questions</h1>
            <hr>
            <ol class="faq-counter">
                <QuestionBox question="Apa yang dimaksud dengan KetahUIparkir?"
                answer="KetahUIparkir merupakan aplikasi mobile berbasis Android yang 
                        bertujuan untuk membantu baik Warga Universitas Indonesia (UI) maupun
                        non-Warga UI untuk mencari tempat parkir di wilayah UI Depok.
                        Dengan kata lain, kamu bisa menggunakan aplikasi ini untuk membantumu 
                        menemukan tempat parkir yang terdekat dengan tujuanmu selama di UI." />
                <QuestionBox question="Apakah perangkat Android saya memadai untuk menggunakan KetahUIparkir?"
                answer="KetahUIparkir dapat digunakan pada perangkat Android Lollipop (versi 5)
                        ke atas. Untuk kamu yang memiliki perangkat dengan versi di bawahnya,
                        mohon maaf, KetahUIparkir tidak dapat kamu gunakan. Kamu bisa memeriksa
                        versi Android yang kamu gunakan melalui pengaturan perangkat kamu,
                        lalu memilih &quot;About Phone&quot;."/>
                <QuestionBox question="Apakah pengguna iOS dapat menggunakan KetahUIparkir?"
                answer="Mohon maaf, untuk saat ini, hanya pengguna Android yang dapat menggunakan
                        KetahUIparkir. Untuk ke depannya, kami dapat mempertimbangkan untuk
                        menambah dukungan terhadap perangkat iOS. Karena itu, bagi kamu
                        pengguna iOS, harus sedikit bersabar yah..."/>
                <QuestionBox question="Apakah saya harus mendaftar untuk dapat menggunakan KetahUIparkir?"
                answer="Tidak. Kamu tidak perlu mendaftar untuk langsung menggunakan KetahUIparkir,
                        jika hanya ingin mendapatkan rekomendasi tempat parkir. Pendaftaran hanya
                        diperlukan jika kamu ingin menyimpan riwayat rekomendasi yang kamu pilih..."/>
                <QuestionBox question="Apakah KetahUIparkir dapat saya gunakan untuk seluruh
                tempat parkir di UI?"
                answer="Sampai saat ini, KetahUIparkir masih dalam proses pengembangan,
                        sehingga belum dapat digunakan untuk mencari tempat parkir di seluruh UI.
                        Namun, setelah rilis, KetahUIparkir nantinya dapat digunakan di seluruh UI,
                        so, selalu pantau informasinya ya!"/>
                <QuestionBox question="Berapa banyak rekomendasi tempat parkir yang bisa saya dapatkan?"
                answer="Hingga 3 lokasi tempat parkir dapat ditawarkan kepada kamu, tergantung dari
                        jarak lokasi tujuan yang kamu pilih dan ketersediaan setiap tempat parkir."/>
                <QuestionBox question="Saya sudah mendapat tempat parkir yang sesuai.
                Apakah saya bisa memesan sebuah slot parkir di tempat tersebut melalui KetahUIparkir?"
                answer="Tidak. KetahUIparkir tidak ditujukan untuk melakukan pemesanan slot seperti itu.
                        KetahUIparkir tidak menjamin ketersediaan tempat parkir di semua lokasi.
                        Silahkan datang ke lokasi parkir dimaksud dan parkir seperti biasa
                        untuk &quot;mengamankan&quot; slot tersebut."/>
                <QuestionBox question="Apakah saya dapat membayar slot parkir yang saya dapatkan
                melalui KetahUIparkir?"
                answer="Sampai saat ini, hal tersebut tidak memungkinkan. Silahkan membayar langsung
                        kepada pengelola parkir yang mengelola slot tersebut, sesuai kebijakan yang berlaku."/>
                <QuestionBox question="Saya melupakan kata sandi KetahUIparkir saya, sehingga saya
                kehilangan akses ke akun saya, juga fitur riwayat. Apa yang harus saya lakukan?"
                answer="Kamu dapat mengirimkan permintaan pengaturan ulang kata sandi melalui Aplikasi,
                        melalui tombol &quot;Forgot Password&quot; pada halaman login. Kamu kemudian akan
                        menerima sebuah email pada alamat yang dicantumkan saat pendaftaran, lalu ikuti
                        prosedur yang tertera. Setelah proses selesai, kamu dapat melanjutkan login
                        menggunakan kata sandi baru."/>
                <QuestionBox question="Kelihatannya, saya punya ide bagus yang dapat membantu
                pengembangan KetahUIparkir. Melalui apa saya dapat menyampaikannya?"
                answer="Kami sangat terbuka terhadap ide kamu, sekaligus berterima kasih
                        atas kesediaan kamu dalam memberi masukan terhadap KetahUIparkir.
                        Silahkan kirimkan pesan kamu melalui formulir yang terdapat di
                        halaman Contact Us, atau dapat langsung menghubungi salah satu dari kami
                        melalui kontak yang telah disediakan di halaman yang sama.
                        Pesanmu kami tunggu ya!"/>
            </ol>
        </section>

        <Footer />
    </div>
</template>

<script>
export default {
    head: {
        title: "FAQ - KetahUIparkir"
    }
}
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,500;0,600;1,400;1,500;1,900&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Nunito:wght@400;600;700&display=swap");

.body {
  scroll-behavior: smooth;
}

#title {
    background-color: #FFF;
}

#faq {
    padding: 3% 15%;
    background-color: #FCECDD;
}

.container-fluid {
    padding: 3% 15%;
}

h1 {
    font-family: "Playfair Display", sans-serif;
    font-weight: 900;
    font-size: 3.5rem;
    font-style: italic;
    line-height: 1.5;
}

h2 {
    font-family: "Nunito", sans-serif;
    font-size: 3rem;
    line-height: 1.5;
}

h3 {
    font-family: "Nunito", sans-serif;
    font-size: 1.5rem;
}

p {
    color: #8f8f8f;
}

.text-center {
    text-align: center;
}

/* Navigation Bar */

.navbar {
    padding: 0 0 3.5rem;
}

.navbar-brand {
    font-family: "Nunito";
    font-size: 2rem;
    color: #000 !important;
}

.nav-link {
    font-size:1.25rem;
    color: #000 !important;
}

</style>