# Grammaire avec Haresh Sir – online grammar test

Six online grammar pages for ICSE Grade 10: the slip tests (Set A, B, C) and three grammar practice sets (Set D, E, F).
Students type their name, answer, see every mistake explained, and send their result to the teacher
(PDF share to WhatsApp or Gmail, or an automatic email if you switch it on).

## Files
- `index.html` – the page students open first. It links to the three sets.
- `setA.html`, `setB.html`, `setC.html` – the tests.
- `config.js` – your email, your WhatsApp number and the optional automatic email key.

## Put it online with GitHub Pages (about 5 minutes, no coding)
1. Sign in at github.com and click **New repository**. Name it `Slip Test 1_Group 1_Grammar` (GitHub will change the spaces to hyphens, so the name becomes `Slip-Test-1_Group-1_Grammar`). Choose **Public** (free GitHub Pages needs Public). Click **Create repository**.
2. Click **uploading an existing file**. Drag in `index.html`, `setA.html`, `setB.html`, `setC.html` and `config.js`. Click **Commit changes**.
3. Open **Settings → Pages**. Under **Branch**, choose `main` and `/ (root)`. Click **Save**.
4. After a minute the page shows your link: `https://haresh1974.github.io/Slip-Test-1_Group-1_Grammar/`
   Send that link to the students. The direct links are the same address followed by `setA.html`, `setB.html` or `setC.html`.

## Set up how results reach you (`config.js`)
Open `config.js` on GitHub, click the pencil icon, change the values and click **Commit changes**.
- `teacherEmail` – already set. The "Send an email" button opens the student's email app addressed to you.
- `teacherWhatsApp` – already set to `919579627052` (+91 9579627052). Then "Send a message on WhatsApp" opens a chat with you. If you ever want students to choose the contact themselves, empty the quotes.
- `web3formsKey` – optional. For an automatic email with no student action: go to web3forms.com, type your email address, copy the access key they send you and paste it between the quotes. Then a "Send to my teacher" button appears on the result page. Check their site for the current free limit.

## Good to know
- The **Share my result (PDF)** button works best on phones. It opens the phone's share sheet, and the PDF is attached automatically in WhatsApp or Gmail. On a computer it saves the PDF instead.
- Answers are inside the page files, so a student who knows how to view the page source could find them. This is fine for practice. Use the printed paper for formal marks.
- The Word question papers and answer keys are not in this folder, on purpose, so they are not public.
