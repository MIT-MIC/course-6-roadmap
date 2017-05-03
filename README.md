<!--# Course 6 Roadmap v0
-->
<p align="center">
  <img src=img/course-6-roadmap.png alt="Course 6 Roadmap" width="500px"/>
</p>

Draws a simple force graph of all classes in Course 6 at MIT with directed edges indicated prerequisites.

## Usage

Run

```
python -m SimpleHTTPServer 8000
```

and navigate to `127.0.0.1:8000` or `localhost:8000`.  Uses `d3.js`.

## TODOs

(Pull requests welcome!)

* Color a node when hovering over it
* Click it to reveal all parent nodes
* Unclick node to de-color everything
* Add class name when hovering over something
* Make node size proportional to node's degree.
