# my-digital-card
My Digital Card is a training project focused on designing a modern, responsive website for creating and sharing digital visiting cards. It helps users showcase their contact details and profiles in a clean, mobile-friendly format.

1. Inline CSS[N] | Embed[N] | External CSS (Y) (Link)
2. class (.) (selector) - style | id (selector) - avoid (#) - for styling
3. sementic - header, main, footer, section, nav (div / span)
4. h1...........h6
5. Box Modal
6. Final Rules for CSS Writing 


/* 🔤 Typography */
color: black;
font-size: 16px;
font-family: Arial, sans-serif;
font-weight: normal | bold | 400 | 700;
text-align: left | center | right;
text-decoration: none | underline;
text-transform: none | uppercase | capitalize;
line-height: 1.5;
letter-spacing: 1px;

/* 📦 Box Model & Sizing */
width: 100% | auto;
height: auto | 100vh;
min-width: 200px;
min-height: 100px;
max-width: 1200px;
margin: 0 | 10px | 0 auto;
padding: 10px;
border: 1px solid #ccc;
border-radius: 5px;
box-sizing: border-box;
overflow: visible | hidden | auto;

/* 🎨 Background & Visuals */
background-color: #f0f0f0;
background-image: url("img.jpg");
background-size: cover | contain;
background-repeat: no-repeat;
background-position: center;
box-shadow: 0 4px 8px rgba(0,0,0,0.1);
opacity: 1 | 0.5;
filter: blur(4px) | grayscale(100%);
backdrop-filter: blur(10px);

/* 📍 Layout & Positioning */
display: block | inline | flex | grid | none;
position: static | relative | absolute | fixed | sticky;
top: 0; left: 0; right: 0; bottom: 0;
z-index: 1;
inset: 0; /* shorthand for top/right/bottom/left */

/* 🧭 Flexbox */
display: flex;
flex-direction: row | column;
justify-content: center | space-between;
align-items: center | stretch;
flex-wrap: wrap;
gap: 10px;

/* 🧮 Grid */
display: grid;
grid-template-columns: 1fr 1fr | repeat(3, 1fr);
grid-template-rows: auto;
gap: 20px;

/* 🎯 Interactivity & States */
cursor: pointer;
pointer-events: auto | none;
user-select: none;
:hover { background-color: #eee; }
:focus { outline: 2px solid blue; }
:active { transform: scale(0.98); }

/* 🔁 Transitions & Animations */
transition: all 0.3s ease;
transform: scale(1.1) | rotate(5deg);
@keyframes fadeIn {
  from { opacity: 0; }
  to { opacity: 1; }
}
animation: fadeIn 1s ease-in-out;

/* 🧠 Variables & Utility */
:root {
  --main-color: #3498db;
}
color: var(--main-color);

/* 📱 Responsive Design */
@media (max-width: 768px) {
  font-size: 14px;
  flex-direction: column;
  padding: 20px;
}