# Hypotrail lesson packs

Lesson packs teach the method behind a Hypotrail Study. Each pack is a directory of English JSON data with `pack.json` and `lessons.json`. Hypotrail validates the files and serves their content in the CLI.

The first pack, `scoring-en`, teaches temporal regression from intake to delivery. Set `HYPOTRAIL_LESSON_PACKS=/abs/path/packs/scoring-en` before running Hypotrail. Use your platform's path separator to list more than one pack directory.

To check a pack, install Hypotrail from the commit in `hypotrail.pin` and run:

```sh
python -m hypotrail lesson check packs/scoring-en --kept /path/to/hypotrail/clients/vscode/test/cli
```
