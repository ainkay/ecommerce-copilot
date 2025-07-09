✅ Prompt Log Entry 1
Prompt:
“How can I use Flexbox to center text and a button in a hero section?”

AI Response Summary:
Recommended using display: flex; flex-direction: column; justify-content: center; align-items: center; text-align: center; height: 100vh; to center the hero content both vertically and horizontally in a column layout.

My Implementation:
Added display: flex and set flex-direction to column for stacking. Used align-items and justify-content to perfectly center the text and button. Set height: 100vh to fill the viewport.

Reflection:
This helped me understand how powerful Flexbox is for centering. It made the hero section look balanced and professional on all screen sizes.

✅ Prompt Log Entry 2
Prompt:
“How do I make my header navigation stay fixed at the top when scrolling?”

AI Response Summary:
Explained that using position: fixed; top: 0; left: 0; right: 0; would pin the header to the top, with z-index to layer it above content, and adding a subtle box-shadow for depth.

My Implementation:
Applied position: fixed to the header, set top: 0, left: 0, right: 0 to stretch it across the viewport, and added box-shadow for a subtle effect. Increased z-index to avoid content overlap.

Reflection:
Prompt was really helpful. I learned about sticky headers and also remembered to add extra top padding in body so content doesn’t hide behind the header.

✅ Prompt Log Entry 3
Prompt:
“What’s the best way to create responsive product cards using CSS Grid?”

AI Response Summary:
Suggested using display: grid on the container with grid-template-columns: repeat(auto-fill, minmax(200px, 1fr)); to make columns adapt to screen size. Recommended using gap for spacing.

My Implementation:
Used display: grid and the auto-fill pattern to automatically fit as many product cards as possible. Added gap: 16px to space them evenly. Each .product-card has padding and border-radius for a clean look.

Reflection:
Prompt gave me a clear solution for responsive layouts. I now prefer CSS Grid for cards because it saves me writing lots of media queries.

✅ Prompt Log Entry 4
Prompt:
“How can I style my ‘Shop Now’ button to look more modern and clickable?”

AI Response Summary:
Recommended using a bold background color with white text, rounded corners, padding, cursor pointer, and a hover effect with transition for smooth color changes.

My Implementation:
Styled all button elements with a green background, white text, border-radius, and padding. Added cursor: pointer and transition: background-color 0.3s. On :hover, the green darkens slightly.

Reflection:
This made my buttons stand out more. The hover effect feels professional and makes the CTA more attractive.

✅ Prompt Log Entry 5
Prompt:
“How do I ensure my footer is always at the bottom of the page?”

AI Response Summary:
Explained how to use CSS to keep the footer at the bottom using position: relative; bottom: 0; left: 0; right: 0; and suggested ensuring enough content height or using flex layouts for sticky footers.

My Implementation:
Used position: relative with bottom: 0; left: 0; right: 0; and added background color and padding for clear visibility. Verified that it stays at the bottom when content is short.

Reflection:
Prompt taught me there are multiple ways to do sticky footers. For longer pages, it works fine; for short pages, a flex column layout might be even better.