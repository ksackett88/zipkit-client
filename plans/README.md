# Standard plan PDFs

Drop the floor-plan PDFs in this folder. The intake form's "Step 1: Download the Standard Plans" grid links to `plans/{slug}.pdf` for each model — if the file exists, the download works; if not, the customer gets a 404 from the browser.

## Filename convention

Lowercase, spaces become dashes, `.pdf` extension.

## Full filename list (28 models)

```
big-sky.pdf
bridger.pdf
tahoe.pdf
sequoia.pdf
frontier.pdf
clyde.pdf
birch.pdf
willow.pdf
bozeman.pdf
sunstone.pdf
bluebell.pdf
shasta.pdf
summit.pdf
jasper.pdf
mesa.pdf
koda.pdf
hayden.pdf
cedar.pdf
timberline.pdf
apache.pdf       (Barndominium)
juniper.pdf      (Barndominium)
zion.pdf
columbia.pdf
alpine.pdf
moab.pdf
meadow.pdf
solitude.pdf
olympic.pdf
```

## Notes

- Customer's download will be auto-renamed to `ZipKit_{slug}_plans.pdf` (so they save it with a clear filename).
- Drop PDFs in incrementally — no code changes needed. Each PDF activates the moment it's committed.
- Thumbnails are pulled from `ksackett88.github.io/zipkit-quoting-tool/photos/` so you don't need to upload model photos here too.
