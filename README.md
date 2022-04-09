| DEVI SILMA YUNIAR | 312010458 |
|-------------------|-----------|
| Pemrograman Web   |  Lab5Web  |

## 1). Membuat Javascript Sederhana
### Hasil
![javascript](img/pengenalan_javascript.png)

Membuat javascript sederhana dengan perintah document.write dan console.log

### Contoh Coding 
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MENGENAL JAVASCRIPT</title>
</head>
<body>
    <h1>Pengenalan javascript</h1>
    <h3>Contoh Document.write dan Console.log</h3>
    <script lang="javascript">
        document.write ("Hello World")
        console.log ("Hello World")
    </script>
</body>
</html>
```

## 2). Javascript Dasar
### Hasil
![Alert](img/alertBox.png)
Properti alert untuk perintah pop

### Contoh Coding
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Alert Box</title>
</head>
<body>
    <script lang="javascript">
        window.alert("ini merupakan pesan untuk anda")
    </script>
</body>
</html>
```


### 3). Method Dalam Objek
### Hasil
![method](img/method.png)

Menggunakan method dalam objek javascript

### Contoh Coding
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Script Javascript</title>
</head>
<body>
    Percobaan memakai Javascript:<br>
    <script lang="javascript">
        document.write("selamat mencoba javascript<br> ");
        document.write ("semoga sukses");
    </script>
</body>
</html>
```

## 4). Mamakai  Properti Prompt
### Hasil
![prompt](img/Prompt.png)

pemakaian properti prompt window pada script

### Contoh Coding
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pemasukan Data</title>
</head>
<body>
    <script lang="javascript">
        var nama = prompt ("siapa nama anda?", "masukkan nama anda!");
        document.write("hai, " + nama);
    </script>
</body>
</html>
```

## 5). Pembuatan Function Dan Cara Pemanggilannya
### Hasil

![function](img/function.png)

menggunakan function dengan body onload di javascript seperti gambar diatas 

### Contoh Coding
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contoh program javascript</title>
    <script lang="javascript">
        function pesan(){
            alert ("memanggil javascript lewat body onload")
        }
    </script>
</head>
<body onload=pesan()>
    
</body>
</html>
```
