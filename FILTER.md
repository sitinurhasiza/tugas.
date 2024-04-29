# Penjelasan

# Kode Program
```html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Contoh Filter CSS</title>
<style>

    .container {
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100vh;

    }

  

    img {
        max-width: 100%;
        height: auto;
        margin: 0 auto;

    }


    .filters {
        display: flex;
        justify-content: space-around;
        margin-top: 20px;
        
    }

    .filter-option {
        cursor: pointer;
        padding: 10px;
        border: 1px solid #ccc;
        border-radius: 5px;
        background-color: pink;

    }

</style>
</head>
<body>

  
<div class="container">
    <img id="image" src="acica.jpeg" alt="Gambar dengan filter CSS">
</div>

<div class="filters">
    <div class="filter-option" onclick="applyFilter('none')">Normal</div>
    <div class="filter-option" onclick="applyFilter('grayscale(100%)')">Grayscale</div>
    <div class="filter-option" onclick="applyFilter('sepia(100%)')">Sepia</div>
    <div class="filter-option" onclick="applyFilter('blur(5px)')">Blur</div>
    <div class="filter-option" onclick="applyFilter('brightness(150%)')">Brightness</div>
    <div class="filter-option" onclick="applyFilter('contrast(200%)')">Contrast</div>
</div>

<script>
    function applyFilter(filter) {
        var image = document.getElementById('image');
        image.style.filter = filter;
    }
    
</script>
</body>
</html>
```

# Hasilnya 

