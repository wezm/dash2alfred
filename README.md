# Snippet Tools

Tools for converting between snippet formats:

- Convert [Dash] snippets into [Alfred] 3 snippets (`dash2alfred`)
- Convert [Alfred] snippets to [Xpander] snippets (`alfred2xpander`)

## dash2alfred

### Usage

    ./dash2alfred ~/Dropbox\ \(Personal\)/Dash\ Snippets.dash Dash\ Snippets.alfredsnippets

Substitute `~/Dropbox\ \(Personal\)/Dash\ Snippets.dash` with the path
to your Dash snippets. You can copy this from Dash by opening the
preferences, switching to the Snippets tab and then copying the
"Snippet Library Location".

Double click the generated `.alfredsnippets` file to import them into
Alfred.

## alfred2xpander

### Usage

    find ../Alfred\ Snippets -name \*.alfredsnippets -exec ./alfred2xpander '{}' \;
