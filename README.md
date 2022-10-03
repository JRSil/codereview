# Comandos

- gpg --full-generate-key
- gpg --list-secret-key --keyid-form LONG

- npm install -g @commitlint/cli @commitlint/config-conventional
- echo "module.exports = {extends: ['@commitlint/config-conventional']}" > commitlint.config.js

ou

- docker run --rm --name="commitsar" -w /src -v "$(pwd)":/src aevea/commitsar commitsar .
