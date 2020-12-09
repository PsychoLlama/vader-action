<div align="center">
  <h1>action-vader</h1>
  <p>Test your vim plugin with <a href="https://github.com/junegunn/vader.vim/">vader</a>.</p>
</div>

## Usage
Basic:
```yml
- uses: PsychoLlama/vader-action@v1
```

Overriding the test glob:
```yml
- uses: PsychoLlama/vader-action@v1
  with:
    # Default: runs all files with the `.vader` extension.
    test-pattern: '**/*.vader'
```

Running tests with neovim:
```yml
- uses: PsychoLlama/vader-action@v1
  with:
    # Note: neovim must be installed before enabling this feature.
    # Installation is easy with the excellent `rhysd/action-setup-vim` action.
    neovim: true
```
