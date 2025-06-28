<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>My Pixel Planet</title>
<style>
  body { display: flex; flex-direction: column; align-items: center; font-family: sans-serif; }
  canvas { border: 1px solid #000; touch-action: none; }
  #colors { margin-top: 10px; }
  button { width: 30px; height: 30px; margin: 2px; border: none; }
</style>
</head>
<body>
  <h1>My Pixel Planet</h1>
  <canvas id="canvas" width="300" height="300"></canvas>
  <div id="colors">
    <button style="background:red" onclick="setColor('red')"></button>
    <button style="background:green" onclick="setColor('green')"></button>
    <button style="background:blue" onclick="setColor('blue')"></button>
    <button style="background:yellow" onclick="setColor('yellow')"></button>
    <button style="background:black" onclick="setColor('black')"></button>
    <button style="background:white; border:1px solid #ccc;" onclick="setColor('white')"></button>
  </div>

<script>
  const canvas = 
