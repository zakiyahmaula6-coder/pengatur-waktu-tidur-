# pengatur-waktu-tidur-
Aplikasi web sederhana untuk mengatur jadwal tidur dan aktivitas harian agar pola istirahat lebih teratur.
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <title>Pengatur Waktu Tidur</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="container">
    <h1>Pengatur Waktu Tidur</h1>
    <p>Atur jadwal tidur agar lebih teratur</p>

    <input type="time" id="sleepTime">
    <button onclick="simpanJadwal()">Simpan Jadwal Tidur</button>

    <h3>Jadwal Tidur Kamu:</h3>
    <p id="jam 8 malam">Belum diatur</p>
  </div>

  <script src="script.js"></script>simpanJadwal()
</body>
</html>
function simpanJadwal() {
  let waktuTidur = document.getElementById("sleepTime").value;

  if (waktuTidur === "") {
    alert("Silakan isi waktu tidur terlebih dahulu!");
  } else {
    document.getElementById("hasil").innerText =
      "Waktu tidur kamu: " + waktuTidur;
  }
}

pengatur-waktu-tidur/
├── index.html
├── style.css
├── script.js
└── README.md
