# roxanneluo.github.io

Personal academic website of **Xuan Luo (罗璇)** — Research Scientist at Google,
working on novel view synthesis for [Project Beam](https://beam.google/).

Live site: **<https://roxanneluo.github.io>**

## Structure

| Path | Purpose |
| --- | --- |
| `index.html` | Main page: about, publications, invited talks, education |
| `projects.html` | Side projects |
| `PeppersCone.html` | Project page for Pepper's Cone (UIST 2017) |
| `assets/css/style.css` | Site stylesheet (no JS dependencies) |
| `images/`, `papers/`, `demos/` | Publication thumbnails, PDFs, and demo videos |
| `cv.pdf` | Curriculum vitae |

## Development

The site is plain static HTML/CSS — no build step. Preview locally with:

```sh
python3 -m http.server
```

then open <http://localhost:8000>.
