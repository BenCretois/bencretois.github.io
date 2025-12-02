# My Website

## Local Development
```bash
# Install Hugo (macOS)
brew install hugo

# Install Hugo (Linux)
sudo apt install hugo

# Clone and run
git clone https://github.com/BenCretois/bencretois.github.io.git
cd bencretois.github.io
hugo server
```

Or with nix:

```bash
nix-shell -p hugo --run "hugo server --bind=0.0.0.0
```

## 📁 Site Structure

```
├── hugo.toml              # Site configuration
├── content/               # All content files
│   ├── projects/         # Research projects
│   ├── publications.md   # Publications page
│   └── contact.md        # Contact information
├── layouts/              # HTML templates
├── static/               # Static assets (CSS, images)
└── .github/workflows/    # GitHub Actions for deployment
```

## Update Profile
- Edit personal info in `hugo.toml`
- Add profile photo as `static/images/benjamin-cretois.jpg`
- Update bio text in `layouts/index.html`

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

