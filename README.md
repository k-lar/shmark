# Shmark

My first attempt at making a markdown parser/compiler to HTML.  
This was a challenge to see how far I could come without reading  
anything online about proper parsing, to see how far I would get.  

It's made in relatively POSIX-y shellscript. Should run on any  
shell, but is tested on bash, zsh and dash.  

## Features

It currently supports a small subset of markdown:  

- Headings
- Paragraphs
- Bold
- Italics
- Single bullet points
    *  Can't nest them like this
- Can use "\\" to make breakline (`<br>`)


## Usage

```console
# This will print the html inside the terminal
./shmark file.md

# You can use terminal redirection to write to a .html file
./shmark file.md > rendered.html
```

## Demonstration

![Side by side html and markdown](https://gitlab.com/k_lar/shmark/uploads/b0b30c040147ac108a6ac517b1ec6604/shmark.png)
