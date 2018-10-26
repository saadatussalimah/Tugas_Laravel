# Tugas DieDump

Fungsi dd()
Fungsi ini digunakan untuk debug data ke halaman web, fungsi dipanggil melalui controller. Fungsi dd() akan menghentikan kode program pada file view, digunakan untuk melihat melihat isi dari variabel.

Contohnya sebagai berikut:

`public function index() {
    $data = [
        'hari'=>'Senin',
              'Selasa',
              'Rabu',
              'Kamis',
              'Jumat',
              'Sabtu',
              'Minggu'
    ];
    dd($data);
    return View::make('welcome');
 }`

Fungsi dd() hanya digunakan pada Framework Laravel. Jika menggunakan PHP Sktruktural maupun framework PHP yang lain, dd() tidak dapat digunakan.
