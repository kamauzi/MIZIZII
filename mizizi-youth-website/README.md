# Mizizi Youth Organization Website

A static website prepared for GitHub Pages.

## Folder structure

```txt
mizizi-youth-website/
├── index.html
├── css/style.css
├── js/main.js
└── assets/images/
    ├── hero.jpg
    ├── placeholder.svg
    └── gallery/
        ├── gallery-1.jpg
        ├── gallery-2.jpg
        └── ...
```

## How to add photos

1. Put the main hero image here:

```txt
assets/images/hero.jpg
```

2. Put gallery photos here:

```txt
assets/images/gallery/
```

3. Rename them as:

```txt
gallery-1.jpg
gallery-2.jpg
gallery-3.jpg
gallery-4.jpg
gallery-5.jpg
gallery-6.jpg
```

Or edit the image names inside `index.html`.

## How to deploy on GitHub Pages

1. Create a GitHub repository, for example:

```txt
mizizi-youth-organization
```

2. Upload all files in this folder.
3. Go to:

```txt
Settings → Pages
```

4. Select:

```txt
Deploy from branch → main → /root
```

5. Your site will be live at:

```txt
https://YOUR-USERNAME.github.io/mizizi-youth-organization/
```

## Later custom domain

When the organization buys a domain, connect it under:

```txt
Settings → Pages → Custom domain
```

Then update DNS with the domain provider.
