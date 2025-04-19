<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>High Frequency Flag</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #f0f0f0;
        }
        .container {
            display: flex;
            align-items: center;
        }
        .pole {
            width: 10px;
            height: 200px;
            background-color: #333;
            border-radius: 5px;
        }
        .flag {
            width: 150px;
            height: 100px;
            background: linear-gradient(45deg, #007bff, #ffffff, #007bff);
            position: relative;
            box-shadow: 2px 2px 5px rgba(0, 0, 0, 0.3);
            animation: wave 2s ease-in-out infinite;
        }
        .flag::before {
            content: "HF";
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            font