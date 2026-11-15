# Sriram S G — AI/ML + Robotics Portfolio

A dependency-free static portfolio built with HTML, CSS and JavaScript. It includes an AI/ML portfolio, robotics-themed visual section, projects, skills, certificates, experience and contact links.

## Folder structure

```text
Ram-19goat.github.io/
├── index.html
├── README.md
├── .nojekyll
└── public/
    ├── profile.jpg
    ├── resume.pdf
    └── certificates/
        ├── nvidia-introduction-to-networking.pdf
        ├── iisc-fundamentals-of-sensors.pdf
        ├── uzh-intro-to-probability.pdf
        ├── google-cloud-generative-ai.pdf
        ├── meta-mysql.pdf
        └── ibm-intro-to-ai.pdf
```

## Run locally

Open `index.html` directly, or run `python3 -m http.server 8000` and open `http://localhost:8000`.

## GitHub Pages

1. Create a public repository named `Ram-19goat.github.io`.
2. Upload the contents of this folder so `index.html` is in the repository root.
3. Go to **Settings → Pages**.
4. Select **Deploy from a branch → main → /(root)** and save.
5. Your site will be available at `https://Ram-19goat.github.io/`.

## Personal files

- Replace `public/profile.jpg` with your own portrait photo.
- `public/resume.pdf` is the resume currently bundled with this package.
- Certificate cards open the PDFs from `public/certificates/`.

## Editing

The editable content is in the `EDIT YOUR CONTENT HERE` section near the bottom of `index.html`.

## Note

This package includes the certificate PDFs currently available in the provided files. If you have additional certificates, place their PDFs in `public/certificates/` and add them to the `CERTS` array in `index.html`.
