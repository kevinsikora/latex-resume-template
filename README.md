# LaTeX Resume Template

A generic LaTeX resume template that produces clean, ATS-friendly (Applicant Tracking System) resumes. Use it locally or on [Overleaf](https://www.overleaf.com), where you can edit the source and preview the PDF right away.

## Project Structure

```
latex-resume-template/
├── README.md
└── latex-resume-template.tex
```

## Usage

1. Open `latex-resume-template.tex` in Overleaf or compile it with a local LaTeX setup.
2. Replace the placeholder name, contact details, summary, experience, certifications, and education with your own information.
3. Compile to generate the PDF resume.

## After Generating the Resume

Remove unneeded file metadata attributes from the finished PDF by running the following command:

```bash
xattr -c /path/to/file.pdf
```

The above command will only work on macOS.
