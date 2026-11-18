# FlowLens

Review, test and compare contact-center call flows in your browser: **NICE CXone Studio**, **Five9 IVR**, **Amazon Connect** and **Genesys Cloud**.

**Open it:** https://s16us-hub.github.io/ReVA/

## What it does

| Tab | What you get |
|---|---|
| 1 Add flow | Drop a CXone Studio export (XML or JSON, Desktop or web Studio), a Five9 IVR export, an Amazon Connect contact flow (JSON) or a Genesys Cloud Architect flow (YAML). ZIPs work too. Each platform has an example flow to try. |
| 2 Review | Flow chart with a lane per path (main call path, OnAnswer, OnRelease…), or a plain-language step list. Click any step for its branches, settings and findings. |
| 3 Findings | Dead ends, unreachable and orphan steps, loops with no exit, menus that retry forever, missing timeout, invalid-input, error and closed-hours branches, hard-coded environments and queue IDs, and skills or scripts missing from your reference lists. Each finding is rated high, medium or low. |
| 4 Test | Every path to test, with a tester assigned to each. Tick ✓ / ✕ on each step as you test, or use **▶ Run step by step**. Download an Excel test sheet, fill it in offline and upload it back. Export results as CSV or a sign-off report. |
| 5 Compare | Two versions of a flow side by side, or a parity check between the same flow on two platforms. |
| 6 Wispr2Uma! | Ask Uma (Claude) about the flow. See below. |
| 7 Export | Mermaid, step list, test cases, Gherkin, or a review report. |

## Where your data goes

Export files are read in your browser. On this page, saved flows, reference lists and test results stay in that browser; clearing site data removes them.

The page loads its helper libraries (dagre, ExcelJS, js-yaml, JSZip and pdf.js) from public CDNs.

Flow data goes to Claude only when you ask Uma a question or add a screenshot, PDF or document, and only when the page runs as a Claude artifact on claude.ai.

## Uma (Claude)

Uma's buttons (**Ask'Uma'tion!**, **Blam'Uma!** and the Wispr2Uma! tab) and reading screenshots, PDFs and Word, PowerPoint, Excel or Visio files need Claude, so they work only in the claude.ai version of the page.

On this GitHub Pages copy they're switched off, and the page says so. Use the XML, JSON or YAML export instead. Everything else works without Claude.

## Team testing

On this page, results are kept in each tester's browser.

1. Enter **Your name** in the Test cycle bar. Results you record show that name, and **Assign to me** uses it.
2. Share the Excel test sheet (**⬇ Download test sheet**).
3. Upload each filled copy (**⬆ Upload filled sheet**) to combine the team's results in one browser.

Evidence uploads are available only in the claude.ai version. Here, paste a link to the recording in the notes.

## Updates

Only the repository owner can change this page. To suggest a change, open an issue.
