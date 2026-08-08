# Color Pulse

A responsive, interactive five-question leadership-style quiz that assigns users one of four color-based profiles:

- 🔴 **Red — The Bold Driver**
- 🔵 **Blue — The Deep Analyst**
- 🟡 **Yellow — The Bright Inspirer**
- 🟢 **Green — The Grounded Supporter**

## Live Demo

[View Color Pulse](https://ghtester777.github.io/)

## Features

- Five-question leadership-style assessment
- Dynamic quiz questions and answer options
- Animated progress bar and screen transitions
- Four personality-style result profiles
- Strengths and potential blind-spot summaries
- Copy-to-clipboard result sharing for Zoom chat
- Mobile-friendly responsive design
- Tailwind CSS styling and Google Inter font

## How It Works

Each answer adds one point to a color category:

| Color | Leadership Style |
|---|---|
| Red | Action-oriented, decisive, and results-driven |
| Blue | Detail-oriented, objective, and strategic |
| Yellow | Enthusiastic, persuasive, and creative |
| Green | Empathetic, reliable, and team-focused |

After the final question, the application selects the color with the highest score and displays its corresponding leadership profile.

## Built With

- HTML5
- CSS3
- Vanilla JavaScript
- [Tailwind CSS](https://tailwindcss.com/) via CDN
- [Google Fonts: Inter](https://fonts.google.com/specimen/Inter)
- GitHub Pages

## Run Locally

Clone the repository:

```bash
git clone https://github.com/GHtester777/GHtester777.github.io.git
cd GHtester777.github.io
```

Start a local web server:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Deployment

This project is deployed with GitHub Pages from the `main` branch.

To publish changes:

```bash
git add .
git commit -m "Describe your change here"
git push origin main
```

## Project Structure

```text
GHtester777.github.io/
├── index.html
└── README.md
```

The app is currently built as a single-file website: its HTML, custom CSS, and JavaScript are all contained in `index.html`.

## Disclaimer

Color Pulse is an educational and entertainment-oriented leadership reflection tool. It is not a clinically validated personality assessment or a substitute for professional psychological evaluation.

## License

This project is available for personal and educational use.
