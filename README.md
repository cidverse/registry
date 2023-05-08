# CID - Central Catalog

The central catalog for `container-images`, `actions` and `workflows` usable in github.com/cidverse/cid.

## Generate Index

To generate the `cid-index.yaml` file, use the following command:

```bash
cid registry process --input <directory>
```

Where <directory> is the input directory containing the files to be processed and merged. The `cid-index.yaml` file will be generated in the same directory as the input directory.

## Update Documentation

TODO: automate this step

Documentation files for workflows and actions are generated automatically using `cid docs -o <directory>`. The documentation files should be committed to https://github.com/cidverse/cidverse.github.io.
