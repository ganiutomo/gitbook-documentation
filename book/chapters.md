# Chapters and Subchapters

GitBook uses a `SUMMARY.md` file to define the structure of chapters and subchapters.

The `SUMMARY.md`'s format is simply a list of links, the name of the link is used as the chapter's name, and the target is a path to that chapter's file.

Subchapters are defined simply by adding a nested list to a parent chapter.

### Simple example

```
# Summary

* [Chapter 1](chapter1.md)
* [Chapter 2](chapter2.md)
* [Chapter 3](chapter3.md)
```

### Example with subchapters split into *parts*

```
# Summary

* [Part I](part1/README.md)
    * [Writing is nice](part1/writing.md)
    * [GitBook is nice](part1/gitbook.md)
* [Part II](part2/README.md)
    * [We love feedback](part2/feedback_please.md)
    * [Better tools for authors](part2/better_tools.md)
```

## Adding chapters from the editor

You can add chapters from the desktop or web editor simply by **right clicking** on a chapter
 and selecting `Add section`. Chapter and subchapters can be reorganized by dragging and dropping.
 
