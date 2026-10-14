# Supreme Court of India – Judgment / Order Finder

Simple free web helper for law students and lawyers.

## What it does

- Lets you enter **Diary Number + Year** or **Case Number + Year**
- Opens the official Supreme Court of India Judgments search page
- Reminds you of the details you entered so you can quickly fill the form + CAPTCHA and download the PDF

## Why it cannot fully auto-download

The official website (`main.sci.gov.in`) protects its search with CAPTCHA.  
A pure static website cannot bypass CAPTCHA. Therefore this tool acts as a **helper** that takes you to the correct official page with your numbers ready.

## How to use

1. Open the website (enable GitHub Pages or open `index.html` locally).
2. Choose Diary Number or Case Number.
3. Enter the details.
4. Click **Open Official SCI Search**.
5. On the official page, complete the CAPTCHA and download the judgment/order PDF.

## Official links included

- [Judgments Search](https://main.sci.gov.in/judgments)
- [e-SCR / DigiSCR](https://digiscr.sci.gov.in/)
- [Verdict Finder](https://verdictfinder.sci.gov.in)
- [eCourts Judgment Search](https://judgments.ecourts.gov.in)

## Future improvements you can add

- Backend that uses public open datasets (e.g. AWS Indian Supreme Court Judgments)
- Integration with your personal Jarvis / local RAG system so downloaded PDFs automatically go into your judgment folder
- Support for High Courts later

## Disclaimer

This is an independent helper tool.  
It is **not** affiliated with the Supreme Court of India.  
Always download and verify judgments from the official website.

---

Created for personal study use.