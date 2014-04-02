# Freifunk Metadata Wordpress Plugin

A small Wordpress plugin to render Freifunk metadata.

It reads (and caches) JSON input from a configured URL and provides shortcodes to output the data.

Currently implemented are `[ff_services]` and `[ff_contact]`.

## Example

Text:

    Services:

    [ff_services]

    Contact:

    [ff_contact]

    Contact Jena:

    [ff_contact url="http://freifunk-jena.de/jena.json"]

Output:

![shortcode output example](http://mschuette.name/wp/wp-upload/freifunk_meta_example.png)
