# WonderBean — Artwork Showcase

Official portfolio and website for **WonderBean** (`@wonderbeandraws`), created with love, whimsical spirit, and bold colors.

## 🎨 Features
- **Warm & Professional Serif Typography**: Google Fonts *Fraunces* paired with *Plus Jakarta Sans*.
- **Whimsical 6-Color Palette**: Incorporates Yellow, Pink, Purple, Green, Blue, and Red on a warm cream canvas.
- **Home**: Studio update announcement (*"artwork coming soon"*) and link to [`@wonderbeandraws`](https://www.instagram.com/wonderbeandraws) on Instagram.
- **Gallery**: Playful placeholder gallery featuring bespoke, handcrafted SVG pickle character studies (*"Dill With It"*, *"The Artiste"*, *"Sir Gherkin"*, and more).
- **About**: The authentic story of Wonder Bean — balancing life as a teacher and artist, embracing boldness and wonder.

## 📁 Project Structure
```
wonderbeandraws/
├── index.html              # Home page
├── gallery.html            # Gallery page with pickle placeholders
├── about.html              # About story
├── 404.html                # Friendly fallback page
├── assets/
│   ├── css/
│   │   └── style.css       # Design system & responsive styles
│   └── images/
│       ├── favicon.svg     # WonderBean beret avatar icon
│       ├── instagram.svg   # Instagram icon
│       ├── pickle-1.svg    # Pickle #1: Dill With It
│       ├── pickle-2.svg    # Pickle #2: The Artiste
│       ├── pickle-3.svg    # Pickle #3: Cool as a Cucumber
│       ├── pickle-4.svg    # Pickle #4: Sir Gherkin
│       ├── pickle-5.svg    # Pickle #5: Cosmic Brine
│       └── pickle-6.svg    # Pickle #6: The Big Dill
└── README.md
```

## 🚀 GitHub Pages & Custom Domain Deployment

### 1. Enable GitHub Pages
1. Go to your GitHub repository: [github.com/ArthurBond/wonderbeandraws](https://github.com/ArthurBond/wonderbeandraws)
2. Click **Settings** > **Pages** (in the left sidebar).
3. Under **Branch**, select `main` and folder `/ (root)`.
4. Click **Save**.
5. Your site will immediately be live at:
   `https://arthurbond.github.io/wonderbeandraws/`

### 2. Connect Your Custom Domains (`wonderbean.com.au` / `wonderbean.au`)
When you are ready to point your purchased domain:
1. In **Settings > Pages > Custom domain**, enter `wonderbean.com.au` (or your chosen primary domain) and save. (This creates a `CNAME` file in the repo).
2. In your DNS provider (where you bought the domain):
   - **Apex domain (`@`) A records**:
     - `185.199.108.153`
     - `185.199.109.153`
     - `185.199.110.153`
     - `185.199.111.153`
   - **Subdomain (`www`) CNAME record**:
     - `arthurbond.github.io.`
3. Check the **Enforce HTTPS** box in GitHub Pages settings.
