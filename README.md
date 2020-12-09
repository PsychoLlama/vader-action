<div align="center">
  <h1>action-vader</h1>
  <p>Test your vim plugin with <a href="https://github.com/junegunn/vader.vim/">vader</a>.</p>
</div>

## Usage
```yml
- uses: PsychoLlama/vader-action@v1
  with:
    # Use a custom glob pattern to find test files.
    # Default: all `.vader` files.
    test-pattern: '**/*.vader'
```
