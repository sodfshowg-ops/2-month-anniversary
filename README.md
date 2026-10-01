<!DOCTYPE html>
<html lang="th">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>2 Months With You ♡</title>

<style>
* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

body {
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
    background: #09090d;
    color: #fff;
    overflow-x: hidden;
}

section {
    min-height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 30px;
}

/* ---------- OPENING ---------- */

#opening {
    position: relative;
    text-align: center;
    background:
        radial-gradient(circle at 50% 40%, #30202b 0%, #09090d 55%);
}

.small {
    color: #aaa;
    letter-spacing: 4px;
    font-size: 12px;
    margin-bottom: 20px;
}

h1 {
    font-size: clamp(42px, 12vw, 90px);
    font-weight: 300;
    letter-spacing: -3px;
}

h1 span {
    color: #ff8fa3;
}

.subtitle {
    margin-top: 20px;
    color: #bbb;
    font-size: 16px;
}

button {
    margin-top: 40px;
    padding: 15px 30px;
    border: 1px solid #555;
    border-radius: 50px;
    background: rgba(255,255,255,0.05);
    color: white;
    font-size: 15px;
    cursor: pointer;
    transition: 0.3s;
}

button:hover {
    background: #fff;
    color: #111;
    transform: scale(1.05);
}

/* ---------- STORY ---------- */

#story {
    background: #0e0e14;
    flex-direction: column;
    text-align: center;
}

.label {
    color: #ff8fa3;
    letter-spacing: 3px;
    font-size: 12px;
    margin-bottom: 15px;
}

.story-title {
    font-size: 38px;
    font-weight: 300;
    margin-bottom: 50px;
}

.timeline {
    max-width: 600px;
    width: 100%;
    text-align: left;
}

.event {
    border-left: 1px solid #555;
    padding: 0 0 40px 25px;
    position: relative;
}

.event::before {
    content: "♡";
    position: absolute;
    left: -10px;
    top: 0;
    color: #ff8fa3;
    background: #0e0e14;
    font-size: 18px;
}

.event h3 {
    font-size: 18px;
    font-weight: 500;
}

.event p {
    margin-top: 8px;
    color: #999;
    line-height: 1.7;
}

/* ---------- LETTER ---------- */

#letter {
    background:
        radial-gradient(circle at center, #241820, #09090d 65%);
    flex-direction: column;
    text-align: center;
}

.letter-box {
    max-width: 650px;
    padding: 35px;
    border: 1px solid #333;
    border-radius: 25px;
    background: rgba(255,255,255,0.03);
    backdrop-filter: blur(10px);
}

.letter-box h2 {
    font-size: 30px;
    font-weight: 300;
    margin-bottom: 25px;
}

.letter-box p {
    color: #ccc;
    line-height: 2;
    font-size: 16px;
}

/* ---------- SECRET ---------- */

#secret {
    background: #08080c;
    flex-direction: column;
    text-align: center;
}

.secret-text {
    display: none;
    max-width: 600px;
    margin-top: 30px;
    animation: fade 1s ease;
}

.secret-text h2 {
    font-size: 32px;
    font-weight: 300;
    color: #ff9aae;
}

.secret-text p {
    margin-top: 20px;
    color: #ccc;
    line-height: 2;
}

@keyframes fade {
    from {
        opacity: 0;
        transform: translateY(20px);
    }

    to {
        opacity: 1;
        transform: translateY(0);
    }
}

/* ---------- HEARTS ---------- */

.heart {
    position: fixed;
    pointer-events: none;
    animation: float 5s linear forwards;
    opacity: 0.8;
}

@keyframes float {
    from {
        transform: translateY(0);
        opacity: 0;
    }

    20% {
        opacity: 0.8;
    }

    to {
        transform: translateY(-100vh);
        opacity: 0;
    }
}

footer {
    padding: 40px;
    text-align: center;
    color: #555;
    background: #08080c;
}
</style>
</head>

<body>

<!-- OPENING -->

<section id="opening">

    <div>

        <div class="small">
            SOMETHING I MADE FOR YOU
        </div>

        <h1>
            2 Months<br>
            <span>With You ♡</span>
        </h1>

        <p class="subtitle">
            มีบางอย่างที่ผมอยากให้คุณรู้...
        </p>

        <button onclick="openStory()">
            OPEN ♡
        </button>

    </div>

