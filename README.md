# RubixCube-GPT5

Interactive Rubik's Cube (2x2x2 up to 20x20x20) built with Three.js.

- OrbitControls camera (rotate/zoom)
- Layer rotations by axis/layer or standard face moves (U, D, L, R, F, B, with ' and 2)
- Shuffle (~100 random quarter turns)
- Solve animates inverse move history
- Keyboard and minimal gamepad support

## Run locally

Serve the folder with any static server, e.g.

```bash
npx http-server -p 8080 -c-1 .
```

Open `http://localhost:8080`.

## GitHub Pages

Once deployed, the site will be available at:

- https://orion-productions.github.io/RubixCube-GPT5/

If Pages is not yet enabled for the repository, push the `gh-pages` branch and
enable GitHub Pages in the repo settings, choosing the `gh-pages` branch as the source.

## License

MIT
