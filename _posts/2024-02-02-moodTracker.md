<style>
    #mood-buttons {
        display: flex;
        justify-content: center;
        margin-top: 20px;
    }

    .mood-button {
        background-color: #fff;
        border: 2px solid #ccc;
        border-radius: 50%;
        font-size: 24px;
        width: 60px;
        height: 60px;
        margin: 0 10px;
        cursor: pointer;
    }

    .happy { color: #ffd700; }
    .neutral { color: #a9a9a9; }
    .sad { color: #87CEEB; }
    .mad { color: #ff6347; }
</style>

<body>
    <h2>How did you feel today?</h2>
    <div id="mood-buttons">
        <button class="mood-button happy" onclick="trackMood('Happy')">😊</button>
        <button class="mood-button neutral" onclick="trackMood('Neutral')">😐</button>
        <button class="mood-button sad" onclick="trackMood('Sad')">😢</button>
        <button class="mood-button mad" onclick="trackMood('Mad')">😡</button>
    </div>

<script>
    function trackMood(mood) {
        alert('You felt ' + mood + ' today!');
        // You can add more logic here to save the mood or perform additional actions.
    }
</script>