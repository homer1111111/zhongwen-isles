# 中文群岛 · Zhongwen Isles

**《中文》课文冒险 — An adventure through the 《中文》 textbook**

A companion to the 《中文》 learning app: an Animal Crossing–style 3D island game for children learning Chinese
with the Jinan University 《中文》 textbook series, Books 1–5.

- Five islands, one for each book, joined by a ferry; 60 lessons.
- Each lesson: the island neighbours perform the original text, then a play built around it, a letter, and two
  questions.
- Every character has pinyin; every line can be heard; English mode is on by default.
- Several children can share one device, each with their own save; a returning player lands on the island they
  last left.

## Play

Open `index.html` in a modern browser, or visit this repository's GitHub Pages site.
Works on phones and tablets (touch) and on desktop.

## Notes

- One self-contained file. Libraries (three.js r128, GSAP 3.12.5) and fonts load from public CDNs.
- Progress is saved in the browser's local storage for this site.
- Speech uses the device's built-in Chinese voice; a device without one plays silently.
- Graphics quality adapts to the device; force it with `?q=low`, `?q=mid` or `?q=high`.
