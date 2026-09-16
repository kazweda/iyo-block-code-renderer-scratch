# Contributing

Thanks for considering a contribution to Iyo Block Code Renderer for Scratch.

## Reporting bugs / requesting features

Please use the [GitHub issue tracker](https://github.com/kazweda/iyo-block-code-renderer-scratch/issues).

## Submitting a pull request

1. Fork the repository and create a branch from `main`.
2. Make your change. Keep pull requests focused on a single fix or feature.
3. If your change is user-facing, add a changelog entry under `== Changelog ==` in `readme.txt` (and bump `Stable tag:` / the plugin header `Version:` only if a maintainer asks you to — version bumps are handled at release time).
4. Test the change in a local WordPress install by activating the plugin and rendering a `scratchblocks` block (see `README.md` for usage).
5. Open a pull request against `main` and describe what changed and why.

`main` is protected: all changes land via pull request. A maintainer will review and merge.

## Code guidelines

- Follow the existing code style in the file you're editing.
- Don't modify the bundled `assets/js/scratchblocks/` library directly — it's vendored from [scratchblocks](https://github.com/scratchblocks/scratchblocks). Report upstream issues there instead.
- Don't commit build artifacts (`build/`, `vendor/`) or files under `.gitignore`.

## License

By contributing, you agree your contribution is licensed under the GPLv2 (or later), matching this project's [LICENSE](LICENSE).
