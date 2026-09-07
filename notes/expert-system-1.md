# Note pertemuan 1 ([Expert System](https://en.wikipedia.org/wiki/Expert_system))

## Definisi
**Definisi [Expert System](https://en.wikipedia.org/wiki/Expert_system)**: **Sistem komputer yang [berbasis pengetahuan](https://en.wikipedia.org/wiki/Knowledge-based_systems) yang menggunakan [penalaran](https://www.ibm.com/think/topics/ai-reasoning) untuk menyelesaikan masalah yang kompleks pada [domain spesifik](https://www.teach.cs.toronto.edu/~csc110y/fall/notes/11-simulation/01-problem-domain.html).**

## Manusia vs Expert System
|Kriteria|[Pakar Manusia](https://en.wikipedia.org/wiki/Expert)|[Expert System](https://en.wikipedia.org/wiki/Expert_system)|
|--|--|--|
|Durabilitas|*Bisa Meninggal, etc.*|**Permanen**|
|Transferabilitas|*Sulit (Membutuhkan Pelatihan Bertahun tahun)*|**Sangat Mudah (Tinggal kasih data)**|
|Konsistensi|*Berfluktasi*|**100% Konsisten**|
|Biaya & Ketersediaan|*Sangat Mahal dan Langka*|**Relatif Murah (setelah pengembangan awal selesai)**|
|Input Data|Menggunakan [Panca Indra](https://en.wikipedia.org/wiki/Sense)|Bersifat [Simbolik](https://en.wikipedia.org/wiki/Symbolic_artificial_intelligence)|
|Daya Inovasi|**Sangat Kreatif dan Adaptif**|*Kaku & Statis (Bergantung pada pengetahuan)*|

**[Expert System](https://en.wikipedia.org/wiki/Expert_system) itu bersinggungan dengan 5 komponen teknologi utama** ([Knowledge-based](https://en.wikipedia.org/wiki/Knowledge-based_systems), [Production Systems](https://en.wikipedia.org/wiki/Production_system_%28computer_science%29), [Knowledge-based DSS](https://scholar.ui.ac.id/en/publications/knowledge-based-systems-in-decision-support-context-a-literature-/), [Intelligent System](https://en.wikipedia.org/wiki/Intelligent_system), [Rule-based](https://en.wikipedia.org/wiki/Rule-based_system))

## [Expert System](https://en.wikipedia.org/wiki/Expert_system) vs [Conventional Programming](https://en.wikipedia.org/wiki/Procedural_programming)
**[Expert system](https://en.wikipedia.org/wiki/Expert_system): memanipulasi [basis pengetahuan](https://en.wikipedia.org/wiki/Knowledge_base)([knowledge based](https://en.wikipedia.org/wiki/Knowledge-based_systems)) menggunakan [heuristic](https://en.wikipedia.org/wiki/Heuristic) dan [inferensi](https://en.wikipedia.org/wiki/Inference).** *Secara sederhana* bersifat sebagai [sistem deduksi](https://en.wikipedia.org/wiki/Deductive_reasoning) (menarik kesimpulan berdasarkan aturan aturan yang ada).

**[Convetional Programming](https://en.wikipedia.org/wiki/Procedural_programming): Memanipulasi [basis data](https://en.wikipedia.org/wiki/Database), bersifat logaritmik dan repetitif** (mengerjakan tugas yang repetitif). *Secara sederhana* conventional programming/appication itu sistem operasi pemrosesan informasi biasa

## Arsitektur Sistem
**[Development Unit](https://en.wikipedia.org/wiki/Knowledge_engineering): Memasukkan keahlian dari pakar dan menyusun aturan-aturan** 

**[Consultant Unit](https://www.techtarget.com/ai/definition/expert-system): [Antarmuka](https://en.wikipedia.org/wiki/User_interface) interaksi pengguna hingga mendapatkan rekomendasi dari sistem**

## 5 Komponen ES
- **[Fasilitas Akuisisi Pengetahuan](https://en.wikipedia.org/wiki/Knowledge_acquisition): Kumpulin ilmu**
- **[Basis Pengetahuan](https://en.wikipedia.org/wiki/Knowledge_base) ([Base Knowledge](https://en.wikipedia.org/wiki/Knowledge_base)): Memori menyimpan fakta & aturan**
- **[Inference Engine](https://en.wikipedia.org/wiki/Inference_engine): Otak (yang memproses aturan-aturan)**
- **[Fasilitas Penjelasan](https://en.wikipedia.org/wiki/Explainable_artificial_intelligence) ([Explanatory facility & Justification](https://en.wikipedia.org/wiki/Explainable_artificial_intelligence)): Memberikan alasan memberi alasan atas jawaban yang dia berikan**
- **[User Interface](https://en.wikipedia.org/wiki/User_interface)**

## Base Knowledge
- **[Shallow Knowledge](https://en.wikipedia.org/wiki/Knowledge_representation_and_reasoning) (Pengetahuan Dangkal):** Dari pengalaman praktisi lapangan berbasis metode [heuristic](https://en.wikipedia.org/wiki/Heuristic)

- **[Deep Knowledge](https://en.wikipedia.org/wiki/Knowledge_representation_and_reasoning):** Dari orang orang yang belajar secara formal dan terstukrtur (buku/peneitian)

## Karakteristik ES
- **Beroperasi di dalam [domain masalah](https://www.teach.cs.toronto.edu/~csc110y/fall/notes/11-simulation/01-problem-domain.html) yang terbatas**
- **Memiliki fasilitas penjelasan dan [penalaran](https://www.ibm.com/think/topics/ai-reasoning)**
- *Dapat menangani data yang ga pasi*
- **Harus memisahkan base knowledge dari inference engine**
- **Memberikan jawaban yang valid dengan cepat**
