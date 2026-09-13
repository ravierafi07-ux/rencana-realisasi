<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulir Rencana & Realisasi Pengambilan Contoh Uji</title>
    <style>
        * {
            box-sizing: border-box;
            font-family: Arial, Helvetica, sans-serif;
            font-size: 10.5px;
        }

        body {
            background-color: #525659;
            margin: 0;
            padding: 20px 0;
            color: #000;
        }

        /* Panel Kontrol (Tidak Ikut Dicetak) */
        .no-print-panel {
            position: fixed;
            top: 15px;
            right: 15px;
            background: #ffffff;
            border: 1px solid #999;
            padding: 15px;
            border-radius: 8px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.3);
            z-index: 1000;
            width: 280px;
        }

        .no-print-panel h3 {
            margin: 0 0 10px 0;
            font-size: 13px;
            border-bottom: 2px solid #0056b3;
            padding-bottom: 5px;
            color: #0056b3;
        }

        .control-group {
            margin-bottom: 12px;
        }

        .control-group label {
            display: block;
            font-weight: bold;
            margin-bottom: 4px;
        }

        .btn {
            background-color: #0056b3;
            color: white;
            border: none;
            padding: 10px 14px;
            cursor: pointer;
            border-radius: 4px;
            font-weight: bold;
            width: 100%;
            font-size: 12px;
        }

        .btn:hover {
            background-color: #003d80;
        }

        /* Tata Letak Halaman Kertas A4 */
        .paper-page {
            width: 210mm;
            min-height: 297mm;
            padding: 12mm 15mm;
            margin: 0 auto 20px auto;
            background: white;
            box-shadow: 0 0 10px rgba(0,0,0,0.3);
            position: relative;
        }

        /* Header Kop Dokumen */
        .doc-header {
            border: 1.5px solid #000;
            width: 100%;
            border-collapse: collapse;
            margin-bottom: 10px;
        }

        .doc-header td {
            border: 1px solid #000;
            padding: 4px;
            text-align: center;
            vertical-align: middle;
        }

        .doc-header .logo-cell { width: 15%; }
        .doc-header .title-cell { width: 63%; }
        .doc-header .doc-num-cell { width: 22%; font-weight: bold; font-size: 11px; }

        .logo-preview {
            max-width: 55px;
            max-height: 55px;
            object-fit: contain;
        }

        .header-title-text {
            font-weight: bold;
            font-size: 11px;
            margin: 0;
            line-height: 1.2;
        }

        .header-subtitle-text {
            font-weight: bold;
            font-size: 10.5px;
            margin-top: 2px;
        }

        /* Elemen Form Input */
        input[type="text"], textarea {
            width: 100%;
            border: none;
            border-bottom: 1px dotted #555;
            outline: none;
            background: transparent;
            font-family: inherit;
            font-size: inherit;
            padding: 1px 0;
        }

        input[type="text"]:focus, textarea:focus {
            border-bottom: 1px solid #000;
        }

        .checkbox-group {
            display: inline-flex;
            align-items: center;
            margin-right: 10px;
            margin-bottom: 3px;
            white-space: nowrap;
        }

        .checkbox-group input {
            margin-right: 4px;
        }

        /* Layout Tabel & Seksi */
        table.form-table {
            width: 100%;
            border-collapse: collapse;
            margin-bottom: 8px;
        }

        table.form-table, table.form-table th, table.form-table td {
            border: 1px solid #000;
        }

        table.form-table th, table.form-table td {
            padding: 3px 4px;
            vertical-align: top;
        }

        .section-title {
            font-weight: bold;
            margin-top: 8px;
            margin-bottom: 4px;
            display: block;
            text-decoration: underline;
        }

        .sketch-box {
            border: 1px solid #000;
            height: 140px;
            width: 100%;
            display: flex;
            align-items: center;
            justify-content: center;
            background-color: #fafafa;
            position: relative;
        }

        .sketch-box img {
            max-height: 100%;
            max-width: 100%;
            object-fit: contain;
        }

        .flex-container {
            display: flex;
            gap: 12px;
        }

        .flex-col { flex: 1; }

        .footer-sign {
            margin-top: 15px;
            width: 100%;
            border-collapse: collapse;
        }

        .footer-sign td {
            border: 1px solid #000;
            padding: 4px;
            vertical-align: top;
        }

        .page-number {
            position: absolute;
            bottom: 5mm;
            right: 15mm;
            font-size: 9px;
            font-style: italic;
        }

        /* CSS KHUSUS PRINT */
        @media print {
            body {
                background: none;
                padding: 0;
                margin: 0;
            }

            .no-print-panel {
                display: none !important;
            }

            .paper-page {
                box-shadow: none;
                margin: 0;
                padding: 10mm 12mm;
                width: 100%;
                page-break-after: always;
            }

            input[type="text"], textarea {
                border-bottom: none !important;
            }

            .sketch-box {
                background-color: transparent !important;
            }

            @page {
                size: A4 portrait;
                margin: 0;
            }
        }
    </style>
