<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Img2List Decimal RGB Converter</title>
<style>
  body { font-family: Arial, sans-serif; margin: 20px; }
  input, button { margin: 5px 0; }
  canvas { display: none; }
</style>
</head>
<body>
<h2>Img2List Decimal RGB Converter</h2>

<label>Upload Image:</label>
<input type="file" id="imageInput" accept="image/*"><br>

<label>Resize Width:</label>
<input type="number" id="resizeWidth" placeholder="Leave blank to keep original"><br>
<label>Resize Height:</label>
<input type="number" id="resizeHeight" placeholder="Leave blank to keep original"><br>

<button id="convertBtn">Convert and Download TXT</button>

<canvas id="canvas"></canvas>

<script>
const imageInput = document.getElementById('imageInput');
const convertBtn = document.getElementById('convertBtn');
const canvas = document.getElementById('canvas');
const ctx = canvas.getContext('2d');

convertBtn.addEventListener('click', () => {
    const file = imageInput.files[0];
    if (!file) {
        alert("Please upload an image first!");
        return;
    }

    const img = new Image();
    img.onload = () => {
        // Resize
        const width = document.getElementById('resizeWidth').value || img.width;
        const height = document.getElementById('resizeHeight').value || img.height;
        canvas.width = width;
        canvas.height = height;
        ctx.drawImage(img, 0, 0, width, height);

        // Get pixel data
        const imageData = ctx.getImageData(0, 0, width, height).data;
        let result = [];
        for (let i = 0; i < imageData.length; i += 4) {
            const r = imageData[i];
            const g = imageData[i + 1];
            const b = imageData[i + 2];
            // Decimal combined RGB: r*65536 + g*256 + b
            result.push(r * 65536 + g * 256 + b);
        }

        // Create TXT file with one number per line
        const blob = new Blob([result.join('\n')], {type: 'text/plain'});
        const link = document.createElement('a');
        link.href = URL.createObjectURL(blob);
        link.download = 'decimal_rgb_list.txt';
        link.click();
        URL.revokeObjectURL(link.href);
    };
    img.src = URL.createObjectURL(file);
});
</script>
</body>
</html>
