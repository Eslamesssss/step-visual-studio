# STEP Visual Studio

A single-page 3D scene builder for planning ad shoots. It walks through idea → person and product → place → pose → camera → lighting → ready to send, and ends with an image prompt you can copy, download, or send to GPT from inside the tool.

## Run

Open `index.html` in a browser, or serve the folder:

```bash
python -m http.server 5178
```

Then go to http://127.0.0.1:5178.

## Notes

- Everything is in `index.html` (Three.js r128 loaded from a CDN).
- Your OpenAI API key is never saved in project files. The tool only remembers it in your browser if you choose to.
