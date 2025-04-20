name: bootstrap

on:
  push:
    branches: [ main ]

jobs:
  build:
    runs-on: window-latest

    steps:
    - uses: actions/checkout@v3
    - name: Run a script
      run: echo "Hello, GitHub Actions!"
