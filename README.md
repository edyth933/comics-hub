Welcome to the comic collection data center. Feel free to add/modify the data set.

## Folder Structure

The `comics` folder is organized as follows:

```
comics
│
└── {comic-slug}      # Comic slug-name or identifier
    ├── info.json     # Comic information file
    └── ch-{n}.json   # Comic chapter files
```

## File Naming Rules

### Comic Information File

The comic information file, `info.json`, should be saved directly inside the `{comic-slug}` folder. It contains metadata and details about the comic.

### Comic Chapter Files

Each comic chapter file should follow the naming convention `ch-{n}.json`, where `{n}` represents the chapter number. These files should also be saved directly inside the `{comic-slug}` folder.

## Example:

Suppose we have an comic called "Adventures of Hero". The folder structure and file naming would look like this:

```
comics
│
└── adventures-of-hero
    ├── info.json
    ├── ch-1.json
    ├── ch-2.json
    └── ...
```

In this example, `info.json` contains information about "Adventures of Hero", `ch-1.json` and `ch-2.json` represent the first and second chapters, respectively.

---

Feel free to modify this README as well!
