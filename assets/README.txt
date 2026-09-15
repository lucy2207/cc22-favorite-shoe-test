Put your 16 colorway images in this folder.
 
By default index.html expects these filenames (see the COLORWAYS array
near the top of the <script> tag):
 
  colorway-01.jpg
  colorway-02.jpg
  colorway-03.png
  colorway-04.jpg
  colorway-05.webp
  colorway-06.jpg
  colorway-07.png
  colorway-08.jpg
  colorway-09.jpg
  colorway-10.webp
  colorway-11.jpg
  colorway-12.png
  colorway-13.jpg
  colorway-14.jpg
  colorway-15.png
  colorway-16.jpg
 
Mixing .jpg / .png / .webp is fine — the <img> tag doesn't care about
file extension, it just needs to point at the right filename.
 
Two ways to use your real files:
 
1. Rename your images to match the list above, OR
2. Open index.html, find the COLORWAYS array, and edit each "file"
   value (and "name" value, if you want a real colorway name shown
   on screen) to match whatever your files are actually called.
 
If a filename is wrong or missing, that card will show a small
"Image not found" placeholder instead of breaking the page, so it's
easy to spot typos while you're setting things up.

===========================================================
HOW TO USE THE APP ONCE YOUR IMAGES ARE IN PLACE
===========================================================
 
1. Make sure the folder layout looks like this:
 
     caitlin-clark-bracket/
     ├── index.html
     └── assets/
         ├── black.jpg
         ├── bracelet.jpeg
         ├── ... (all 16 images)
 
   The images MUST stay inside the "assets" folder, sitting next
   to index.html (not inside index.html's own folder structure
   moved around) — index.html looks for them at "assets/<filename>".
 
2. Double-click index.html (or right-click → Open with → your
   browser). It'll open as a local file — no server, install, or
   internet connection needed (aside from loading the two Google
   Fonts on first load).
 
3. Click "Play" to start the bracket, then keep tapping the
   colorway you prefer in each match-up until a champion is
   crowned. Click "Play again" to reshuffle and run it again —
   the order is randomized fresh every time.
 
4. To share it with someone else, just zip the whole
   caitlin-clark-bracket folder (index.html + assets) and send
   it — they open index.html the same way, no setup required.
 
5. If you ever want to host it online instead of opening the file
   locally (e.g. so you can send a link), you can drag the whole
   folder into a static host like Netlify Drop, GitHub Pages, or
   Vercel — no code changes needed.
