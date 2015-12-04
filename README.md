# CLI animated GIF generator

Quickly create an animated GIF of a CLI command and its resulting output.

## Usage

Create a Markdown file with the contents of your command, and it's output. The
first line should be the command with a `$` at the start of the line to
signify the terminal prompt, e.g.:

```markdown
$ ls -al

drwxrwxrwt  31 root   wheel     1054 Dec  4 07:55 .
drwxr-xr-x@  6 root   wheel      204 Oct 12 07:42 ..

```

If that Markdown content was saved to a file called `example.md`, then pass
that filename into `cli-gif-generator` as the only argument, e.g.:

```bash
./cli-gif-generator example.md
```

And the result would look like:

![CLI animated GIF example](http://a.gln.io/AHR6rvvSbs.gif)
