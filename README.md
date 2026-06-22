# HW01
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Random Flashcard Generator</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <div class="container">
        <h1>💡 Random Flashcards</h1>
        
        <div class="flashcard-wrapper">
            <div class="flashcard" id="flashcard">
                <div class="front">
                    <p class="word" id="word-front">Loading...</p>
                    <span class="hint">Click to flip</span>
                </div>
                <div class="back">
                    <p class="pos" id="word-pos">[n.]</p>
                    <p class="translation" id="word-back">Loading...</p>
                </div>
            </div>
        </div>

        <button id="next-btn">Next Word ➡️</button>
    </div>

    <script src="script.js"></script>
</body>
</html>
