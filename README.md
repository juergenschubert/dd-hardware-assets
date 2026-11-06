# DD Hardware Assets

An independent image library for Dell Data Domain topology diagrams and presentations. This repository is not an official Dell repository.

## Upload approved PNGs

You can add images directly on GitHub; cloning the repository is optional.

1. Open `heads/` for Data Domain head/controller images or `shelves/` for storage shelf images.
2. Choose **Add file → Upload files** and upload the production-approved PNGs.
3. Keep filenames short and descriptive, for example `dd9910-front.png` or `es40-shelf-front.png`.

The README files in those folders keep the upload paths visible on GitHub. They are placeholders, not hardware images. No image has been fabricated or included.

## Reference templates stay separate

`reference-templates/` is reserved for non-production reference material. Do not put its contents in a customer-facing or production-approved image set. The top-level `heads/` and `shelves/` folders are the production image locations.

## Optional manifest

Uploading a PNG is enough to use it. If you want to record metadata, add one entry for it to [`manifest.json`](manifest.json), following [`schema/asset-manifest.schema.json`](schema/asset-manifest.schema.json). The manifest starts empty so it does not claim any asset exists or has been approved.

## Rights and public distribution

This repository is public. Before uploading, confirm that the image may be distributed publicly on GitHub. Presentation approval or local approval does not by itself establish public distribution rights. See [`RIGHTS.md`](RIGHTS.md).
