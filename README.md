# nf-outputs-releases

Public release artifacts for the [nf-outputs](https://github.com/theiagen-rd/nf-outputs) Nextflow plugin.

Source code is maintained in a private repository. This repo hosts only compiled
release artifacts so that Nextflow can auto-install the plugin without
authentication.

## Installation

```bash
export NXF_PLUGINS_TEST_REPOSITORY="https://github.com/theiagen-rd/nf-outputs-releases/releases/download/v0.1.0/nf-outputs-0.1.0-meta.json"
nextflow run your-pipeline.nf -preview -plugins nf-outputs@0.1.0
```
