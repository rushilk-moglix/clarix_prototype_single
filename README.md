# Clarix prototype, in one file

Clarix: run calling campaigns with your agents, follow every call and download the results.

This repository holds the whole clickable prototype as **one HTML file**, for design, engineering and leadership review.
Nothing to install and nothing to run.

| Way | How |
| :--- | :--- |
| Open it online | https://rushilk-moglix.github.io/clarix_prototype_single/Clarix-Prototype.html |
| Download it | https://rushilk-moglix.github.io/clarix_prototype_single/ and press **Download the file**, then double click the file |
| Share it | Send `Clarix-Prototype.html` by email or chat. It works offline |

It signs in to a demo workspace by itself.

## What to look at

| Where | What |
| :--- | :--- |
| Dashboard | The same calling numbers as Echo, an agent picker, input problems and why calls did not finish. |
| Campaigns | New campaign: pick an agent, download its template, upload the sheet. |
| Call logs and a call | Every call with its status; open one for the outcome, answers and dials. |
| Follow ups | Rows that need a person, with an owner and notes. |
| Orchestration | Under Build: split one upload into routes by rule, each going to an agent, with live counts from a real file. |
| Agent setup and Data | Under Build: how a sheet maps to an agent, and lookups that fill blanks. |

## Good to know

- The data is invented sample data held in memory. It starts fresh each time the file is opened or reloaded.
- Calls are simulated. Nothing is dialled and nothing leaves your computer.
- Use Chrome or Edge.
- Page addresses use `#`, for example `Clarix-Prototype.html#/overview`. You can send someone a link to a specific page.
- This is a prototype of the planned product, not the live product.

## Source

The file is built from the full prototype: https://github.com/rushilk-moglix/clarix_prototype (`npm run build:single`).
The running demo of that prototype is at https://rushilk-moglix.github.io/clarix_prototype/.
