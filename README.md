# Soft Cravings website

Every Bite, A Little Happiness. Orders go to WhatsApp (0810 923 7627).

## Host on GitHub Pages
1. Create a new repository on github.com (e.g. `soft-cravings`), set to Public.
2. Click **Add file > Upload files** and drag in everything from this folder: `index.html`, `images` folder, `.nojekyll`, `README.md`. Commit.
3. Go to **Settings > Pages**. Under Source choose **Deploy from a branch**, branch `main`, folder `/ (root)`, Save.
4. After about a minute your site is live at `https://YOUR-USERNAME.github.io/soft-cravings/`.

(Netlify also works: drag the folder onto app.netlify.com/drop.)

## Edit products, prices and settings
Open `index.html` on GitHub, click the pencil, and find `EDIT YOUR MENU BELOW`.
- `DEF` is the product list: change `name`, `desc`, `price` (naira, numbers only), `cat` (Cakes, Pastries, Small Chops, Cupcakes, Desserts), `img` (a photo name from the images folder), `sizes`, `cake:1` for cake options, `pop:1` to show under Popular.
- `SETD` holds the Friday order deadline (`deadline`), delivery charge (`fee`), pickup info (`pickup`), Instagram handle (`insta`) and offers (`promos`).
- Prices are sample prices until you replace them.
- To add a photo: upload it into the `images` folder, then use its name (e.g. `images/newcake.jpg`) as `img`.
Commit changes and the site updates in a minute or two.
