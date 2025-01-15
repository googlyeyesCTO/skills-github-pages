<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Googly Eyes on Images</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 20px;
        }
        canvas {
            margin-top: 20px;
            border: 1px solid #ccc;
        }
        #upload {
            margin-top: 20px;
        }
        #googly-eyes {
            margin-top: 20px;
            padding: 10px 20px;
            background-color: #4CAF50;
            color: white;
            border: none;
            cursor: pointer;
        }
        #googly-eyes:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>
    <h1>Put Googly Eyes on Your Picture!</h1>
    <input type="file" id="upload" accept="image/*">
    <canvas id="canvas"></canvas>
    <button id="googly-eyes">Add Googly Eyes</button>

    <script src="script.js"></script>
</body>
</html>
