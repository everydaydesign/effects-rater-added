# Effects rater, two added reports

A two-study copy of the AI Role Rater used in the first round of inter-rater coding ([everydaydesign/effects-rater](https://github.com/everydaydesign/effects-rater)). It holds the two reports that were added to the review later and the same instrument as the first round, AI role A, B, or C and comparison type 1 to 6, with the same wording on every card.

## How to rate

1. Open the page and enter your first name at the top left.
2. Read each report in the viewer and choose one AI role and one comparison type. Press Submit, or Enter.
3. When both reports are rated, press **Export ratings (CSV)** and send the file to the first author.

Please rate on your own and do not discuss your ratings until both files are in. Your ratings are saved only in your own browser, under keys of their own, so they do not touch your ratings from the first round. Keyboard: A, B, C for the role, 1 to 6 for the comparison, Enter to submit, arrow keys for the previous or next report, Page Up and Page Down for pages.

The exported file has one row per report, with the columns `study_id`, `authors`, `year`, `doi`, `coder`, `rating`, `comparison`, `note`, and `rated_at`. The comparison is stored as a letter, as in the first round: N for 1 (AI vs no-AI), H for 2 (AI vs human), P for 3 (AI vs peer), X for 4 (AI+human vs human), V for 5 (AI vs AI), and O for 6 (Other / single-group).

## Sources and licences

The two articles are open access and are included unchanged under their licences.

- Brügge, E., Ricchizzi, S., Arenbeck, M., Keller, M. N., Schur, L., Stummer, W., Holling, M., Lu, M. H., & Darici, D. (2024). Large language models improve clinical decision making of medical students through patient simulation and structured feedback: A randomized controlled trial. *BMC Medical Education, 24*, 1391. https://doi.org/10.1186/s12909-024-06399-7. File `pdfs/brugge-2024.pdf`, licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
- Hao, H., Razali, A. B., & Zuo, R. (2026). Exploring the impact of integrated AWE and generative AI feedback on Chinese EFL undergraduates’ higher-order thinking in argumentative writing. *SAGE Open, 16*(1). https://doi.org/10.1177/21582440251413884. File `pdfs/hao-2026.pdf`, licensed under [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/).

The PDF viewer is [PDF.js](https://mozilla.github.io/pdf.js/) by the Mozilla Foundation, included in `vendor/` under the Apache License 2.0.
