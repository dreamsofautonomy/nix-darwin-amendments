# Video Amendments

This page describes any amendments from the nix-darwin video that were discovered
after filming

## Homebrew

After installing homebrew, you'll need to add the following line to your
shell rc file, i.e. `.zshrc` in order for installed homebrew binaries to
be detected.

```
export PATH="/opt/homebrew:$PATH"
```

If you're using homebrew already, you likely have this already added.
