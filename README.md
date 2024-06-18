## VS Code

```
CODE_DIR=~/Library/Application\ Support/Code/User # may be system dependent
rm $CODE_DIR/settings.json && \
ln -s `pwd`/.vscode/settings.json $CODE_DIR/settings.json
```
