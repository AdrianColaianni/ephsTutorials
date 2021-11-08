# EPHS Tech Tutorial Website

[https://hs.rathaus.red](https://hs.rathaus.red) (we need a better domain)

This is a simple website where users can read and create tutorials.
There are no ads, trackers, cookies or javascript.

## Ways to contribute

- By creating a tutorial
- Make a tutorial with nice pictures or add pictures if there aren't any.
	- Submitted images should be small `.webp` files ideally less than 100K or so.
- Fix errors in tutorials or add minor improvements.

## Rules for submission

- Model submission files after [example.md](example.md). Put them in `src/`.
- Tutorials should start with a title, with a single `#`, *on the first line*. No empty line at the top, no trailing line at the end. The file needs to be `\n` terminated in linux-fashion (if you're on linux you don't need to care, it should be automatic).
- File names should be the name of the tutorial with words separated by hyphens (`-`). Not underscores, and definitely not spaces.
- Tutorials must be simple and easy to follow, i.e. no extra complexity, command prompt or advanced diagnosis.
- Don't include laptop and other basic things in the materials list.

**If you fail to do these things, I will deny your submission with a list of reasons why.**

### Tags

You can (and should) add tags at the end of your tutorial. The syntax is:
```
;tags: tag1 tag2 tag3
```

The tag line should be a single line, at the end of the markdown file, preceded
by a blank line.

Add between 1 and 4 tags, **prioritize existing tags**.

List of special, categorical tags to use if relevant:
- `basic`: for basic tutorials
- `schoology`
- `microsoft`
- `docs`: for google docs tutorials
- `macbook`
- `iOS`

### Images

Images are stored in `data/pix`.

Each tutorial can have a title image at the top and several instructional images as necessary.

Do not add images you found on the internet. Take a good screenshot yourself of the process. If you see a bad or substandard image, you may submit a better one.

Images should be in `.webp` format and with as small file size as possible. If you submit an image for say, `connecting-to-wifi.md`, it should be added as `pix/connecting-to-wifi.webp`.

If you would like to add additional directional images, they should be numbered with two digits like: `pix/connecting-to-wifi-01.webp`, etc.

## About the site

The front page, for now, will just be a list of tutorials automatically generated from the content of `src`. As more articles are added, the site will be reorganized, categorized or will implement server-side scripting or searches. This is not necessary yet though.

I don't want images of tutorials on the mainpage yet. I'll think about how best to do it to minimize bandwidth if possible.

## License

This website and all its content is in the public domain. By submitting text or images or anything else to this repository, you waive any pretense of ownership to it, although you are welcome and recommended to give yourself credit at the bottom of a submitted page for you adding it (including personal link).
