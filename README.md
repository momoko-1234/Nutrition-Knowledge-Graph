# Nutrition Knowledge Graph

An interactive, open-source map of relationships between foods, nutrients, and health benefits.

## Features

- 100 nodes across food, nutrient, and health-benefit categories
- Directional relationships from food to nutrient to benefit
- Nutrient synergy and interaction relationships
- Search with automatic graph focus
- Node-type and relationship filters
- Zoom, pan, drag, connected-node highlighting, and detail panel
- Responsive mobile detail sheet

## Run locally

No build step is required. Start any static file server in the project directory:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## GitHub Pages

Open **Settings → Pages**, choose **Deploy from a branch**, then select the `main` branch and `/ (root)`.

## Contributing

Bug reports, accessibility improvements, translations, interface ideas, and evidence-backed data corrections are welcome. Read [CONTRIBUTING.md](CONTRIBUTING.md) before submitting a pull request.

## Health information disclaimer

This project is educational and does not provide medical diagnosis or treatment advice. Relationships in the graph may summarize biological mechanisms or associations and should not be treated as personal health recommendations. Always verify sources and consult a qualified health professional for medical decisions.

## License

Code is available under the [MIT License](LICENSE). Contributors are responsible for ensuring submitted content and sources can be redistributed.
