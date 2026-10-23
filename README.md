# CSCI 3330 Lab #6 — EJS

## Run in VS Code (Windows)
1. Extract this ZIP file.
2. In VS Code, choose **File → Open Folder** and open `3330-lab-16-ejs-main`.
3. Open **Terminal → New Terminal**. Make sure the terminal is in this folder (the one containing `index.js` and `package.json`).
4. Check that Node.js and npm are installed by running `node -v` and `npm -v`.
5. Run `npm install`.
6. Run `npm start`.
7. Open `http://localhost:3000` in your browser. Test Home, About, and Contact.
8. To stop the server, click the terminal and press **Ctrl+C**.

If `node` or `npm` is not recognized, Node.js needs to be installed or made available on the computer.

## Routes
- `/` — EJS home page with dynamic username.
- `/about` — About page.
- `/contact` — Contact page.

The starter HTML files and CSS are retained. The new EJS views and shared header/footer partials are in `views/`.
