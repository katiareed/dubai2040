# Dubai 2040 Career Card Builder

A free web tool for the NAIS AI Literacy Foundation unit *Dubai 2040: Build Your Future Team*. Students build a printable career card with their AI-generated minifigure, stats out of 10 and a four-step learning pathway. The teacher turns the submitted cards into a print sheet (nine cards per A4 page, with card backs) for the class board game.

Everything runs in the student's browser. Nothing is uploaded to a server, there are no logins, and no student data is collected.

## What Is in This Folder

1. `index.html`: the Career Card Builder.
2. `vendor/`: two small helper libraries the page needs (html2canvas makes the card picture, jsPDF makes the print sheet). They are stored here so the page works even if a school network blocks outside script sites.
3. `favicon.svg`: the browser tab icon.
4. `THIRD-PARTY-LICENSES.txt`: licences for the two libraries (both MIT, free to use).
5. `README.md`: this guide.

## How to Publish on GitHub Pages (No Coding Needed)

1. Sign in at github.com.
2. Click the **+** at the top right and choose **New repository**.
3. Name it (this one is `dubai2040`), choose **Public**, and click **Create repository**.
4. On the new page, click the link **uploading an existing file**.
5. Unzip the pack on your computer. Open the `dubai-2040-career-cards` folder, select everything inside it (including the `vendor` folder) and drag it into the GitHub upload box. Use Chrome or Edge, which upload folders correctly.
6. Check that the list shows `index.html` and `vendor/html2canvas.min.js`. Click **Commit changes**.
7. Go to **Settings**, then **Pages** in the left menu.
8. Under **Build and deployment**, set **Source** to **Deploy from a branch**, choose the branch **main** and the folder **/ (root)**, then click **Save**.
9. Wait one to two minutes and refresh the Pages screen. Your link appears at the top:
   https://katiareed.github.io/dubai2040/

## Live Links

1. **Students:** https://katiareed.github.io/dubai2040/
2. **Teacher print sheet:** https://katiareed.github.io/dubai2040/#sheet (opens the Print Sheet tab directly).

Post the student link on Schoology or as a QR code on the lesson slide.

## How Students Use It

1. Fill in the six steps: character, picture, stats, learning pathway, AI and me, fact-check.
2. Add the AI image: Upload image, drag it in, or copy it and press Ctrl+V (Cmd+V on Mac).
3. Press **Get my card image**.
4. Press **Download PNG**, or **Copy image** and paste it into the Schoology assignment. On an iPad, press and hold the card and choose Save to Photos.

Work is saved in that browser only. Students should download their card before closing the page or switching device.

## How the Teacher Makes the Print Sheet

1. Download the students' PNG cards from Schoology into one folder.
2. Open the teacher link and click **Upload card PNGs**. Select many files at once.
3. Tick **Add a page of card backs** if you will print double-sided.
4. Click **Download print sheet (PDF)**.
5. Print at **100% / Actual size** (not "Fit to page") on A4 card, 250 to 300 gsm. Cut along the light grey lines. Cards are 63 x 88 mm, standard playing-card size.

For double-sided printing, choose **Flip on long edge**. The backs page is mirrored so each back lines up with its card.

## Updating the Tool Later

1. In the repository, click `index.html`, then the pencil icon (or **Add file** and **Upload files** to replace it).
2. Click **Commit changes**. The live site updates within a minute or two.

## Troubleshooting

1. **The page shows "404".** Wait two minutes after turning on Pages, and check that `index.html` is in the main folder of the repository, not inside another folder.
2. **"The image tool did not load".** The `vendor` folder is missing or was uploaded to the wrong place. Upload it again so the path reads `vendor/html2canvas.min.js`.
3. **The fonts look plain.** The school network blocks Google Fonts. The tool still works with the system font.
4. **The card shows the example (Noor).** That is the example card. Students press **Start a blank card**, or simply type over each field.
5. **A student lost their card.** Their work is saved in the browser they used. Ask them to open the same link on the same device and browser.

## Credits

Created by Ms Katia Reed for North American International School, Dubai. AI Literacy Foundation, Grades 9, 10 and 12. Linked to the UAE MoE AI Curriculum (D3 Software Use, D4 Ethical Awareness, D5 Real-World Applications).
