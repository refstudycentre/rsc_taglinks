# rsc_taglinks
Parses body text of nodes, changing [[tag]] into a link to the tag, and tagging the content as neccessary.

## What it does

- Defines a new filter for use in text formats
- Defines permissions
- Defines menu callbacks
- Builds a form that lists empty tags, and allows the user to delete them
- Defines a settings page
- When saving a node, it processes text fields. Text like `[[asdf]]` is replaced with `asdf`, and a taxonomy term named `asdf` is created and attached to a preconfigured field on the node.
