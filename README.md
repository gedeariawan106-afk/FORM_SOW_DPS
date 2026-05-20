<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Form Order Kendala Teknisi</title>
    <style>
        /* =========================
   GOOGLE FONT
========================= */
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap');

/* =========================
   BODY
========================= */
body{
    margin:0;
    padding:30px 15px;
    font-family:'Poppins', sans-serif;
    background:
    linear-gradient(135deg,#0f172a,#1e293b,#2563eb);
    min-height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;
}

/* =========================
   FORM CONTAINER
========================= */
.form-container{
    width:100%;
    max-width:700px;
    background:rgba(255,255,255,0.12);
    backdrop-filter:blur(12px);
    -webkit-backdrop-filter:blur(12px);
    border:1px solid rgba(255,255,255,0.2);
    border-radius:25px;
    padding:35px;
    box-shadow:
    0 8px 32px rgba(0,0,0,0.35);
    animation:fadeIn 0.8s ease;
}

/* =========================
   TITLE
========================= */
.form-container h2{
    text-align:center;
    color:#fff;
    font-size:30px;
    margin-bottom:30px;
    font-weight:700;
    letter-spacing:1px;
}

/* =========================
   FORM GROUP
========================= */
.form-group{
    margin-bottom:22px;
    display:flex;
    flex-direction:column;
}

/* =========================
   LABEL
========================= */
.form-group label{
    color:#ffffff;
    margin-bottom:8px;
    font-size:14px;
    font-weight:600;
    letter-spacing:0.5px;
}

/* =========================
   INPUT, SELECT, TEXTAREA
========================= */
.form-group input,
.form-group select,
.form-group textarea{
    width:100%;
    padding:14px 16px;
    border:none;
    outline:none;
    border-radius:14px;
    font-size:15px;
    background:rgba(255,255,255,0.15);
    color:#fff;
    transition:0.3s ease;
    box-sizing:border-box;
    border:1px solid rgba(255,255,255,0.15);
}

/* OPTION SELECT */
.form-group select option{
    color:#000;
}

/* TEXTAREA */
.form-group textarea{
    min-height:120px;
    resize:vertical;
}

/* PLACEHOLDER */
::placeholder{
    color:rgba(255,255,255,0.7);
}

/* FOCUS EFFECT */
.form-group input:focus,
.form-group select:focus,
.form-group textarea:focus{
    border:1px solid #60a5fa;
    box-shadow:
    0 0 15px rgba(96,165,250,0.5);
    transform:translateY(-2px);
}

/* =========================
   KODE ORDER
========================= */
#kode{
    background:rgba(255,255,255,0.12);
    padding:14px;
    border-radius:12px;
    color:#fff;
    font-weight:600;
    letter-spacing:1px;
    text-align:center;
    border:1px dashed rgba(255,255,255,0.3);
}

/* =========================
   BUTTON SUBMIT
========================= */
.btn-submit{
    width:100%;
    padding:16px;
    border:none;
    border-radius:16px;
    font-size:17px;
    font-weight:700;
    letter-spacing:1px;
    cursor:pointer;
    color:#fff;
    position:relative;
    overflow:hidden;

    background:linear-gradient(
        270deg,
        #2563eb,
        #06b6d4,
        #3b82f6,
        #0ea5e9
    );

    background-size:600% 600%;
    animation:gradientMove 6s ease infinite;

    transition:0.4s ease;

    box-shadow:
    0 10px 25px rgba(37,99,235,0.4);
}

/* HOVER BUTTON */
.btn-submit:hover{
    transform:
    translateY(-4px)
    scale(1.02);

    box-shadow:
    0 15px 35px rgba(37,99,235,0.6);
}

/* CLICK EFFECT */
.btn-submit:active{
    transform:scale(0.98);
}

/* DISABLED */
.btn-submit:disabled{
    opacity:0.7;
    cursor:not-allowed;
}

/* =========================
   SUCCESS MESSAGE
========================= */
.success{
    margin-top:20px;
    text-align:center;
    font-size:15px;
    font-weight:600;
}

/* =========================
   ANIMATION
========================= */
@keyframes gradientMove{
    0%{
        background-position:0% 50%;
    }
    50%{
        background-position:100% 50%;
    }
    100%{
        background-position:0% 50%;
    }
}

@keyframes fadeIn{
    from{
        opacity:0;
        transform:translateY(30px);
    }
    to{
        opacity:1;
        transform:translateY(0);
    }
}

/* =========================
   RESPONSIVE
========================= */
@media(max-width:768px){

    .form-container{
        padding:25px;
        border-radius:20px;
    }

    .form-container h2{
        font-size:24px;
    }

    .btn-submit{
        font-size:15px;
    }
}
    </style>
</head>
<body>

<div class="form-container">
    <h2>Form Order Kendala</h2>
    <form id="orderForm">
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
                        <option>6700-KCP SANUR</option>
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
                        <option value="">Pilih Jenis Kendala</option>
                        <option>E-Service</option>
                        <option>Mesin Sari</option>
                        <option>BDS Web</option>
                        <option>CS digital</option>
                        <option>Printer</option>
                        <option>Server</option>
                        <option>PC Mati</option>
                        <option>Tablet Mati</option>
                        <option>Tablet Error</option>
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
            let nomorAdmin = '6281236472747';

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
