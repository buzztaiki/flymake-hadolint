# flymake-hadolint

Flymake backend for hadolint, a Dockerfile linter.

## Usage

To use it with [dockerfile-mode](https://github.com/spotify/dockerfile-mode), add the following to your init file:

```lisp
(add-hook 'dockerfile-mode-hook #'flymake-hadolint-setup)
```
