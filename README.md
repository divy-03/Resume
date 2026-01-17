# Resume

A repo where I keep my [resume](https://github.com/divy-03/Resume/blob/main/resume.pdf) and its [latex](https://github.com/divy-03/Resume/blob/main/resume.tex) code

## Resume Update Workflow

This repo is also associated with an automated workflow which updates my resume on drive too.

- **GitHub Actions Bot**:
  - triggers when resume.tex is updated
  - compile latex to pdf
  - commits pdf back to this same repo

- **n8n**:
  - triggers on push on this repo
  - get the updated resume pdf
  - update the pdf uploaded on drive
