<!DOCTYPE html>
<html lang="my">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>မရယ် စိတ်မဆိုးတော့ပါနဲ့..</title>
    <style>
        body {
            text-align: center;
            font-family: Arial, sans-serif;
            margin-top: 50px;
            background-color: #ffeff0;
        }
        h2 {
            font-size: 24px;
            font-weight: bold;
            color: #ff4d6d;
        }
        #loveText {
            font-size: 20px;
            font-weight: bold;
            transition: font-size 0.3s ease-in-out;
            color: #d6336c;
        }
        .button {
            padding: 10px 20px;
            font-size: 16px;
            margin: 10px;
            cursor: pointer;
            border: none;
            border-radius: 10px;
            color: white;
        }
        .happy {
            background-color: #ff85a2;
        }
        .angry {
            background-color: #ff4d6d;
        }
    </style>
</head>
<body>

    <h2>မရယ် 😘 စိတ်မဆိုးတော့ပါနဲ့.. 🥺</h2>
    
    <h3 id="loveText">ချစ်တယ် 💕</h3>

    <button class="button happy" onclick="increaseSize()">စိတ်မဆိုးတော့ဘူးရှင် 🤗</button>
    <button class="button angry" onclick="changeText()">စိတ်ဆိုးမှာဘဲ 😠</button>

    <script>
        let size = 20;
        function increaseSize() {
            size += 10;
            document.getElementById("loveText").style.fontSize = size + "px";
        }

        function changeText() {
            let texts = [
                "မောင်ကိုမချစ်တော့ဘူးလား 🥺",
                "အဲ့လိုမလုပ်ပါနဲ့ 😢",
                "ပြုပြင်ပါမယ်မရယ် 🤗",
                "အခွင့်အရေးပေးပါနော် 😭",
                "ခွင့်လွှတ်ပေးပါလို့ 😔",
                "ချစ်တယ်လေနော် 💕"
            ];
            let randomText = texts[Math.floor(Math.random() * texts.length)];
            document.getElementById("loveText").innerHTML = randomText;
        }
    </script>

</body>
</html>
