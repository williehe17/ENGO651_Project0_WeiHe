# ENGO651 Project 0 — Premier League 2024/25 Website

## Project overview
This project is a multi-page website about the Premier League 2024/25 season.  
It includes standings, teams overview, season statistics, and classic match highlights. Bootstrap 4 is used for layout/components, and custom styling is provided through SCSS compiled into CSS.

## Pages
- **index.html**: Home page with introduction, navigation, a content list, and an image.
- **standings.html**: Final league standings table (Top 5 highlighted green; Bottom 3 highlighted red).
- **teams.html**: Teams grouped into categories using Bootstrap grid and cards.
- **statistics.html**: Top scorers and top assists tables, plus a short season summary.
- **matches.html**: Three classic match highlight cards with images and bullet lists.

## Styling
- **styles.scss**: SCSS source file using variables, nesting, and inheritance (`@extend`).
- **styles.css**: Compiled CSS stylesheet used by all pages (linked as `css/styles.css`).

## Frameworks / Libraries
- **Bootstrap 4**: Used for the navbar, grid system, cards, tables, and buttons.

## Assets
- Images are stored in the **img/** folder and referenced by `index.html` and `matches.html`.
