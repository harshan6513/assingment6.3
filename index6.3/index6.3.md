
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Assignment 6.3 - Overflow</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Assignment 6.3</h1>
    <p>Overflow & Layout Fixing</p>
  </header>

  <main>
    <h2>1. Overflow Examples</h2>

    <section class="examples">
      <article>
        <h3>Overflow: Visible</h3>
        <div class="box visible">
          This is a long paragraph demonstrating visible overflow.
          The extra content extends outside the fixed-height container.
          More content is added to show the overflow behavior clearly.
        </div>
      </article>

      <article>
        <h3>Overflow: Hidden</h3>
        <div class="box hidden">
          This is a long paragraph demonstrating hidden overflow.
          The extra content is clipped and cannot be seen outside
          the fixed-height container.
        </div>
      </article>

      <article>
        <h3>Overflow: Auto</h3>
        <div class="box auto">
          This is a long paragraph demonstrating auto overflow.
          When the content exceeds the fixed height, a scrollbar
          appears so the user can read the remaining text.
          Keep scrolling to see this extra content.
        </div>
      </article>

      <article>
        <h3>Overflow: Scroll</h3>
        <div class="box scroll">
          This is a long paragraph demonstrating scroll overflow.
          A scrollbar is provided so the user can move through
          the content inside this fixed-height container.
          This is additional content for testing.
        </div>
      </article>
    </section>

    <h2>2. Separate Scrollable Content</h2>
    <div class="reading-box">
      <h3>College Notice</h3>
      <p>Welcome to the college notice section.</p>
      <p>Notice 1: Check your class timetable regularly.</p>
      <p>Notice 2: Complete all assignments before the deadline.</p>
      <p>Notice 3: Attend practical classes on time.</p>
      <p>Notice 4: Keep your notes organised.</p>
      <p>Notice 5: Check the examination schedule carefully.</p>
      <p>Notice 6: Contact your teacher if you need help.</p>
      <p>Notice 7: Keep your student identity card with you.</p>
      <p>Notice 8: Follow the college laboratory rules.</p>
    </div>

    <h2>3. Fixed Layout — Overflow Issue Solved</h2>
    <div class="fixed-layout">
      <div class="layout-card">
        <h3>Fixed Layout</h3>
        <p>
          This content stays inside its parent container.
          Long words and text wrap instead of breaking the layout.
        </p>
        <p class="long-text">
          ExtraContentForTestingLongTextOverflowAndLayoutFixing
        </p>
      </div>
    </div>
  </main>

  <footer>
    <p>Web Development Assignment 6.3</p>
  </footer>
</body>
</html>
