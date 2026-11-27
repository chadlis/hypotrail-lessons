# Hypotrail lesson packs

Lesson packs teach the method behind a Hypotrail Study. Each pack is a directory of English JSON data with `pack.json` and `lessons.json`. Hypotrail validates the files and serves their content in the CLI.

`forecasting-en` teaches temporal regression from intake to delivery with seven diagrams in the VS Code companion. Set `HYPOTRAIL_LESSON_PACKS=/abs/path/packs/forecasting-en` before starting VS Code or running the CLI. Use your platform's path separator to list more than one pack directory.

To check a pack, install Hypotrail from the commit in `hypotrail.pin` and run:

```sh
python -m hypotrail lesson check packs/forecasting-en --kept /path/to/hypotrail/clients/vscode/test/cli
```

Lesson content is licensed under [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/). See [LICENSE](LICENSE).
