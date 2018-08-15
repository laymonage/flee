+++
title = "Mulai"
date = 2018-08-15T09:09:54+07:00
tags = [""]
categories = [""]
comments = true
draft = false
+++

Yeay, akhirnya kelar juga setupnya. <!--more-->

Biasanya gua bikin situs statis pake [Jekyll][jekyll], kalau ini
pakai [Hugo][hugo]. Jadi, kemarin gua sedikit belajar dan baca-baca
tentang Hugo dulu.

Kenapa gua pake Hugo? Soalnya, gua baca di blog orang-orang, katanya
kalo pake Jekyll itu bakal lemot parah untuk nge-build situs yang
udah banyak page-nya. Sedangkan kalo pake Hugo, itu **jauh** lebih cepet.
Nih [hasil benchmarknya][benchmark]. Karena situs ini bakal diisi dengan
konten yang lebih mentah, gua rasa kayaknya nanti bakal banyak pages yang
dibuat... or at least begitu harapan gua sih wkwk. Daripada nanti repot-repot
migrasi dari Jekyll ke Hugo, gua pikir mending langsung aja pake Hugo.

Setupnya ga terlalu sulit, kurang lebih sama kayak Jekyll.
Kalau gua liat-liat lagi, kayaknya Hugo lebih rapi strukturnya.
Tapi, [dari yang gua baca][comparison] sih Hugo ga bisa pake plugin-plugin
gitu, jadi mungkin secara fungsional bakal lebih terbatas. Ga masalah sih,
situs ini kan emang cuma buat tempat coret-coretan, hehe.

Eniwei, sebelum gua build situsnya, gua perlu untuk milih tema yang
bakal dipake di situs ini. Sebenernya, gua pengen tema yang ala-ala
doodle atau handwriting gitu, tapi gua ga nemu di
[theme list][theme list]-nya :(  
Pengen sih bikin tema sendiri, tapi untuk sekarang gua belum ada waktu,
soalnya perlu belajar struktur temanya Hugo dulu. Belum lagi bikin
graphics art-nya..

Jadi, akhirnya gua pilih untuk pake tema yang ada. Gua nyari tema yang
simpel, dan kebetulan nemu tema [Cactus][cactus]. Gua lumayan suka
formatnya yang simpel dan rapi, tapi agak terlalu simpel soalnya ga ada
fitur tags dan archive. Setelah nyari-nyari lagi, ternyata ada tema
[Cactus Plus][cactus plus]. Cactus Plus ini fork dari Cactus, dan ada
fitur-fitur tambahan, termasuk di antaranya ada tags dan archive.
Tanpa pikir panjang, gua langsung pake tema ini deh :D

Tapi dari Cactus Plus pun masih ada beberapa hal yang gua pengen ubah,
jadi gua fork Cactus Plus ke GitHub gua, trus bikin branch baru untuk
nambahin editan gua. Oh ya, pake Hugo enaknya tuh bisa lebih gampang
untuk gonta-ganti tema, soalnya ada folder khusus tema sendiri untuk
situs kita.

Trus, salah satu hal yang paling menarik menurut gua adalah, lu bisa
(dan sebaiknya) naro tema di folder themes sebagai git submodule.
Jadi, misal gua punya folder `flee` yang isinya situs ini (yang
sekaligus berupa repositori git), di dalemnya ada folder `themes`.
Di dalem folder `themes`, ada folder `hugo-theme-cactus-plus`.
Nah, foldernya si Cactus Plus ini ditambahin sebagai git submodule.
Git submodule itu sebenernya kayak repo git di dalem repo git.
Jadi, folder `hugo-theme-cactus-plus` ini berfungsi layaknya repo
git sendiri. Buat lebih jelasnya, coba baca [post ini][git submodule] deh.

Hmm, udah lumayan banyak ya. Enak juga ternyata nulis bebas begini wkwk,
baru sebentar udah produktif. Gua nulis ini di jam kosong gua di kegiatan
PSAF hari pertama. [Kalau kalian pernah baca][kelana], gua ikut kepanitiaan
PMB Fasilkom UI 2018 sebagai mentor. Gua seneng bisa ikut kepanitiaan ini,
soalnya seru dan menarik banget untuk bisa liat kegiatan-kegiatan PMB dari
perspektif yang lain (tahun lalu kan gua maba, wkwk).

Oke lah, mungkin segitu dulu dari gua kali ini. Terima kasih buat kalian
yang nyempetin untuk baca ini. Kalau mau beropini, silakan kasih komentar
di bawah ini ya! Daaah~


[jekyll]: https://jekyllrb.com
[hugo]: https://gohugo.io
[benchmark]: https://forestry.io/blog/hugo-vs-jekyll-benchmark
[comparison]: https://forestry.io/blog/hugo-and-jekyll-compared
[theme list]: https://themes.gohugo.io
[cactus]: https://themes.gohugo.io/cactus
[cactus plus]: https://themes.gohugo.io/hugo-theme-cactus-plus
[git submodule]: https://blog.github.com/2016-02-01-working-with-submodules
[kelana]: https://laymonage.com/kelana
