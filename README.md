# MTEX documentation figures

Figures rendered by the MTEX documentation build, served at
https://mtex-toolbox.github.io/figures/ and embedded by the pages of
https://mtex-toolbox.github.io.

- `<Page>_NN.png`: MATLAB figures, written by `makeDoc` in the website repository
- `python/`: Python figures, written by `docs/site.py` in pymtex

The files are generated; nothing here is edited by hand. The repository keeps a
single commit that every deploy replaces (`tools/deploy-figures.sh` in the
website repository), so its size does not grow with each rebuild.
