# Week 03 Time

## Using Time

```

// https://editor.p5js.org/jht9629-nyu/sketches/3VKJ-q8ar
// ims03-jht scrolling color bars
// color pops on at wrap around - no rate regulation

// https://editor.p5js.org/jht9629-nyu/sketches/ZpoPuHXRo
// ims04-jht scroll color bars - no pop

// https://editor.p5js.org/jht9629-nyu/sketches/2pxhnehBV
// ims04-jht scroll color rate
// rate adjusted to achieve complete
// scroll in my.scrollSeconds
// https://p5js.org/reference/#/p5/deltaTime
  let deltaSecs = deltaTime / 1000
  my.xstep = width * deltaSecs / my.scrollSeconds;

// https://editor.p5js.org/jht9629-nyu/sketches/i6akdNRS2
// video scan radial v7
  secsDelta += deltaTime / 1000;

// https://editor.p5js.org/jht9629-nyu/sketches/wT957KlMz
// MazeSpin liberation screens v2
  let now = millis() / 1000;


```

## saving data locally

Must locally or in web browser to use url parameters

- url param strings
- localStorage

```
// https://editor.p5js.org/jht9629-nyu/sketches/TQyVoswjQ
// p5moLibrary DrawPoints
// https://molab-itp.github.io/p5moLibrary/src/demo/DrawPoints/?v=65

// https://editor.p5js.org/jht9629-nyu/sketches/iIIAb8KIDr
// p5moLibrary Astronomical 47
// https://molab-itp.github.io/p5moLibrary/src/demo/Astronomical/?v=65

// https://editor.p5js.org/jht9629-nyu/sketches/5fTCCJ_Sh
// get_url_params demo

```

- [p5moLibrary](https://github.com/molab-itp/p5moLibrary)

## Homework Week03

- Expand your full screen p5js screen or write/find a new one to use configuration data

  - make the p5js sketch available via your github repo as github pages

- add a link to your sketch on the [wiki home page](https://github.com/p5videoKit/IM-Screens-2024-03-ima/wiki#week-03-homework)

- enter any questions or notes on your wiki page

<!-- ## nodejs setup

[https://nodejs.org/en/download](https://nodejs.org/en/download)

 -->

## Class Resources

- [p5mirror](https://github.com/molab-itp/p5mirror)

  - mirror your editor.p5js sketches into a git repo

- [p5moExamples](https://github.com/molab-itp/p5moExamples)

  - p5js examples for p5moLibrary

- [p5moLibrary](https://github.com/molab-itp/p5moLibrary)

  - a p5js Library for cloud storage enhanced multi-device experiences

- [p5VideoKit](https://github.com/molab-itp/p5videoKit)
  - a dashboard for mixing video in the browser.
