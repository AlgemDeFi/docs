# Unstaking nASTR

Untuk mendapatkan kembali ASTR mereka, pemegang nASTR harus mengembalikan token mereka ke Algem menggunakan salah satu dari dua opsi unstaking yang tersedia:

### Unstaking reguler

Opsi unstake reguler menggunakan fungsi yang sama dengan staking dApps dari Astar Network. Setelah pengguna meng-unstake token nASTR-nya, Algem memicu unstaking pada Staking dApps Astar. Setelah periode unstaking berakhir, Algem akan menerima token ASTR dan mendistribusikannya langsung ke dompet pengguna.

### Immediate unstaking

Dalam opsi Immediate unstaking, pengguna dapat memutuskan untuk unstake nASTR-nya dan menerima token ASTR-nya secara langsung tanpa menunggu sepuluh era, seperti dalam kasus unstaking biasa. Sebagai imbalannya, Algem membebankan sedikit biaya untuk layanan tersebut. In[formasi lebih lanjut tentang biaya kami](../pendapatan-protokol.md).

Pilihan ini juga bergantung pada kapasitas unstaking pool. Kumpulan tersebut berisi sejumlah token ASTR. Sistem akan menolak transaksi jika kumpulan kosong atau tidak memiliki cukup token untuk memenuhi permintaan unstaking pengguna.

Pendapatan protokol memasok kumpulan, dan begitu juga unstaking reguler dari pengguna langsung. Artinya, jika pengguna segera meng-unstake token nASTR-nya menggunakan unstaking pool, dia akan menerima token ASTR-nya langsung dari pool. Namun, Algem juga akan memicu opsi unstaking reguler di dApps staking. Setelah sepuluh era, token ASTR dari staking dApp akan ditambahkan dan mengisi pool yang memungkinkan pengguna lain untuk segera unstake.

Pengoperasiannya sama di kedua opsi, hanya waktu dan biaya yang berubah. ASTR yang diterima setelah unstaking bukanlah setoran awal tetapi jumlah nastr yang tidak di-stake.

Yaitu, Jika pengguna telah membeli atau menjual token nASTR sejak setoran pertamanya dan telah menghapus seluruh saldo naASTR miliknya, dia akan menerima lebih banyak atau lebih sedikit token ASTR daripada setoran awalnya.

### Q: What is the unstaking period?

Periode unstaking bervariasi dari 10 ERA hingga 13 ERA (sekitar 10-13 hari).

### T: Mengapa demikian? Dalam periode unstaking dApp Jaringan Astar adalah 10 ER

Staking DApp memiliki batas 4 panggilan/pengguna yang tidak terikat selama 10 hari. Karena kontrak liquid staking kami pada dasarnya adalah pengguna, Algem mengelompokkan semua panggilan yang tidak terikat ke dalam kumpulan dan mengirimkannya ke staking dApp 4 kali/10 hari. Itulah mengapa jika Anda membatalkan staking ASTR di awal siklus ini, periode pembatalan staking Anda akan menjadi 13 ERA.
