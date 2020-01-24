# bmd
yet another blog script lol

bmd is a non-chronological flatfile bash blogging script.

its super lightweight - only 35 lines of code not counting whitespace.

## dependencies
- it needs bash it might work with other shells but i have not tested it
- cmark - commonmark is used to parse the markdown, you can use markdown_py
instead (bundled with python), but that is significantly slower (several
seconds) (you can also just use any other markdown parser)

## how to use
basically all you have to do is put markdown files in `.posts/`
and run `./bmd` and it will generate stuff


