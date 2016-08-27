# Contributing

If you want to contribute, just leave request in [issues](https://github.com/audio-lab/contributing/issues).

## Naming conventions

* `gl-*` packages relate to webgl processing, usually that means at least `gl` in options and `draw` method. Similar to [gl-vis](https://github.com/gl-vis) components.
* `*-util` packages provide a collection of some functions specific for some domain, like audio-buffers, pcm, stream etc.
* `sound-*` packages relate to sound producing side of code, unlike `audio-*`, which are focused on technical side. E. g. `sound-bird` etc.
* `audio-*` packages should provide stream interfaces (at least). Unless it is known name, like `audio-buffer`. Better fit to [audiojs](https://github.com/audiojs).
* `web-audio-*` packages should be related with Web Audio API and make sense in that context. Better fit to [audiojs](https://github.com/audiojs).

Of course there are exceptions.

## Workflow

Stick to PRs workflow and all fine.

## Related

**[audiojs](https://github.com/audiojs)** — a place for audio components in js.
