<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Animated Child Saying Hi</title>
<style>
    @keyframes wave {
        0% { transform: rotate(0deg); }
        20% { transform: rotate(20deg); }
        40% { transform: rotate(0deg); }
        60% { transform: rotate(20deg); }
        80% { transform: rotate(0deg); }
        100% { transform: rotate(0deg); }
    }
    .child {
        width: 100px;
        height: 100px;
        background-image: url('https://www.freepik.com/premium-vector/cartoon-boy-hand-up-say-hi-vector-illustration_134333218.htm');
        background-size: cover;
        position: relative;
        animation: wave 2s infinite;
    }
    .speech-bubble {
        position: absolute;
        bottom: 120%;
        left: 50%;
        transform: translateX(-50%);
        background-color: #ffffff;
        border: 2px solid #000000;
        padding: 10px;
        border-radius: 10px;
    }
</style>
</head>
<body>

<div class="child"></div>
<div class="speech-bubble">Hi!</div>

</body>
</html>

