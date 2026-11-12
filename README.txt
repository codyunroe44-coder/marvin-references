MARVIN CHARACTER REFERENCE PACK
================================
These are the lead solo reference images for Marvin's characters, renamed
to the exact filenames bot.py expects:

  marvin.jpg        (Marvin, ref-14)
  luca.jpg          (Luca, ref-27 robe solo)
  lucas.jpg         (Lucas, ref-02)
  timmy.jpg         (Timmy, ref-03)
  ryland.jpg        (Ryland, ref-04)
  nolan.jpg         (Nolan, ref-05)
  tyler.jpg         (Tyler, ref-07)
  cole.jpg          (Cole, ref-09)
  logan.jpg         (Logan, ref-10)
  kieran.jpg        (Lord Kieran, ref-12)
  fire_phoenix.jpg  (Fire Phoenix, ref-13)
  kid_lightning.jpg (Kid Lightning, ref-19)
  colin.jpg         (Colin Scorpio, ref-20)
  kid_omen.jpg      (Kid Omen, ref-21)
  general_near.jpg  (General Near, ref-22)

HOW TO USE
1. Upload all 15 .jpg files to one folder on any host that gives direct
   image links (each file's URL must end in its filename, e.g.
   https://your-host/references/marvin.jpg).
2. In Railway, add an environment variable:
     REFERENCES_BASE_URL = https://your-host/references
   (the folder URL, no trailing slash needed)
3. Restart the bot. When a !imagine prompt names a character, Marvin
   fetches that character's reference and generates from it automatically.
