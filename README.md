# lukka.github.io

## Action usage explorer

The [action usage explorer](https://lukka.github.io/graph/graph.html) shows public
repositories using run-cmake, get-cmake, and run-vcpkg, together with recorded
usage trends.

The source lives in [lukka/get-action-usage](https://github.com/lukka/get-action-usage).
Its publication workflow copies the compiled explorer assets and data into
`graph/`. GitHub Pages publishes this repository from the root of the `main` branch.

To preview this website locally, run from the repository root:

```sh
python3 -m http.server 8080 --bind 127.0.0.1
```

Open <http://127.0.0.1:8080/graph/graph.html>. No build or GitHub token is needed
in this repository; keep all explorer assets and data files together when updating.

## **License Information**

Copyright 2022-2026 by Luca Cappa lcappa@gmail.com
All content of this repository is licensed under the CC BY-SA License. See the LICENSE file in the root for license information.
