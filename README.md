# SBA ELI Design
For maintaining the Ascent platform design assets.

## Requirements
* [Sketch](https://www.sketchapp.com/) or [SketchTools](https://developer.sketchapp.com/guides/sketchtool/)
* Git
* [Git LFS](https://git-lfs.github.com/)

## Setup
1. Clone this repo
1. Run `git lfs install && git lfs track '*.png' && git lfs track '*.sketch' && git add .gitattributes`
1. Run `cp pre-commit .git/hooks/pre-commit && chmod 700 .git/hooks/pre-commit` and replace the [SketchTools path](https://github.com/jrwatts/office-lookup/blob/3d420e96c1b93930367048e3fa4a3085d996a46f/pre-commit#L3) SkechTools path if needed
