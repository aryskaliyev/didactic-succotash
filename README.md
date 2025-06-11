# Principles
## Unit Testing
- Rule of thumb 👍
  1. Check for error types first, eg `assert.ErrorIs`
  2. Whenever necessary, check for error strings, eg `assert.EqualError`