</section>


<!-- STORY -->

<section id="story">

    <div class="label">
        OUR STORY
    </div>

    <div class="story-title">
        เรื่องราวเล็ก ๆ ของเรา
    </div>

    <div class="timeline">

        <div class="event">
            <h3>วันที่เราได้รู้จักกัน</h3>
            <p>
                วันธรรมดาวันหนึ่งที่ผมไม่รู้เลยว่า
                มันจะกลายเป็นจุดเริ่มต้นของเรื่องราวของเรา
            </p>
        </div>

        <div class="event">
            <h3>วันที่เราเริ่มสนิทกัน</h3>
            <p>
                จากคนที่ไม่รู้จักกัน
                กลายเป็นคนที่ผมอยากคุยด้วยมากขึ้นเรื่อย ๆ
            </p>
        </div>

        <div class="event">
            <h3>วันที่เราเป็นแฟนกัน ♡</h3>
            <p>
                และวันหนึ่งคุณก็กลายเป็น
                “คุณแฟน” ของผมจริง ๆ
            </p>
        </div>

        <div class="event">
            <h3>วันนี้ — 2 เดือน</h3>
            <p>
                เวลาสองเดือนอาจดูไม่นาน
                แต่สำหรับผม มันมีความหมายมากกว่าตัวเลข
            </p>
        </div>

    </div>

</section>


<!-- LETTER -->

<section id="letter">

    <div class="label">
        A LETTER FOR YOU
    </div>

    <div class="letter-box">

        <h2>ถึงคุณแฟน ♡</h2>

        <p>
            สุขสันต์ครบรอบ 2 เดือนนะคุณ
            <br><br>

            ขอบคุณที่เข้ามาเป็นส่วนหนึ่งในชีวิตของผม
            ขอบคุณสำหรับทุกบทสนทนา
            ทุกความเข้าใจ และทุกช่วงเวลาที่เราได้มีให้กัน
            <br><br>

            ผมไม่รู้ว่าอนาคตของเราจะเป็นอย่างไร
            แต่ตอนนี้ผมดีใจที่มีคุณอยู่ตรงนี้
            และผมอยากใช้เวลาที่มีอยู่กับคุณให้ดีที่สุด
            <br><br>

            ขอบคุณที่เป็นคุณนะ
            <br><br>

            — จากผม ♡
        </p>

    </div>

</section>


<!-- SECRET -->

<section id="secret">

    <div class="label">
        ONE LAST THING
    </div>

    <h2>
        คุณคิดว่าหมดแล้วเหรอ?
    </h2>

    <button onclick="showSecret()">
        ยังมีอีกอย่าง ♡
    </button>

    <div class="secret-text" id="secretText">

        <h2>
            I LOVE YOU ♡
        </h2>

        <p>
            สุขสันต์ครบรอบ 2 เดือนนะครับคุณแฟน
            <br><br>
            ถึงเราจะอยู่ไกลกัน
            แต่ผมก็ยังดีใจที่ได้มีคุณอยู่ในชีวิต
            <br><br>
            อยู่ด้วยกันไปนาน ๆ นะ
            🤍
        </p>

    </div>

</section>


<footer>
    Made with love ♡
    <br>
    2 Months With You
</footer>


<script>

function openStory() {

    document.getElementById("story")
        .scrollIntoView({
            behavior: "smooth"
        });

    createHearts(15);
}


function showSecret() {

    const secret =
        document.getElementById("secretText");

    secret.style.display = "block";

    createHearts(30);
}


function createHearts(amount) {

    for (let i = 0; i < amount; i++) {

        const heart =
            document.createElement("div");

        heart.className = "heart";
        heart.innerHTML = "♡";

        heart.style.left =
            Math.random() * 100 + "vw";

        heart.style.bottom = "-20px";

        heart.style.fontSize =
            (12 + Math.random() * 20) + "px";

        heart.style.animationDuration =
            (3 + Math.random() * 4) + "s";

        document.body.appendChild(heart);

        setTimeout(() => {
            heart.remove();
        }, 7000);
    }
}

</script>

</body>
</html>