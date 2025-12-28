# QR Code Generator Website

A simple web application that generates a QR code from user-entered text.
When the generated QR code is scanned using any QR scanner, it displays the same message entered by the user.

---

## Live Demo

* Netlify (Primary Deployment):
  [https://qrgen14.netlify.app](https://qrgen14.netlify.app)

* GitHub Pages:
  [https://ashwin-arch.github.io/qr-generator/](https://ashwin-arch.github.io/qr-generator/)

---

## Project Concept

QR (Quick Response) codes are used to store and transfer information quickly. They can store:

* Plain text
* URLs
* Contact details
* Other small data payloads

In this project:

* The text typed by the user is embedded directly into the QR code
* No backend server or database is required
* The QR code works offline once generated

---

## Technologies Used

* HTML5 – Structure of the webpage
* CSS3 – Styling and layout
* JavaScript – Logic for generating QR codes
* QRCode.js – JavaScript library used to generate QR codes

---

## Project Structure

```
qr-generator/
│
├── index.html     # Main website file
├── .gitignore     # Git ignored files
└── README.md      # Project documentation
```

---

## How the Application Works

1. The user enters a message in the input field
2. On clicking **Generate QR**, JavaScript reads the input text
3. The QRCode.js library converts the text into a QR code
4. The QR code is displayed on the webpage
5. Scanning the QR code shows the original message

---

## Deployment Methods Used

### Netlify Deployment

* Deployed using Netlify
* Automatically rebuilds on new commits
* Faster and recommended for production use

### GitHub Pages Deployment

* Hosted directly from the GitHub repository
* Uses the `main` branch and root folder
* Suitable for static websites

---

## How to Run Locally

1. Clone the repository:

   ```bash
   git clone https://github.com/Ashwin-arch/qr-generator.git
   ```

2. Navigate to the project folder:

   ```bash
   cd qr-generator
   ```

3. Open the project in a browser:

   ```bash
   firefox index.html
   ```

---

## GitHub CLI Workflow Used

```bash
git init
git add .
git commit -m "Initial QR code generator website"
gh repo create qr-generator --public
git push -u origin main
```

---

## Key Features

* Works completely offline
* No backend required
* Mobile-friendly QR scanning
* Lightweight and fast
* Beginner-friendly implementation

---

## Future Enhancements

* Download QR code as an image
* Password-protected QR codes
* Dynamic QR codes using backend
* Custom QR colors and logos
* Convert into a Progressive Web App (PWA)

---

## Author

Ashwin Kumar G Rao
Computer Science & Engineering
GitHub: [https://github.com/Ashwin-arch](https://github.com/Ashwin-arch)

---

## License

This project is open-source and free to use for learning and educational purposes.
