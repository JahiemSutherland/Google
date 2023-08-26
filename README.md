<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Google Search</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f2f2f2;
        }
        .search-container {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        .search-box {
            background-color: white;
            border: 1px solid #ccc;
            border-radius: 8px;
            padding: 10px;
            width: 400px;
            display: flex;
            box-shadow: 0px 2px 6px rgba(0, 0, 0, 0.1);
        }
        .search-input {
            flex: 1;
            border: none;
            outline: none;
            font-size: 16px;
        }
        .search-button {
            background-color: #4285f4;
            color: white;
            border: none;
            border-radius: 4px;
            padding: 8px 15px;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <div class="search-container">
        <div class="search-box">
            <input type="text" class="search-input" placeholder="Search Google">
            <button class="search-button">Google Search</button>
        </div>
    </div>
</body>
</html>
