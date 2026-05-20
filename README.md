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

table div{
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
    padding:18px;
    border-radius:24px;
    color:#2563eb;
    font-weight:bold;
    text-align:center;
    width:100%;
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

    table div{
        display:flex;
        flex-direction:column;
    }

    table div{
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
            <div class="form-group">
                <label for="nama">NAMA</label>
                <input type="text" id="nama" required placeholder="Nama Lengkap">
            </div>
            <div class="form-group">
                <label for="nip">NIP</label>
                <input type="text" id="nip" required placeholder="Nomor Induk Pegawai">
            </div>
           <div class="form-group">
                <label for="kode_cabang">KODE CABANG</label>
                    <select id="kode_cabang" required>
                        <option value="">Pilih Cabang</option>
                        <option>0040-KCU DENPASAR</option>
                        <option>0146-KCU KUTA</option>
                        <option>6115-KCP GATOT SUBROTO BARAT</option>
                        <option>7730-KCP GATOT SUBROTO TIMUR</option>
                        <option>6690-KCP GATOT SUBROTO DENPASAR</option>
                        <option>6113-KCP BULUH INDAH</option>
                        <option>0435-KCP COKROAΜΙΝΟΤΟ</option>
                        <option>6485-KCP MAHENDRADATA</option>
                        <option>7445-KCP BENOA</option>
                        <option>7670-KCP SESETAN</option>
                        <option>7680-KCP TEUKU UMAR</option>
                        <option>0049-KCP MALUKU</option>
                        <option>6110-KCP GRAND SUDIRMAN</option>
                        <option>7725-KCP RENON</option>
                        <option>0135-KCP UBUD</option>
                        <option>0416-KCP GIANYAR</option>
                        <option>0395-KCP KLUNGKUNG</option>
                        <optio>6700-KCP SANUR</option>
                        <option>7720-KCP BYPASS MUMBUL</option>
                        <option>7723-KCP PECATU</option>
                        <option>7705-KCP SUNSET BOULEVARD</option>
                        <option>8580-KCP BYPASS NGURAH RAI</option>
                        <option>0404-KCP KARTIKA PLAZA</option>
                        <option>6955-KCP PASAR KUTA</option>
                        <option>6130-KCP RAYA KUTA</option>
                        <option>7700-KCP KEROBOKAN</option>
                        <option>7703-KCP CANGGU</option>
                        <option>0142-KCP TABANAN</option>
                        <option>7728-KCP GAJAH MADA</option>
                        <option>7726-KCP DALUNG</option>
                    </select>
                </div>
                
<div class ="form-group">
                <label for="jenis_kendala">JENIS KENDALA</label>
                <select id="jenis_kendala" required>
                <option value="">Pilih Kendala</option>
                        <option>E-Service</option>
                        <option>Mesin Sari</option>
                        <option>BDS Web</option>
                        <option>CS digital</option>
                        <option>Printer</option>
                        <option>Server</option>
                        <option>PC Mati</option>
                        <option>Tablet Mati</option>
                        <option >Tablet Error</option>
                        <option>Update</option>
                        <option>Payroll</option>
                        <option>Kunjungan</option>
                        <option>Teknis</option>
                        <option>Lainnya…</option>
                    </select>
            </div>
            
<div class="form-group">
                    <label for="deskripsi">DESKRIPSI</label>
                    <textarea id="deskripsi" required placeholder="Jelaskan detail kendala..."></textarea>
                </div>
            <div class="form-group">
                <label for="whatsapp">WHATSAPP</label>
                <input type="tel" id="whatsapp" required placeholder="Contoh: 081234567xxx">
            </div>
<div class="form-group">
                <label for="tanggal">TANGGAL</label>
                <input type="date" id="tanggal" required>
                <label for="jam">JAM</label>
                <input type="time" id="jam" required>
            </div>

<div class="form-group">
                <label for="kode">KODE</label>
                <p id="kode">Memuat...</p>
            </div>
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
      <button type="submit" class="btn-submit" id="submitBtn">KIRIM ORDER</button>
      <div class="success" id="success"></div>
    </form>
</div>

<script>
    // URL Google Apps Script
    const WEB_APP_URL = "https://script.google.com/macros/s/AKfycbxAeWD7u0eNiZugEmpshZStr4OZsetlwTCT7p3SFk2Hm0Wd1ESK1wvkyeqPVVu-5QC3cw/exec";

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
        let jam = document.getElementById("jam").value;
        let kode = document.getElementById("kode").innerText;

        const formData = {
            nama: nama,
            nip: nip,
            kode_cabang: cabang,
            jenis_kendala: kendala,
            deskripsi: deskripsi,
            whatsapp: whatsapp,
            tanggal: tanggal,
            jam: jam,
            kode: kode,
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
            let nomorAdmin = '628';

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
⏰ Jam : ${jam}
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
