# HouseLens — Housing Market Analysis Website

## Setup

1. Install dependencies:
```bash
pip install -r requirements.txt
```

2. Run the Flask app:
```bash
python app.py
```

3. Open in browser: http://localhost:5000

## Pages
- `/` — Home page with project overview and scenario summaries
- `/dashboard` — Embedded Tableau dashboard + visualization breakdown
- `/team` — Team members and project info

## Adding Team Photos
Place member photos in `static/img/` named:
- `kaivalya.jpg`, `samarth.jpg`, `ishan.jpg`, `jay.jpg`, `pavan.jpg`

Then update the avatar elements in `templates/team.html` to use `<img>` tags.

## Structure
```
housing_project/
├── app.py
├── requirements.txt
├── templates/
│   ├── base.html
│   ├── index.html
│   ├── dashboard.html
│   └── team.html
└── static/
    ├── img/           ← Dashboard screenshots + team photos
    └── Transformed_Housing_Data2.csv
```
