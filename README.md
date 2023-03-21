# pratikum2

faris maulana<br>
3121101459<br>
TI.21.A3

# code Php dasar 1
```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <title>PHP Dasar</title>
</head>

<body>
    <h1>Belajar PHP Dasar</h1>
    <?php
    echo "Hello World";
    ?>
</body>
<h1>Menggunakan Variable</h1>
<?php
$nim = "312110459";
$nama = 'Faris';
echo "NIM : " . $nim . "<br>";
echo "Nama : $nama";
?>

</html>
```

# output
![lab1](https://user-images.githubusercontent.com/128495827/226687684-6a4a76af-2716-4a66-bed0-12ba2a939a41.PNG)

# code Php dasar 2
```
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>PHP Dasar</title>
</head>

<body>
  <!-- Variabel $_GET -->
  <h4><b>Predefine Variable</b></h4>
  <?php
  echo 'Selamat Datang ' . $_GET['nama']
  ?>
</body>

</html>
```

# output

![lab2](https://user-images.githubusercontent.com/128495827/226688286-4442c3bf-ef8a-48ae-9e7b-d9de2d59aa6a.PNG)

# code Php dasat 3
```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <title>PHP Dasar</title>
</head>

<body>
    <h2>Form Input</h2>
    <form method="post">
        <label>Nama: </label>
        <input type="text" name="nama">
        <input type="submit" value="Kirim">
    </form>
    <?php
    echo 'Selamat Datang ' . $_POST['nama'];
    ?>
</body>

</html>
```
# outpu

![lab3](https://user-images.githubusercontent.com/128495827/226688810-9e137a12-7b82-45f9-9a09-9a4071bb0d00.PNG)

# code Php dasar 4
```
<! html DOCTYPE>
<html lang="en">

<Head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <Basic ></title>
</Head>

<body>
  <?php
  $gaji = 500000;
  $pajak = 0.1;
  $THP = $pajak - ($gaji *  $pajak);
  Echo "Gaji sebelum pajak = Rp.  $gaji <br>";
  Echo "Gaji yang dibawa pulang = Rp.  $THP";
  ?>
</body>

</html>
```

# output

![lab4](https://user-images.githubusercontent.com/128495827/226689439-052b76bc-7f6e-43cc-8a34-0e3414b7cfff.PNG)

# code Php dasar 5
```
<! html DOCTYPE>
<html lang="en">

<Head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <Basic ></title>
</Head>

<body>
  <h2>Kondisi If</h2>
  <?php
  $nama_hari = date("l");
  if ($nama_hari == "Rabu") {
    Echo "Wednesday";
  } elseif ($nama_hari == "Kamis") {
    Echo "Thursday";
  } else {
    Echo "jumat";
  }
  ?>
</body>
```

# output

![lab5](https://user-images.githubusercontent.com/128495827/226689880-03568dc1-8207-47ec-a7a9-64c3fcab1cd5.PNG)

# code Php dasar 6
```
<h2>Kondisi Switch</h2>
<?php
$nama_hari = date("l");
Switch ($nama_hari) {
  case "Minggu":
    Echo "Sunday";
    Break;
  case "Senin":
    Echo "Monday";
    Break;
  case "Selasa":
    Echo "Tuesday";
    Break;
  Default:
    Echo "Selasa";
}
Echo "/$nama_hari";
?>
```

# output

![lab6](https://user-images.githubusercontent.com/128495827/226690191-d14f13d7-381d-4df6-828c-53a309ed86c5.PNG)

# code Php dasar 7
```
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>PHP Dasar</title>
</head>

<body>
  <h2>Perulangan For</h2>
  <?php
  echo "Perulangan 50 sampai 60 <br />";
  for ($i = 50; $i <= 60; $i++) {
    echo "Perulangan ke: " . $i . '<br />';
  }
  echo "Perulangan Menurun dari 60 ke 50 <br />";
  for ($i = 60; $i >= 50; $i--) {
    echo "Perulangan ke: " . $i . '<br />';
  }
  ?>
</body>

</html>
```

# output

![lab7](https://user-images.githubusercontent.com/128495827/226690710-9ede3c67-aee0-4dff-9176-58933597c75a.PNG)

# code Php dasar 8
```
<h2>Perulangan While</h2>
<?php
echo "Perulangan 10 sampai 20 <br />";
$i = 10;
while ($i <= 20) {
  echo "Perulangan ke: " . $i . '<br />';
  $i++;
}
?>
```

# output

![lab8](https://user-images.githubusercontent.com/128495827/226691279-47fa909a-7b78-45ad-b9de-18c8902c80ac.PNG)

# code Php dasar 9
```
<h2>Perulangan Do while</h2>
<?php
echo "Perulangan 50 sampai 70 <br />";
$i = 50;
do {
  echo "Perulangan ke: " . $i . '<br />';
  $i++;
} while ($i <= 70);
?>
```
# output

![lab9](https://user-images.githubusercontent.com/128495827/226691595-4df64e5d-656b-4112-abc5-d5b1316e9b1f.PNG)

