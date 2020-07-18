# Set Markdown CSS
This is a small and fast sh script to select the desired css for MarkdownPreview (https://github.comiamcco/markdown-preview.vim)

## What is it to good for?
It's nice to quickly change a different CSS to preview your Markdown Files when you're working in VIM

## How does it work?
It creates a symbolic link with a CSS file, allowing you to keep your .vimrc pointing to a fixed CSS file, while quickly selecting which CSS you want to use

## How do I use it?
you edit line 7 to reflect the path to your chosen CSS configuration, then you edit your .vimrc to include a line:

<pre><code>let g:mkdp_markdown_css = '/path/to/the/configured/css.css'
</code></pre>

If you don't want to edit it, the location it'll point to is:

<pre><code>~/.local/lib/markdown_css/configured.css
</code></pre>
