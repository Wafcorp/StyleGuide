# StyleGuide

Style guide for WafCorp Repo's

## Project Style:

- If the project is version there are 2 options :
    - Semver[^1] *(e.g. 1.2.3)*
    - Or if the versioning doesn't need to be complex, it should single digit and separated from name with a "-". *(
      e.g. "Season-3")*
- Naming :
    - Must follow PascalCase[^2]. *(e.g. FirstProject)*
    - Should not contain any special characters.
    - Refrain from using number characters in name. Instead, spell the number out. *(Only apply if the number is not a
      version number)*

## Folder Naming:

- Should follow the same naming scheme as Projects.

## Files:

- Naming:
    - Must follow snake_case[^3]. *(e.g. apple_file.txt)*
    - Should not contain any special characters. Unless necessary.
    - Refrain from using number characters in name. Instead, spell the number out, or not use it at all.
- File format:
    - Text files should all be Markdown[^4] files. Unless other format is necessary. *(e.g. file_name.md)*

> [!IMPORTANT]
> Here are some link to help with Markdown formatting:
> - [Quick Cheat Sheet](https://github.com/im-luka/markdown-cheatsheet/blob/main/README.md)
> - [Full GitHub Docs](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)



[^1]: Semver(Semantic versioning) is a versioning format that is made of three Identifiers.
The First 1.x.x being major (Breaking) version changes.
Second x.1.x being minor (Non-breaking) version changes.
Third x.x.1 being a patch / bugfix version. Read more here: https://semver.org/
[^2]: PascalCase is the practice of writing phrases without spaces or punctuation and with all words being capitalized.
[^3]: snake_case is the naming convention in which each space is replaced with an underscore "_" character, and the
first letter of each word is written in lowercase.
[^4]: Markdown is a lightweight markup language for creating formatted text using a plain-text editor.