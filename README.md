# Flow Workbench

Review, test and compare **NICE CXone Studio** and **Five9 IVR** call flows in your browser.

**Open it:** https://s16us-hub.github.io/ReVA/

Your files are read in your own browser and are never uploaded. Saved flows and test results stay in that browser.

## What it does

| Tab | What you get |
|---|---|
| Add flow | Drop a CXone Studio export (XML or JSON, Desktop or web Studio) or a Five9 IVR export. ZIPs work too. |
| Review | Flow chart with a lane per path (main call path, OnAnswer, OnRelease…), or a plain-language step list. Click any step for its branches, settings and findings. |
| Findings | Dead ends, unreachable steps, loops with no exit, missing timeout / invalid / error branches, unknown skills or scripts. |
| Test | Every path to test. Tick ✓ / ✕ on each step as you test, or **▶ Run step by step**. Download an Excel test sheet, fill it in offline and upload it back. Sign-off report. |
| Compare | Two versions side by side, or a CXone flow against its Five9 version. |
| Wispr2Uma! | Ask Claude about the flow (see below). |
| Export | Mermaid, step list, test cases, Gherkin, or a review report. |

## Using Claude (Uma)

The **Ask'Uma'tion!**, **Blam'Uma!** and screenshot / document buttons prepare a complete prompt with the flow data, copy it, and open claude.ai in a new tab. Paste it there and send: Claude answers under **your own** Claude login.

No Claude account? Everything else works without it.

To read a screenshot, PDF or Word / Excel / Visio document: upload it, attach the same file in Claude with the copied prompt, then paste Claude's JSON answer into **Or paste XML or JSON** and press **Use pasted text**.

## Team testing

Results are kept in each tester's browser. To combine a team's results, share the Excel test sheet (**⬇ Download test sheet**) and upload each filled copy (**⬆ Upload filled sheet**). Enter **Your name** in the Test cycle bar so results show who tested.

## Updates

Only the repository owner can change this page. To suggest a change, open an issue.
