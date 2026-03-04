<!doctype html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Secret Code Reveal</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <main class="app">
      <section class="card lock-card" id="lockCard">
        <p class="kicker">Enter secret code</p>
        <h1>Type the code to unlock</h1>
        <form id="codeForm" autocomplete="off">
          <input
            id="codeInput"
            class="code-input"
            type="password"
            inputmode="text"
            placeholder="••••"
            maxlength="12"
            aria-label="Secret code"
            required
          />
          <button type="submit">Unlock</button>
        </form>
        <p id="hint" class="hint">Hint: it starts with o</p>
        <p id="error" class="error" aria-live="polite"></p>
      </section>

      <section class="card reveal-card hidden" id="revealCard" aria-live="polite">
        <p class="kicker">Unlocked</p>
        <h2>I Thought I Saw Your Face Today</h2>
        <p class="subtitle">by SheandHimOfficial</p>
        <p class="message">You opened this little secret moment ✨</p>
        <button id="playBtn">Play Music</button>
        <audio id="song" preload="none" src="assets/i-thought-i-saw-your-face-today.mp3"></audio>
        <p class="footnote">
          Add your licensed audio file at
          <code>assets/i-thought-i-saw-your-face-today.mp3</code> to enable playback.
        </p>
      </section>
    </main>

    <script src="script.js"></script>
  </body>
</html>

:root {
  --bg: #0f1020;
  --card: #191b2f;
  --text: #f5f6ff;
  --muted: #b7bbdf;
  --accent: #8f7cff;
  --danger: #ff7a91;
}

* {
  box-sizing: border-box;
}

body {
  margin: 0;
  min-height: 100vh;
  display: grid;
  place-items: center;
  background: radial-gradient(circle at top, #23264d, var(--bg) 55%);
  color: var(--text);
  font-family: "Segoe UI", system-ui, -apple-system, sans-serif;
}

.app {
  width: min(92vw, 460px);
}

.card {
  background: linear-gradient(155deg, #20244a, var(--card));
  border: 1px solid #31345b;
  border-radius: 20px;
  padding: 1.4rem;
  box-shadow: 0 20px 40px rgba(0, 0, 0, 0.35);
}

.kicker {
  margin: 0;
  color: var(--muted);
  text-transform: uppercase;
  letter-spacing: 0.12em;
  font-size: 0.72rem;
}

h1,
h2 {
  margin: 0.45rem 0 1rem;
  line-height: 1.2;
}

form {
  display: grid;
  gap: 0.75rem;
}

.code-input,
button {
  width: 100%;
  border-radius: 12px;
  border: 1px solid #424677;
  background: #11132a;
  color: var(--text);
  padding: 0.85rem 1rem;
  font-size: 1rem;
}

button {
  border: 0;
  background: linear-gradient(90deg, var(--accent), #6070ff);
  font-weight: 600;
  cursor: pointer;
}

button:hover {
  filter: brightness(1.06);
}

.hint,
.subtitle,
.footnote {
  color: var(--muted);
  margin-bottom: 0;
}

.error {
  color: var(--danger);
  min-height: 1.2rem;
}

.hidden {
  display: none;
}

.message {
  margin-top: 0.35rem;
}

code {
  background: rgba(255, 255, 255, 0.08);
  border-radius: 6px;
  padding: 0.12rem 0.35rem;
}

const SECRET_CODE = "open";

const codeForm = document.getElementById("codeForm");
const codeInput = document.getElementById("codeInput");
const error = document.getElementById("error");
const lockCard = document.getElementById("lockCard");
const revealCard = document.getElementById("revealCard");
const playBtn = document.getElementById("playBtn");
const song = document.getElementById("song");

codeForm.addEventListener("submit", (event) => {
  event.preventDefault();

  if (codeInput.value.trim().toLowerCase() !== SECRET_CODE) {
    error.textContent = "Wrong code. Try again.";
    codeInput.select();
    return;
  }

  error.textContent = "";
  lockCard.classList.add("hidden");
  revealCard.classList.remove("hidden");
});

playBtn.addEventListener("click", async () => {
  try {
    await song.play();
    playBtn.textContent = "Playing…";
  } catch {
    playBtn.textContent = "Audio unavailable";
  }
});
