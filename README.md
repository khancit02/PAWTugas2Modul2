# PAWTugas2Modul2
<!DOCTYPE html>
<html>
<head>
    <title>Form Registrasi</title>
</head>
<body>
    <h1>Form Registrasi</h1>

    <form>
        <h2>Biodata</h2> <fieldset>
        <label for="nama">Nama Mahasiswa:</label>
        <input type="text" id="nama" name="nama"><br><br>

        <label for="nim">No Induk Mahasiswa (NIM):</label>
        <input type="text" id="nim" name="nim"><br><br>

        <label for="alamat">Alamat Mahasiswa:</label>
        <textarea id="alamat" name="alamat"></textarea><br><br>

        <label for="tanggal_lahir">Tanggal Lahir:</label>
        <select id="tanggal_lahir" name="tanggal_lahir">
            <option value="01">01</option>
            </select>
        <select id="bulan_lahir" name="bulan_lahir">
            <option value="Januari">Januari</option>
            </select>
        <select id="tahun_lahir" name="tahun_lahir">
            <option value="1990">1990</option>
            </select><br><br>

        <label>Jenis Kelamin:</label>
        <input type="radio" name="jenis_kelamin" value="pria"> Pria
        <input type="radio" name="jenis_kelamin" value="wanita"> Wanita<br><br>

        <label for="foto">Upload Foto:</label>
        <input type="file" id="foto" name="foto"><br><br>

        <label for="url_website">URL Website:</label>
        <input type="url" id="url_website" name="url_website"><br><br>

        <label for="perguruan tinggi">Perguruan Tinggi:</label>
        <input type="text" id="perguruan tinggi" name="perguruan tinggi"><br><br>
        </fieldset>
        <br>
       <fieldset>
        <h2>Info Akun</h2>
        <label for="email">Email:</label>
        <input type="email" id="email" name="email"><br><br>

        <label for="username">Username:</label>
        <input type="text" id="username" name="username"><br><br>

        <label for="password">Password:</label>
        <input type="password" id="password" name="password"><br><br>

        <label for="konfirmasi_password">Ulangi Password:</label>
        <input type="password" id="konfirmasi_password" name="konfirmasi_password"><br><br>
        </fieldset>
        <br>
        <fieldset>
        <h2>Kemampuan Dasar</h2>
        <input type="checkbox" name="kemampuan[]" value="HTML"> HTML
        <input type="checkbox" name="kemampuan[]" value="CSS"> CSS
        <input type="checkbox" name="kemampuan[]" value="Javascript"> Javascript
        <input type="checkbox" name="kemampuan[]" value="PHP"> PHP
        <input type="checkbox" name="kemampuan[]" value="MySQL"> MySQL
        <input type="checkbox" name="kemampuan[]" value="Laravel"> Laravel
        <input type="checkbox" name="kemampuan[]" value="React Native"> React Native
        </fieldset>
        <br>
        <button type="reset">Reset</button>
        <button type="submit">Simpan</button>
    </form>
</body>
</html>
