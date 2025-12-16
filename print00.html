<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Typing Story</title>

<style>
    @font-face {
        font-family: "TNRCondensedBold";
        src: local("Times New Roman");
        font-weight: bold;
    }

    body {
        margin: 0;
        min-height: 100vh;
        background: #0b0b0b;
        color: #f2f2f2;
        font-family:"Times New Roman", serif;
        font-weight: bold;
        display: flex;
        justify-content: center;
        align-items: center;
        cursor: pointer;
    }

    #container {
        width: 80%;
        max-width: 900px;
        line-height: 1.5;
        font-size: 26px;
        white-space: pre-wrap;
    }

    .line {
        border-right: 2px solid #f2f2f2;
        padding-right: 4px;
        animation: blink 1s infinite;
    }

    @keyframes blink {
        0%, 50% { border-color: #f2f2f2; }
        51%, 100% { border-color: transparent; }
    }

    #buttonBox {
        margin-top: 25px;
    }

    button {
        background: transparent;
        border: 2px solid #f2f2f2;
        color: #f2f2f2;
        font-family: inherit;
        font-size: 20px;
        padding: 8px 18px;
        cursor: pointer;
    }

    button:hover {
        background: #f2f2f2;
        color: #0b0b0b;
    }
</style>
</head>

<body>

<div id="container"></div>

<script>
const container = document.getElementById("container");

let step = 0;
let typing = false;
let currentLine = null;
let charIndex = 0;

const firstBlock = [
    "i got muted",
    "so i found another way..",
    "(i mean it's kinda cool.)",
    "(back to my depression eras now since everything requires.",
    'i think ".css" matching with you a lot >>',
    "but that's not the point here."
];

const secondBlock = [
    `"knock knock..."`,
    `"it's Mei!!!!!! happy birthday to you, Urie 🎂, cherish every moment you have, best wishes to you! (vietnamese version) chuc mung sinh nhat con chien that lac Urie tui tin ban se thanh cong hon trong cuoc song va song healthy len ok"`,
    
];


function typeLine(text, delayAfter = 0, callback) {
    typing = true;
    charIndex = 0;

    const line = document.createElement("div");
    line.className = "line";
    container.appendChild(line);
    currentLine = line;

    function typingEffect() {
        if (charIndex < text.length) {
            line.textContent += text.charAt(charIndex);
            charIndex++;
            setTimeout(typingEffect, 60);
        } else {
            line.classList.remove("line");
            typing = false;
            if (callback) {
                setTimeout(callback, delayAfter);
            }
        }
    }
    typingEffect();
}

/* ========== FLOW ========== */

// Auto start after open
setTimeout(() => {
    runFirstBlock();
}, 1500);

function runFirstBlock() {
    let i = 0;
    function next() {
        if (i < firstBlock.length) {
            let delay = firstBlock[i].includes("cool") ? 2000 : 0;
            typeLine(firstBlock[i], delay, () => {
                i++;
                next();
            });
        }
    }
    next();
}

// Click logic
document.body.addEventListener("click", () => {
    if (typing) return;

    // Clear screen
    if (step === 0) {
        container.innerHTML = "";
        step = 1;
        typeLine(secondBlock[0]);
        showButton();
        return;
    }

    // Continue lines
    if (step > 1 && step <= secondBlock.length) {
        typeLine(secondBlock[step - 1]);
        step++;
    }
});

function showButton() {
    const box = document.createElement("div");
    box.id = "buttonBox";

    const btn = document.createElement("button");
    btn.textContent = "who's there?";

    btn.onclick = (e) => {
        e.stopPropagation();
        box.remove();
        step = 1;
        typeLine(secondBlock[1]);
    };

    box.appendChild(btn);
    container.appendChild(box);
}
</script>

</body>
</html>