</head>
<body>

    <!-- Panel Kontrol Navigasi & Pengunggah Gambar -->
    <div class="no-print-panel">
        <h3>Menu Edit & Cetak</h3>
        <div class="control-group">
            <label for="input-logo">Unggah Logo Header (Kop):</label>
            <input type="file" id="input-logo" accept="image/*">
        </div>
        <div class="control-group">
            <label for="input-sketch">Unggah Foto Sketsa Lokasi:</label>
            <input type="file" id="input-sketch" accept="image/*">
        </div>
        <hr style="margin: 10px 0;">
        <button class="btn" onclick="window.print()">Cetak / Print Dokumen</button>
    </div>

    <!-- Templat Header Berulang -->
    <template id="header-template">
        <table class="doc-header">
            <tr>
                <td class="logo-cell">
                    <img class="header-logo-img logo-preview" src="data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' width='50' height='50'><rect width='100%' height='100%' fill='%23eee'/><text x='50%' y='50%' dominant-baseline='middle' text-anchor='middle' font-size='9' fill='%23aaa'>Logo</text></svg>" alt="Logo">
                </td>
                <td class="title-cell">
                    <div class="header-title-text" contenteditable="true">UPTD LABORATORIUM LINGKUNGAN</div>
                    <div class="header-title-text" contenteditable="true">DINAS LINGKUNGAN HIDUP KOTA SEMARANG</div>
                    <hr style="border: 0.5px solid #000; margin: 3px 0;">
                    <div class="header-subtitle-text" contenteditable="true">RENCANA DAN REALISASI PENGAMBILAN CONTOH UJI</div>
                </td>
                <td class="doc-num-cell">
                    No. Dok.: F 7.3-2
                </td>
            </tr>
        </table>
    </template>

    <!-- HALAMAN 1: RENCANA PENGAMBILAN CONTOH UJI AIR (BAGIAN 1) -->
    <div class="paper-page" id="page1">
        <div class="header-target"></div>
        
        <div style="text-align: center; font-weight: bold; text-decoration: underline; margin-bottom: 8px;">RENCANA PENGAMBILAN CONTOH UJI AIR</div>

        <span class="section-title">A. Informasi Umum</span>
        <div style="padding-left: 10px;">
            <strong>1. Data Pelanggan</strong>
            <table style="width: 100%; margin-bottom: 5px;">
                <tr><td style="width: 120px;">Nama Pelanggan</td><td style="width: 10px;">:</td><td><input type="text"></td></tr>
                <tr><td>Alamat Pelanggan</td><td>:</td><td><input type="text"></td></tr>
            </table>

            <strong>2. Jadwal Pengambilan Contoh Uji Air</strong>
            <table style="width: 100%; margin-bottom: 8px;">
                <tr>
                    <td style="width: 140px;">Petugas Pengambil Contoh Uji Air</td><td style="width: 10px;">:</td><td><input type="text"></td>
                    <td style="width: 110px; text-align: right;">Tanggal Pengambilan</td><td style="width: 10px;">:</td><td><input type="text"></td>
                </tr>
            </table>
        </div>

        <span class="section-title">B. Informasi Contoh Uji Air</span>
        <div style="padding-left: 10px;">
            <strong>1. Tujuan Pengambilan Contoh Uji Air</strong>
            <div style="margin: 3px 0 8px 0;">
                <label class="checkbox-group"><input type="checkbox"> Pemantauan Rutin / Pengendalian</label>
                <label class="checkbox-group"><input type="checkbox"> Izin Lingkungan</label>
                <label class="checkbox-group"><input type="checkbox"> Pengawasan / Penegakan Hukum</label>
                <label class="checkbox-group"><input type="checkbox"> Penelitian Lingkungan</label>
            </div>

            <strong>2. Ruang Lingkup Pengambilan Contoh Uji Air</strong>
            <table class="form-table" style="margin-top: 4px;">
                <thead>
                    <tr>
                        <th style="width: 5%;">No.</th>
                        <th style="width: 30%;">Jenis Contoh Uji</th>
                        <th style="width: 8%;">Qty</th>
                        <th style="width: 32%;">Titik Pengambilan Contoh Uji</th>
                        <th style="width: 25%;">Baku Mutu Pengujian</th>
                    </tr>
                </thead>
                <tbody>
                    <script>
                        for(let i=1; i<=5; i++) {
                            document.write(`<tr><td style="text-align:center;">${i}</td><td><input type="text"></td><td><input type="text"></td><td><input type="text"></td><td><input type="text"></td></tr>`);
                        }
                    </script>
                </tbody>
            </table>

            <strong>3. Parameter yang Diujikan</strong>
            <table class="form-table" style="margin-top: 4px;">
                <thead>
                    <tr>
                        <th style="width: 8%;">No.</th>
                        <th>Parameter Pengujian</th>
                    </tr>
                </thead>
                <tbody>
                    <script>
                        for(let i=1; i<=5; i++) {
                            document.write(`<tr><td style="text-align:center;">${i}</td><td><input type="text"></td></tr>`);
                        }
                    </script>
                </tbody>
            </table>
        </div>
        <div class="page-number">Ed. 3, Rev. 4</div>
    </div>

    <!-- HALAMAN 2: RENCANA PENGAMBILAN CONTOH UJI AIR (PERALATAN) -->
    <div class="paper-page" id="page2">
        <div class="header-target"></div>

        <span class="section-title">1. Peralatan Pengukuran Contoh Uji Air</span>
        <table class="form-table">
            <thead>
                <tr>
                    <th style="width: 23%;">Jenis Peralatan</th><th style="width: 10%;">Kondisi</th>
                    <th style="width: 23%;">Jenis Peralatan</th><th style="width: 10%;">Kondisi</th>
                    <th style="width: 24%;">Jenis Peralatan</th><th style="width: 10%;">Kondisi</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td><label class="checkbox-group"><input type="checkbox"> pH Meter</label></td><td><label class="checkbox-group"><input type="checkbox"> Baik</label></td>
                    <td><label class="checkbox-group"><input type="checkbox"> TDS Meter</label></td><td><label class="checkbox-group"><input type="checkbox"> Baik</label></td>
                    <td><label class="checkbox-group"><input type="checkbox"> Salinitas Meter</label></td><td><label class="checkbox-group"><input type="checkbox"> Baik</label></td>
                </tr>
                <tr>
                    <td><label class="checkbox-group"><input type="checkbox"> Termometer Raksa</label></td><td><label class="checkbox-group"><input type="checkbox"> Baik</label></td>
                    <td><label class="checkbox-group"><input type="checkbox"> Turbidity Meter</label></td><td><label class="checkbox-group"><input type="checkbox"> Baik</label></td>
                    <td><input type="text"></td><td><label class="checkbox-group"><input type="checkbox"> Baik</label></td>
                </tr>
                <tr>
                    <td><label class="checkbox-group"><input type="checkbox"> DO Meter</label></td><td><label class="checkbox-group"><input type="checkbox"> Baik</label></td>
                    <td><label class="checkbox-group"><input type="checkbox"> Colorimeter</label></td><td><label class="checkbox-group"><input type="checkbox"> Baik</label></td>
                    <td><input type="text"></td><td><label class="checkbox-group"><input type="checkbox"> Baik</label></td>
                </tr>
                <tr>
                    <td><label class="checkbox-group"><input type="checkbox"> Set Titrasi DO</label></td><td><label class="checkbox-group"><input type="checkbox"> Baik</label></td>
                    <td><label class="checkbox-group"><input type="checkbox"> Spectroquant Move DC</label></td><td><label class="checkbox-group"><input type="checkbox"> Baik</label></td>
                    <td><input type="text"></td><td><label class="checkbox-group"><input type="checkbox"> Baik</label></td>
                </tr>
            </tbody>
        </table>

        <span class="section-title">2. Peralatan Pengambilan Contoh Uji Air</span>
        <table class="form-table">
            <thead>
                <tr>
                    <th style="width: 23%;">Jenis Peralatan</th><th style="width: 10%;">Kondisi</th>
                    <th style="width: 23%;">Jenis Peralatan</th><th style="width: 10%;">Kondisi</th>
                    <th style="width: 24%;">Jenis Peralatan</th><th style="width: 10%;">Kondisi</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td><label class="checkbox-group"><input type="checkbox"> Ember Plastik Bening</label></td><td><label class="checkbox-group"><input type="checkbox"> Baik</label></td>
                    <td><label class="checkbox-group"><input type="checkbox"> Water Sampler Horizontal</label></td><td><label class="checkbox-group"><input type="checkbox"> Baik</label></td>
                    <td><label class="checkbox-group"><input type="checkbox"> Botol Komposit Plastik</label></td><td><label class="checkbox-group"><input type="checkbox"> Baik</label></td>
                </tr>
                <tr>
                    <td><label class="checkbox-group"><input type="checkbox"> Ember Stainless Steel</label></td><td><label class="checkbox-group"><input type="checkbox"> Baik</label></td>
                    <td><label class="checkbox-group"><input type="checkbox"> Water Sampler Vertical</label></td><td><label class="checkbox-group"><input type="checkbox"> Baik</label></td>
                    <td><label class="checkbox-group"><input type="checkbox"> Botol Komposit Stainless</label></td><td><label class="checkbox-group"><input type="checkbox"> Baik</label></td>
                </tr>
                <tr>
                    <td><label class="checkbox-group"><input type="checkbox"> Gayung Teleskopik</label></td><td><label class="checkbox-group"><input type="checkbox"> Baik</label></td>
                    <td><label class="checkbox-group"><input type="checkbox"> Current Meter</label></td><td><label class="checkbox-group"><input type="checkbox"> Baik</label></td>
                    <td><input type="text"></td><td><label class="checkbox-group"><input type="checkbox"> Baik</label></td>
                </tr>
                <tr>
                    <td><label class="checkbox-group"><input type="checkbox"> Gelas Ukur Plastik</label></td><td><label class="checkbox-group"><input type="checkbox"> Baik</label></td>
                    <td><label class="checkbox-group"><input type="checkbox"> Meteran</label></td><td><label class="checkbox-group"><input type="checkbox"> Baik</label></td>
                    <td><input type="text"></td><td><label class="checkbox-group"><input type="checkbox"> Baik</label></td>
                </tr>
                <tr>
                    <td><label class="checkbox-group"><input type="checkbox"> Alat GPS</label></td><td><label class="checkbox-group"><input type="checkbox"> Baik</label></td>
                    <td><label class="checkbox-group"><input type="checkbox"> Ice Box & Ice Gel</label></td><td><label class="checkbox-group"><input type="checkbox"> Baik</label></td>
                    <td><input type="text"></td><td><label class="checkbox-group"><input type="checkbox"> Baik</label></td>
                </tr>
                <tr>
                    <td><label class="checkbox-group"><input type="checkbox"> Secchi Disk</label></td><td><label class="checkbox-group"><input type="checkbox"> Baik</label></td>
                    <td><label class="checkbox-group"><input type="checkbox"> Botol Pencuci (Aquadest)</label></td><td><label class="checkbox-group"><input type="checkbox"> Baik</label></td>
                    <td><input type="text"></td><td><label class="checkbox-group"><input type="checkbox"> Baik</label></td>
                </tr>
            </tbody>
        </table>

        <span class="section-title">3. Jenis dan Jumlah Wadah Contoh Uji Air</span>
        <table class="form-table">
            <thead>
                <tr>
                    <th>Jenis Botol</th>
                    <th>Polyethylene (PE)</th>
                    <th>Polyethylene (PE)</th>
                    <th>Amber Glass</th>
                    <th>Amber Glass</th>
                    <th>Botol Winkler</th>
                </tr>
                <tr>
                    <th>Volume</th>
                    <th>500 ml</th>
                    <th>1000 ml</th>
                    <th>250 ml</th>
                    <th>500 ml</th>
                    <th>102 ml</th>
                </tr>
                <tr>
                    <th>Jumlah Botol</th>
                    <td><input type="text" style="text-align:center;"></td>
                    <td><input type="text" style="text-align:center;"></td>
                    <td><input type="text" style="text-align:center;"></td>
                    <td><input type="text" style="text-align:center;"></td>
                    <td><input type="text" style="text-align:center;"></td>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td style="font-weight: bold; text-align: center;">Ruang Lingkup Pengujian</td>
                    <td style="font-size: 9.5px;">
                        • pH<br>• Suhu<br>• COD<br>• Amoniak<br>• Krom Heksavalen<br>• Nitrat<br>• Nitrit<br>• Sulfida<br>• Total Fosfat<br>• Residual Klorin<br>• Klorin Bebas
                    </td>
                    <td style="font-size: 9.5px;">
                        • BOD<br>• TSS<br>• TDS<br>• Warna<br>• Kekeruhan<br>• Kesadahan<br>• Logam (umum)<br>• Sulfat<br>• Klorida<br>• Fluorida
                    </td>
                    <td style="font-size: 9.5px;">
                        • Total Coliform<br>• Fecal Coliform<br>• Escherichia Coli
                    </td>
                    <td style="font-size: 9.5px;">
                        • Minyak dan Lemak
                    </td>
                    <td style="font-size: 9.5px;">
                        • Oksigen Terlarut (Dissolved Oxygen)
                    </td>
                </tr>
            </tbody>
        </table>

        <span class="section-title">4. Peralatan Keselamatan dan Kesehatan Kerja (K3)</span>
        <table class="form-table">
            <thead>
                <tr>
                    <th style="width: 23%;">Jenis Peralatan</th><th style="width: 10%;">Kondisi</th>
                    <th style="width: 23%;">Jenis Peralatan</th><th style="width: 10%;">Kondisi</th>
                    <th style="width: 24%;">Jenis Peralatan</th><th style="width: 10%;">Kondisi</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td><label class="checkbox-group"><input type="checkbox"> Baju Lapangan</label></td><td><label class="checkbox-group"><input type="checkbox"> Baik</label></td>
                    <td><label class="checkbox-group"><input type="checkbox"> Safety Helmet</label></td><td><label class="checkbox-group"><input type="checkbox"> Baik</label></td>
                    <td><label class="checkbox-group"><input type="checkbox"> Tabung APAR</label></td><td><label class="checkbox-group"><input type="checkbox"> Baik</label></td>
                </tr>
                <tr>
                    <td><label class="checkbox-group"><input type="checkbox"> Masker / Respirator</label></td><td><label class="checkbox-group"><input type="checkbox"> Baik</label></td>
                    <td><label class="checkbox-group"><input type="checkbox"> Safety Shoes</label></td><td><label class="checkbox-group"><input type="checkbox"> Baik</label></td>
                    <td><input type="text"></td><td><label class="checkbox-group"><input type="checkbox"> Baik</label></td>
                </tr>
                <tr>
                    <td><label class="checkbox-group"><input type="checkbox"> Sarung Tangan</label></td><td><label class="checkbox-group"><input type="checkbox"> Baik</label></td>
                    <td><label class="checkbox-group"><input type="checkbox"> Safety Goggle</label></td><td><label class="checkbox-group"><input type="checkbox"> Baik</label></td>
                    <td><input type="text"></td><td><label class="checkbox-group"><input type="checkbox"> Baik</label></td>
                </tr>
                <tr>
                    <td><label class="checkbox-group"><input type="checkbox"> Safety Vest / Rompi K3</label></td><td><label class="checkbox-group"><input type="checkbox"> Baik</label></td>
                    <td><label class="checkbox-group"><input type="checkbox"> Kotak P3K</label></td><td><label class="checkbox-group"><input type="checkbox"> Baik</label></td>
                    <td><input type="text"></td><td><label class="checkbox-group"><input type="checkbox"> Baik</label></td>
                </tr>
            </tbody>
        </table>
        <div class="page-number">Ed. 3, Rev. 4</div>
    </div>

    <!-- HALAMAN 3: PROSEDUR & ADMINISTRASI -->
    <div class="paper-page" id="page3">
        <div class="header-target"></div>

        <span class="section-title">D. Prosedur Pengambilan Contoh Uji Air</span>
        <div style="padding-left: 10px; margin-bottom: 8px;">
            <strong>1. Prosedur Pengambilan Contoh Uji Air</strong>
            <div>
                <label class="checkbox-group"><input type="checkbox"> Metode Pengambilan Contoh Uji Air Limbah untuk Pengujian Fisika dan Kimia (SNI 8990:2021)</label><br>
                <label class="checkbox-group"><input type="checkbox"> Metode Pengambilan Contoh Uji Air untuk Pengujian Fisika dan Kimia (SNI 8995:2021)</label><br>
                <label class="checkbox-group"><input type="checkbox"> Metode Pengambilan Contoh Uji Air dan Air Limbah untuk Parameter Mikrobiologi (SNI 9063:2022)</label><br>
                <label class="checkbox-group"><input type="checkbox"> Metode Pengambilan Contoh Uji Air Laut (SNI 6964.8:2015)</label>
            </div>

            <strong style="margin-top: 5px; display:block;">2. Teknik Pengambilan Contoh Uji Air</strong>
            <div>
                <label class="checkbox-group"><input type="checkbox"> Sesaat / Grab Sampling</label>
                <label class="checkbox-group"><input type="checkbox"> Komposit Tempat</label>
                <label class="checkbox-group"><input type="checkbox"> Komposit Gabungan</label><br>
                <label class="checkbox-group"><input type="checkbox"> Komposit Waktu</label>
                <label class="checkbox-group"><input type="checkbox"> Komposit Kedalaman</label>
            </div>

            <strong style="margin-top: 5px; display:block;">3. Pengendalian Pengambilan Contoh Uji Air</strong>
            <div>
                <label class="checkbox-group"><input type="checkbox"> Sampel Terbelah (Split)</label>
                <label class="checkbox-group"><input type="checkbox"> Blanko Wadah Sampel</label>
                <label class="checkbox-group"><input type="checkbox"> Blanko Perjalanan</label><br>
                <label class="checkbox-group"><input type="checkbox"> Sampel Duplikat (Duplicate)</label>
                <label class="checkbox-group"><input type="checkbox"> Blanko Peralatan</label>
                <label class="checkbox-group"><input type="checkbox"> Blanko Lapangan</label>
            </div>
        </div>

        <span class="section-title">E. Administrasi Pengambilan Contoh Uji Air</span>
        <table style="width: 100%; border-collapse: collapse; margin-bottom: 10px;">
            <tr>
                <td style="width: 60%; padding: 3px 0;">1. Surat Tugas atau Surat Pengantar Pelaksanaan Kegiatan Pengambilan Contoh Uji:</td>
                <td><label class="checkbox-group"><input type="checkbox"> Ada</label> <label class="checkbox-group"><input type="checkbox"> Tidak</label></td>
            </tr>
            <tr>
                <td style="padding: 3px 0;">2. Transportasi Perjalanan Pengambilan Contoh Uji:</td>
                <td><label class="checkbox-group"><input type="checkbox"> Darat</label> <label class="checkbox-group"><input type="checkbox"> Laut</label> <label class="checkbox-group"><input type="checkbox"> Udara</label></td>
            </tr>
            <tr>
                <td style="padding: 3px 0;">3. Biaya Perjalanan / Tiket Perjalanan / Akomodasi Lain-Lain:</td>
                <td><label class="checkbox-group"><input type="checkbox"> Ada</label> <label class="checkbox-group"><input type="checkbox"> Tidak</label></td>
            </tr>
            <tr>
                <td style="padding: 3px 0;">4. Asuransi Perjalanan Petugas Pengambilan Contoh Uji:</td>
                <td><label class="checkbox-group"><input type="checkbox"> Ada</label> <label class="checkbox-group"><input type="checkbox"> Tidak</label></td>
            </tr>
            <tr>
                <td colspan="2" style="padding: 3px 0;">5. Perlengkapan Pendukung Administrasi Pengambilan Contoh Uji:</td>
            </tr>
            <tr>
                <td style="padding-left: 15px;">a. Dokumen Pengambilan Contoh Uji</td>
                <td><label class="checkbox-group"><input type="checkbox"> Ada</label> <label class="checkbox-group"><input type="checkbox"> Tidak</label></td>
            </tr>
            <tr>
                <td style="padding-left: 15px;">b. Alat Tulis (Pulpen, Spidol Permanen, dll)</td>
                <td><label class="checkbox-group"><input type="checkbox"> Ada</label> <label class="checkbox-group"><input type="checkbox"> Tidak</label></td>
            </tr>
            <tr>
                <td style="padding-left: 15px;">c. Kertas Label Contoh Uji</td>
                <td><label class="checkbox-group"><input type="checkbox"> Ada</label> <label class="checkbox-group"><input type="checkbox"> Tidak</label></td>
            </tr>
            <tr>
                <td style="padding-left: 15px;">d. Kamera Dokumentasi</td>
                <td><label class="checkbox-group"><input type="checkbox"> Ada</label> <label class="checkbox-group"><input type="checkbox"> Tidak</label></td>
            </tr>
            <tr>
                <td style="padding-left: 15px;">e. Box Container Perlengkapan</td>
                <td><label class="checkbox-group"><input type="checkbox"> Ada</label> <label class="checkbox-group"><input type="checkbox"> Tidak</label></td>
            </tr>
        </table>

        <span class="section-title">Instruksi Khusus:</span>
        <textarea rows="4" style="border: 1px solid #ccc; width: 100%; padding: 5px;"></textarea>

        <table style="width: 100%; margin-top: 30px; text-align: center;">
            <tr>
                <td style="width: 50%;">
                    Yang Mengesahkan,<br><strong>Manajer Teknis</strong>
                    <br><br><br><br><br>
                    ( <input type="text" style="width: 60%; text-align: center;"> )
                </td>
                <td style="width: 50%;">
                    Yang Membuat,<br><strong>Penyelia Petugas Pengambilan Contoh Uji</strong>
                    <br><br><br><br><br>
                    ( <input type="text" style="width: 60%; text-align: center;"> )
                </td>
            </tr>
        </table>
        <div class="page-number">Ed. 3, Rev. 4</div>
    </div>

    <!-- HALAMAN 4: REALISASI PENGAMBILAN CONTOH UJI -->
    <div class="paper-page" id="page4">
        <div class="header-target"></div>

        <div style="text-align: center; font-weight: bold; text-decoration: underline; margin-bottom: 10px;">REALISASI PENGAMBILAN CONTOH UJI</div>

        <table style="width: 100%; margin-bottom: 8px;">
            <tr><td style="width: 110px;">Nama Pelanggan</td><td style="width: 10px;">:</td><td><input type="text"></td></tr>
            <tr><td>Alamat Pelanggan</td><td>:</td><td><input type="text"></td></tr>
        </table>

        <table style="width: 100%; margin-bottom: 8px;">
            <tr>
                <td style="width: 110px;">Tanggal Pengambilan</td><td style="width: 10px;">:</td><td><input type="text"></td>
                <td style="width: 40px; text-align: right;">Jam</td><td style="width: 10px;">:</td><td><input type="text"></td>
                <td style="width: 100px; text-align: right;">Kode Contoh Uji</td><td style="width: 10px;">:</td><td><input type="text"></td>
            </tr>
        </table>

        <span class="section-title">Jenis Contoh Uji yang Diambil:</span>
        <div>
            <label class="checkbox-group"><input type="checkbox"> Air Sungai & Sejenisnya</label>
            <label class="checkbox-group"><input type="checkbox"> Air Bersih Sanitasi</label>
            <label class="checkbox-group"><input type="checkbox"> Air Minum</label>
            <label class="checkbox-group"><input type="checkbox"> Air Rawa</label>
            <label class="checkbox-group"><input type="checkbox"> Air Limbah Domestik</label><br>
            <label class="checkbox-group"><input type="checkbox"> Air Danau & Sejenisnya</label>
            <label class="checkbox-group"><input type="checkbox"> Air Tanah / Akuifer</label>
            <label class="checkbox-group"><input type="checkbox"> Air Estuari</label>
            <label class="checkbox-group"><input type="checkbox"> Air Laut</label>
            <label class="checkbox-group"><input type="checkbox"> Air Limbah:</label> <input type="text" style="width: 150px;">
        </div>

        <span class="section-title">Titik Pengambilan Contoh Uji:</span>
        <div>
            <label class="checkbox-group"><input type="checkbox"> Inlet STP / WWTP</label> 
            <label class="checkbox-group" style="margin-left: 150px;"><input type="checkbox"> Aliran Upstream</label><br>
            <label class="checkbox-group"><input type="checkbox"> Outlet STP / WWTP</label>
            <label class="checkbox-group" style="margin-left: 142px;"><input type="checkbox"> Aliran Downstream</label><br>
            <label class="checkbox-group"><input type="checkbox"> Tidak Ada STP / WWTP ( <input type="text" style="width: 150px;"> )</label>
        </div>

        <span class="section-title">Teknik Pengambilan Contoh Uji:</span>
        <div>
            <label class="checkbox-group"><input type="checkbox"> Sesaat / Grab Sampling</label>
            <label class="checkbox-group"><input type="checkbox"> Komposit Tempat</label>
            <label class="checkbox-group"><input type="checkbox"> Komposit Gabungan</label><br>
            <label class="checkbox-group"><input type="checkbox"> Komposit Waktu</label>
            <label class="checkbox-group"><input type="checkbox"> Komposit Kedalaman</label>
        </div>

        <span class="section-title">Metode Pengambilan Contoh Uji:</span>
        <div>
            <label class="checkbox-group"><input type="checkbox"> Metode Pengambilan Contoh Uji Air Limbah untuk Pengujian Fisika dan Kimia (SNI 8990:2021)</label><br>
            <label class="checkbox-group"><input type="checkbox"> Metode Pengambilan Contoh Uji Air untuk Pengujian Fisika dan Kimia (SNI 8995:2021)</label><br>
            <label class="checkbox-group"><input type="checkbox"> Metode Pengambilan Contoh Uji Air dan Air Limbah untuk Parameter Mikrobiologi (SNI 9063:2022)</label><br>
            <label class="checkbox-group"><input type="checkbox"> Metode Pengambilan Contoh Uji Air Laut (SNI 6964.8:2015)</label>
        </div>

        <span class="section-title">Pengendalian Mutu Contoh Uji:</span>
        <div>
            <label class="checkbox-group"><input type="checkbox"> Sampel Terbelah (Split)</label>
            <label class="checkbox-group" style="margin-left: 50px;"><input type="checkbox"> Blanko Peralatan</label>
            <label class="checkbox-group" style="margin-left: 50px;"><input type="checkbox"> Blanko Lapangan</label><br>
            <label class="checkbox-group"><input type="checkbox"> Sampel Duplikat (Duplicate)</label>
            <label class="checkbox-group" style="margin-left: 36px;"><input type="checkbox"> Blanko Wadah Sampel</label>
            <label class="checkbox-group" style="margin-left: 35px;"><input type="checkbox"> Blanko Perjalanan</label>
        </div>

        <span class="section-title">Pengukuran Lapangan:</span>
        <table class="form-table" style="text-align: center; font-size: 9.5px;">
            <thead>
                <tr>
                    <th colspan="4">Parameter Insitu (Wajib)</th>
                    <th colspan="2">Parameter Insitu (Tambahan)</th>
                    <th colspan="6">Parameter Fisik</th>
                    <th rowspan="3">Catatan Observasi</th>
                </tr>
                <tr>
                    <th rowspan="2">pH</th>
                    <th rowspan="2">Suhu (°C)</th>
                    <th colspan="2">Oksigen Terlarut (DO)</th>
                    <th rowspan="2">Debit (m³/s) atau (m³/hari)</th>
                    <th rowspan="2">Parameter Lain:</th>
                    <th rowspan="2">Berwarna</th>
                    <th rowspan="2">Berbau</th>
                    <th rowspan="2">Partikel Kotoran</th>
                    <th rowspan="2">Lapisan Minyak</th>
                    <th rowspan="2">Berbusa</th>
                    <th rowspan="2">Sampah</th>
                </tr>
                <tr>
                    <th>Volume Titrasi (mL)</th>
                    <th>DO Meter (mg/L)</th>
                </tr>
            </thead>
            <tbody>
                <script>
                    for(let i=1; i<=3; i++) {
                        document.write(`
                            <tr>
                                <td><input type="text"></td>
                                <td><input type="text"></td>
                                <td><input type="text"></td>
                                <td><input type="text"></td>
                                <td><input type="text"></td>
                                <td><input type="text"></td>
                                <td><input type="text"></td>
                                <td><input type="text"></td>
                                <td><input type="text"></td>
                                <td><input type="text"></td>
                                <td><input type="text"></td>
                                <td><input type="text"></td>
                                <td><input type="text"></td>
                            </tr>
                        `);
                    }
                </script>
            </tbody>
        </table>
        <div class="page-number">Ed. 3, Rev. 4</div>
    </div>

    <!-- HALAMAN 5: SKETSA & PENGAMANAN CONTOH UJI -->
    <div class="paper-page" id="page5">
        <div class="header-target"></div>

        <div class="flex-container">
            <div class="flex-col" style="flex: 1.2;">
                <span class="section-title">Sketsa Lokasi atau Foto Titik Pengambilan Contoh Uji:</span>
                <div class="sketch-box" id="sketch-container">
                    <span style="color: #999;" class="no-print-panel">Gambar sketsa akan muncul di sini</span>
                </div>
            </div>
            <div class="flex-col" style="flex: 0.8;">
                <span class="section-title">Titik Koordinat Pengambilan Contoh Uji:</span>
                <div style="margin-bottom: 4px;">LS: <input type="text" style="width: 80%;"></div>
                <div style="margin-bottom: 8px;">BT: <input type="text" style="width: 80%;"></div>
                <div style="margin-bottom: 8px;">Suhu Udara: <input type="text" style="width: 40%;"> °C</div>
                
                <span class="section-title">Kondisi Cuaca:</span>
                <div>
                    <label class="checkbox-group"><input type="checkbox"> Cerah</label>
                    <label class="checkbox-group"><input type="checkbox"> Berawan</label>
                    <label class="checkbox-group"><input type="checkbox"> Hujan</label>
                </div>
            </div>
        </div>

        <span class="section-title">Rangkaian Pengamanan Contoh Uji:</span>
        <table class="form-table">
            <thead>
                <tr>
                    <th style="width: 4%;">No</th>
                    <th style="width: 14%;">Kode CU</th>
                    <th style="width: 22%;">Parameter</th>
                    <th style="width: 15%;">Jenis Wadah</th>
                    <th style="width: 15%;">Volume</th>
                    <th style="width: 18%;">Pengawetan</th>
                    <th style="width: 12%;">Waktu Simpan</th>
                </tr>
            </thead>
            <tbody>
                <script>
                    for(let i=1; i<=5; i++){
                        document.write(`
                            <tr>
                                <td style="text-align: center;">${i}</td>
                                <td><input type="text"></td>
                                <td><input type="text"></td>
                                <td>
                                    <label class="checkbox-group"><input type="checkbox"> Plastik PE</label><br>
                                    <label class="checkbox-group"><input type="checkbox"> Gelas Kaca</label><br>
                                    <label class="checkbox-group"><input type="checkbox"> Winkler</label>
                                </td>
                                <td>
                                    <label class="checkbox-group"><input type="checkbox"> 102 ml</label><br>
                                    <label class="checkbox-group"><input type="checkbox"> 250 ml</label><br>
                                    <label class="checkbox-group"><input type="checkbox"> 500 ml</label><br>
                                    <label class="checkbox-group"><input type="checkbox"> 1000 ml</label>
                                </td>
                                <td>
                                    <label class="checkbox-group"><input type="checkbox"> Tanpa Pengawet</label><br>
                                    <label class="checkbox-group"><input type="checkbox"> H₂SO₄</label><br>
                                    <label class="checkbox-group"><input type="checkbox"> HNO₃</label><br>
                                    <label class="checkbox-group"><input type="checkbox"> NaOH</label>
                                </td>
                                <td><input type="text"></td>
                            </tr>
                        `);
                    }
                </script>
            </tbody>
        </table>

        <span class="section-title">Abnormalitas atau Penyimpangan dari Kondisi Normal yang Dapat Mempengaruhi Interpretasi Hasil Pengujian:</span>
        <div style="display: flex; gap: 15px; margin-bottom: 5px;">
            <div style="flex: 1;">
                1. <input type="text" style="width: 90%;"><br>
                2. <input type="text" style="width: 90%;"><br>
                3. <input type="text" style="width: 90%;">
            </div>
            <div style="flex: 1;">
                4. <input type="text" style="width: 90%;"><br>
                5. <input type="text" style="width: 90%;"><br>
                6. <input type="text" style="width: 90%;">
            </div>
        </div>

        <div style="margin-top: 5px;">
            <label class="checkbox-group"><input type="checkbox"> Pelaksanaan sesuai rencana</label><br>
            <label class="checkbox-group"><input type="checkbox"> Pelaksanaan tidak sesuai rencana. Hal ini dikarenakan:</label>
            <input type="text" style="width: 100%;">
        </div>

        <table class="footer-sign">
            <tr>
                <td style="width: 40%; text-align: center;">
                    Mengetahui,<br><strong>Penyelia Petugas Pengambilan Contoh Uji</strong>
                    <br><br><br><br>
                    ( <input type="text" style="width: 75%; text-align: center;"> )
                </td>
                <td style="width: 60%;">
                    <strong>Petugas Pengambilan Contoh Uji</strong>
                    <div style="display: flex; justify-content: space-between; margin-top: 3px;">
                        <span>Nama Petugas</span>
                        <span style="margin-right: 40px;">Tanda Tangan</span>
                    </div>
                    <div style="margin-top: 3px;">
                        1) <input type="text" style="width: 85%;"><br>
                        2) <input type="text" style="width: 85%;"><br>
                        3) <input type="text" style="width: 85%;">
                    </div>
                </td>
            </tr>
        </table>
        <div class="page-number">Ed. 3, Rev. 4</div>
    </div>

    <!-- LOGIKA JAVASCRIPT -->
    <script>
        // Render Header Kop untuk setiap halaman
        const headerTemplate = document.getElementById('header-template').content;
        document.querySelectorAll('.header-target').forEach(target => {
            target.appendChild(headerTemplate.cloneNode(true));
        });

        // Fitur Unggah Logo Header (Otomatis memperbarui seluruh halaman)
        document.getElementById('input-logo').addEventListener('change', function(e) {
            const file = e.target.files[0];
            if (file) {
                const reader = new FileReader();
                reader.onload = function(event) {
                    document.querySelectorAll('.header-logo-img').forEach(img => {
                        img.src = event.target.result;
                    });
                };
                reader.readAsDataURL(file);
            }
        });

        // Fitur Unggah Gambar Sketsa Lokasi
        document.getElementById('input-sketch').addEventListener('change', function(e) {
            const file = e.target.files[0];
            if (file) {
                const reader = new FileReader();
                reader.onload = function(event) {
                    const sketchContainer = document.getElementById('sketch-container');
                    sketchContainer.innerHTML = '';
                    const img = document.createElement('img');
                    img.src = event.target.result;
                    sketchContainer.appendChild(img);
                };
                reader.readAsDataURL(file);
            }
        });
    </script>
</body>
</html>
