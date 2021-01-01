# Tests

- `typ`: Input files.
- `ref`: Reference images which the output is compared with to determine whether
         a test passed or failed. To keep things small, please run
         `oxipng -o max tests/ref/<img>` when creating or updating reference
         images (note that `<img>` can be `*` to optimize all images).
- `res`: Resource files used by tests.
- `out`: PNG and PDF files produced by tests.
