<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Ayo Giat Belajar</title>

  <style>
    *{
      margin:0;
      padding:0;
      box-sizing:border-box;
      font-family: Arial, sans-serif;
    }

    body{
      height:100vh;
      display:flex;
      justify-content:center;
      align-items:center;
      background: linear-gradient(135deg, #4facfe, #ffffff);
      overflow:hidden;
    }

    .container{
      background:white;
      padding:40px;
      border-radius:25px;
      text-align:center;
      width:350px;
      box-shadow:0 10px 30px rgba(0,0,0,0.2);
      position:relative;
    }

    h1{
      color:#1976d2;
      margin-bottom:15px;
    }

    p{
      color:#444;
      margin-bottom:25px;
      font-size:18px;
    }

    .stickers{
      font-size:50px;
      margin-bottom:15px;
    }

    .buttons{
      position:relative;
      height:120px;
    }

    button{
      padding:12px 25px;
      border:none;
      border-radius:15px;
      font-size:18px;
      cursor:pointer;
      transition:0.3s;
    }

    #yesBtn{
      background:#2196f3;
      color:white;
    }

    #yesBtn:hover{
      background:#1565c0;
      transform:scale(
