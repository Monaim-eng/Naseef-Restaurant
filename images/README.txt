NASEEF RESTAURANT WEBSITE - IMAGES FOLDER
==========================================

Drop your photos into this folder using these EXACT filenames.
The website automatically picks them up — no code editing needed.

HOMEPAGE (index.html):

  hero.jpg        Full-width banner behind the homepage headline.
                  Recommended: landscape, at least 1920x1080px.
                  Best pick: the waterfront terrace / sunset shot.

  about.jpg       Portrait photo next to the "Our Story" text.
                  Recommended: portrait, around 1000x1250px.

  tanoor.jpg      Landscape photo for the "From Our Tanoor" section.
                  Recommended: landscape, around 1600x1000px.

  gallery-1.jpg   Sea view terrace
  gallery-2.jpg   Naseef signage & entrance
  gallery-3.jpg   Indoor seating & greenery
  gallery-4.jpg   Mixed grill platter
  gallery-5.jpg   Breakfast spread
  gallery-6.jpg   Outdoor waterfront seating
                  Recommended: square, at least 800x800px each.
                  (These 6 also appear on the homepage preview.)

CATERING PAGE (catering.html):

  catering.jpg    Banner photo behind the "Catering Services" heading.
                  Recommended: landscape, at least 1920x1080px.
                  A spread/platter shot works well here.

  catering-1.jpg  through  catering-8.jpg
                  Photos in the "Catering in Action" grid further down the
                  page (past setups, trays, events). Just add files named
                  catering-1.jpg, catering-2.jpg, etc. — no code editing
                  needed for photos #1-8. Click any to view full-size.
                  Recommended: square-ish, at least 800x800px each.

                  Want more than 8? Add catering-9.jpg, catering-10.jpg, etc.,
                  then open catering.html, find the line:
                      const TOTAL_CATERING_PHOTOS = 8;
                  and change 8 to your new total.

FULL GALLERY PAGE (gallery.html):

  gallery-1.jpg  through  gallery-30.jpg
                  The full gallery page auto-builds itself from this numbered
                  sequence — just add files named gallery-1.jpg, gallery-2.jpg,
                  gallery-3.jpg, and so on. No code editing needed for photos
                  #1-30. (gallery-1 through gallery-6 also show as the 6-photo
                  preview on the homepage.)
                  Recommended: square-ish, at least 800x800px each.
                  Click any photo on the gallery page to open it full-size,
                  with arrow-key/swipe navigation between them.

  Want MORE than 30 photos? Add gallery-31.jpg, gallery-32.jpg, etc.,
  then open gallery.html, find the line:
      const TOTAL_PHOTOS = 30;
  and change 30 to your new total. That's the only edit needed.

NOTES:
- File names are case-sensitive on some systems — keep them lowercase exactly as above.
- .jpg is expected. If you use .png or .jpeg instead, rename the file
  or update the matching "url('images/...')" line in style.css.
- If a file is missing, that section just shows a plain color background
  instead of breaking — safe to add photos gradually.
