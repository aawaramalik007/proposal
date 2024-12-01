<html>
<head>
    <title>A Special Question</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background: linear-gradient(to right, cyan, lightblue);
            text-align: center;
            height: 100vh;
            margin: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            font-family: "Comic Sans MS";
          	margin-top: 500px;
        }

        section {
            background-color: rgba(0, 0, 0, 0.3); /* Semi-transparent white */
            padding: 20px;
            border-radius: 10px;
        }

        h1 {
            color: #333;
        }

        p {
            color: #666;
        }

        button {
            background-color: #ccc;
            border: none;
            padding: 10px 20px;
            text-decoration: none;
            display: inline-block;
            font-size: 16px;
            margin: 10px;
            cursor: pointer;
            font-family: "Comic Sans MS";
        }
    </style>
</head>
<body>
<section>
    <h1>Sawera ji! Will you be my... life partner?</h1>
    <p>I really like spending time with you. Would you like to be more than friends?</p>
    <button id="yes">Yes</button>
    <button id="no">No</button>

    <div id="result" style="display: none;">
        <p id="message"></p>
    </div>
</section>

<script>
    const yesButton = document.getElementById('yes');
    const noButton = document.getElementById('no');
    const resultDiv = document.getElementById('result');
    const messageElement = document.getElementById('message');

    yesButton.addEventListener('click', () => {
        messageElement.textContent = 'I love you !';
        resultDiv.style.display = 'block';
    });

    noButton.addEventListener('click', () => {
        messageElement.textContent = 'I hope you will change your mind later, I will keep trying.';
        resultDiv.style.display = 'block';
    });
</script>
</body>
</html>
