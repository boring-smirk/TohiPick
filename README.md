# TohiPick

TohiPick is a lightweight, single-file web app for sorting and managing **Iranian university major-selection codes** (انتخاب رشته) with a fast drag-and-drop interface.

## Features

- Drag-and-drop reordering with sortable priority numbers
- Multi-select actions (move to top/up/down/bottom/specific position, bulk delete)
- Add new items individually or in bulk
- Search by code, university, major, or notes
- Export options:
  - Copy only ordered codes
  - Copy full ordered list
  - Download CSV (UTF-8 BOM for Persian Excel support)
  - Download a self-contained HTML file with current order
- Local persistence via browser `localStorage`
- Font family and font size controls

## Tech Stack

- Plain HTML, CSS, and JavaScript
- [SortableJS](https://github.com/SortableJS/Sortable) (CDN)
- No backend, no build step, no package manager required

## Project Structure

- `/R∅shte_T_Vr.html` – complete application (UI, styles, logic, and initial data)

## Getting Started

1. Clone or download the repository.
2. Open `/R∅shte_T_Vr.html` in a modern browser.
3. Start sorting and exporting your selected order.

## Data & Storage

- Initial sample items are embedded in the `originalData` array in the HTML file.
- Runtime changes are saved in browser local storage, so your order persists on the same device/browser.

## Notes

- This is a client-side utility app intended for quick personal workflow use.
- Sharing via **Export HTML** generates a standalone file containing your current ordered list.
