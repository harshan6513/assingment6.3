
* {
  box-sizing: border-box;
}

body {
  margin: 0;
  font-family: Arial, sans-serif;
  background: #f3f6fb;
  color: #243047;
  line-height: 1.6;
}

header {
  background: #243b64;
  color: white;
  text-align: center;
  padding: 24px 16px;
}

header h1 {
  margin: 0;
}

main {
  width: 100%;
  max-width: 1100px;
  margin: 24px auto;
  padding: 0 18px;
}

h2 {
  margin-top: 30px;
  color: #243b64;
}

.examples {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 24px;
}

.examples article {
  min-width: 0;
}

.box {
  height: 120px;
  padding: 12px;
  border: 2px solid #7890b5;
  border-radius: 8px;
  background: white;
}

.visible {
  overflow: visible;
  background: #e4efff;
}

.hidden {
  overflow: hidden;
  background: #ffe8e8;
}

.auto {
  overflow: auto;
  background: #e5f8eb;
}

.scroll {
  overflow: scroll;
  background: #fff1d9;
}

.reading-box {
  height: 180px;
  max-width: 650px;
  padding: 16px;
  overflow: auto;
  border: 2px solid #4d6fa9;
  border-radius: 10px;
  background: white;
}

.reading-box h3 {
  margin-top: 0;
}

.fixed-layout {
  width: 100%;
  max-width: 650px;
  padding: 16px;
  border: 2px solid #b6c5dc;
  border-radius: 10px;
  background: white;
}

.layout-card {
  min-width: 0;
  overflow-wrap: anywhere;
}

.long-text {
  overflow-wrap: anywhere;
  background: #e5f8eb;
  padding: 10px;
}

footer {
  margin-top: 32px;
  padding: 16px;
  background: #243b64;
  color: white;
  text-align: center;
}

@media (max-width: 650px) {
  .examples {
    grid-template-columns: 1fr;
  }
}
