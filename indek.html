<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Form Order Kendala Teknisi</title>
    <style>
       *{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

body{
    font-family:Arial, sans-serif;
    background:linear-gradient(135deg,#0f172a,#1e3a8a,#2563eb);
    min-height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;
    padding:20px;
}

.form-container{
    width:100%;
    max-width:700px;
    background:rgba(255,255,255,0.12);
    backdrop-filter:blur(12px);
    padding:30px;
    border-radius:20px;
    box-shadow:0 10px 35px rgba(0,0,0,0.3);
    animation:fadeIn 0.8s ease;
}

.form-container h2{
    text-align:center;
    color:#fff;
    margin-bottom:25px;
    font-size:28px;
    letter-spacing:1px;
}

table{
    width:100%;
    border-collapse:collapse;
}

table tr td{
    padding:10px 5px;
    vertical-align:top;
}

label{
    color:#fff;
    font-weight:bold;
    font-size:14px;
}

input,
select,
textarea{
    width:100%;
    padding:12px 14px;
    border:none;
    outline:none;
    border-radius:12px;
    background:rgba(255,255,255,0.95);
    font-size:14px;
    transition:0.3s;
}

textarea{
    min-height:120px;
    resize:vertical;
}

input:focus,
select:focus,
textarea:focus{
    transform:scale(1.02);
    box-shadow:0 0 10px rgba(255,255,255,0.6);
}

#kode{
    background:#fff;
    padding:10px;
    border-radius:10px;
    color:#2563eb;
    font-weight:bold;
    text-align:center;
    width:fit-content;
}

.btn-submit{
    width:100%;
    margin-top:25px;
    padding:15px;
    border:none;
    border-radius:14px;
    background:linear-gradient(135deg,#00c853,#00e676);
    color:#fff;
    font-size:18px;
    font-weight:bold;
    cursor:pointer;
    position:relative;
    overflow:hidden;
    transition:all 0.35s ease;
    box-shadow:0 5px 15px rgba(0,200,83,0.4);
}

/* Hover animasi */
.btn-submit:hover{
    transform:translateY(-3px) scale(1.02);
    box-shadow:0 10px 25px rgba(0,255,120,0.6);
}

/* Efek klik */
.btn-submit:active{
    transform:scale(0.96);
}

/* Efek cahaya berjalan */
.btn-submit::before{
    content:'';
    position:absolute;
    top:0;
    left:-100%;
    width:100%;
    height:100%;
    background:linear-gradient(
        120deg,
        transparent,
        rgba(255,255,255,0.5),
        transparent
    );
    transition:0.6s;
}

.btn-submit:hover::before{
    left:100%;
}

/* Tombol disabled */
.btn-submit:disabled{
    background:#999;
    cursor:not-allowed;
    box-shadow:none;
}

/* Success Message */
.success{
    margin-top:20px;
    text-align:center;
    font-weight:bold;
    color:#fff;
}

/* Animasi form muncul */
@keyframes fadeIn{
    from{
        opacity:0;
        transform:translateY(20px);
    }
    to{
        opacity:1;
        transform:translateY(0);
    }
}

/* Responsive */
@media(max-width:600px){

    .form-container{
        padding:20px;
    }

    table tr{
        display:flex;
        flex-direction:column;
    }

    table tr td{
        width:100%;
    }

    label{
        margin-bottom:5px;
        display:block;
    }

    .btn-submit{
        font-size:16px;
    }
}
    </style>
</head>
<body>

<div class="form-container">
    <h2>Form Order Kendala</h2>
    <form id="orderForm">
        <table>
            <tr>
                <td><label for="nama">NAMA</label></td>
                <td><input type="text" id="nama" required placeholder="Nama Lengkap"></td>
            </tr>
            <tr>
                <td><label for="nip">NIP</label></td>
                <td><input type="text" id="nip" required placeholder="Nomor Induk Pegawai"></td>
            </tr>
            <tr>
                <td><label for="kode_cabang">KODE CABANG</label></td>
                    <td> <select id="kode_cabang" required>
                        <option>D05248-DENPASAR UTARA</option>
                        <option>D05249-DENPASAR TIMUR</option>
                        <option>D05250-DENPASAR SELATAN</option>
                        <option>D05251-DENPASAR BARAT</option>
                        <option>D05252-DENPASAR KOTA</option>
                    <option>D05253-DENPASAR KUTA</option>
                    </select>
                    </td>
            </tr>
            <tr>
                <td><label for="jenis_kendala">JENIS KENDALA</label></td>
                    <td><select id="jenis_kendala" required>
                        <option value="">Pilih Jenis Kendala</option>
                        <option>Kendala Teknis</option>
                        <option>Kendala Administrasi</option>
                        <option>Kendala Logistik</option>
                        <option>Kendala Lainnya</option>
                    </select>
            </tr>
            <tr>
                <td><label for="deskripsi">DESKRIPSI</label></td>
                <td><textarea id="deskripsi" required placeholder="Jelaskan detail kendala..."></textarea></td>
            </tr>
            <tr>
                <td><label for="whatsapp">WHATSAPP</label></td>
                <td><input type="tel" id="whatsapp" required placeholder="Contoh: 081234567xxx"></td>
            </tr>
            <tr>
                <td><label for="tanggal">TANGGAL</label></td>
                <td><input type="date" id="tanggal" required></td>
                <td> <input type="time" id="waktu" required></td>
            </tr>

            <tr>
                <td><label for="kode">KODE</label></td>
                <td><p id="kode">Memuat...</p></td>
            </tr>
        </table>
        <script>
                function generateOrderNumber() {
            // Membuat awalan (misal: SOW-)
            const prefix = "SOW-";
            
            // Membuat angka acak 6 digit (contoh: 100000 - 999999)
            const randomNum = Math.floor(100000 + Math.random() * 900000);
            
            // Menggabungkan prefix dan angka
            const finalOrder = prefix + randomNum;
            
            // Menampilkan di elemen HTML
            document.getElementById("kode").innerText = finalOrder;
        }
        // Jalankan fungsi saat halaman dimuat
        window.onload = generateOrderNumber;
        </script>
        </tr>
      <button type="submit" class="btn-submit" id="submitBtn">KIRIM ORDER</button>
      <div class="success" id="success"></div>
    </form>
</div>

<script>
    // URL Google Apps Script
    const WEB_APP_URL = "https://script.google.com/macros/s/AKfycbxfvEQHu_sL_ZHMtIdzoYnbL7VVXzBJhl2I6gCaV7JRjhHl8IN0NChp3HktVF95B1Nszw/exec";

    // Generate kode order
    function generateOrderNumber() {
        const prefix = "SOW-";
        const randomNum = Math.floor(100000 + Math.random() * 900000);
        const finalOrder = prefix + randomNum;

        document.getElementById("kode").innerText = finalOrder;
    }

    window.onload = generateOrderNumber;

    // Submit Form
    document.getElementById('orderForm').addEventListener('submit', function(e) {
        e.preventDefault();

        const submitBtn = document.getElementById('submitBtn');

        submitBtn.innerText = "Mengirim...";
        submitBtn.disabled = true;

        // Ambil data form
        let nama = document.getElementById("nama").value;
        let nip = document.getElementById("nip").value;
        let cabang = document.getElementById("kode_cabang").value;
        let kendala = document.getElementById("jenis_kendala").value;
        let deskripsi = document.getElementById("deskripsi").value;
        let whatsapp = document.getElementById("whatsapp").value;
        let tanggal = document.getElementById("tanggal").value;
        let kode = document.getElementById("kode").innerText;

        const formData = {
            nama: nama,
            nip: nip,
            kode_cabang: cabang,
            jenis_kendala: kendala,
            deskripsi: deskripsi,
            whatsapp: whatsapp,
            tanggal: tanggal,
            kode: kode
        };

        // Kirim ke Google Apps Script
        fetch(WEB_APP_URL, {
            method: 'POST',
            mode: 'no-cors',
            headers: {
                'Content-Type': 'application/json'
            },
            body: JSON.stringify(formData)
        })
        .then(() => {

            // Nomor admin WA
            let nomorAdmin = '6281246443838';

            // Pesan WhatsApp
            let pesan =
`Hallo Admin,

Saya ingin melaporkan kendala dengan detail berikut:

📌 KODE ORDER : ${kode}

👤 Nama : ${nama}
🆔 NIP : ${nip}
🏢 Cabang : ${cabang}
⚠️ Kendala : ${kendala}

📝 Deskripsi :
${deskripsi}

📱 WhatsApp : ${whatsapp}
📅 Tanggal : ${tanggal}`;

            // Encode pesan
            let encodedMessage = encodeURIComponent(pesan);

            // Link WhatsApp
            let waURL = `https://wa.me/${nomorAdmin}?text=${encodedMessage}`;

            // Buka WhatsApp
            window.open(waURL, '_blank');

            // Success
            document.getElementById('success').innerHTML =
                "<p style='color:green;'>Order berhasil dikirim!</p>";

            // Reset form
            document.getElementById('orderForm').reset();

            // Generate kode baru
            generateOrderNumber();
        })
        .catch(error => {
            console.error(error);
            alert("Gagal mengirim data!");
        })
        .finally(() => {
            submitBtn.innerText = "KIRIM ORDER";
            submitBtn.disabled = false;
        });
    });
</script>
</body>
</html>
