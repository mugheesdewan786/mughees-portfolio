# Mughees Dewan — Portfolio

Personal site for Pakistani and Gulf hiring. Astro, no UI framework.

## Run

Needs Node 22+. This machine has 24 via nvm:

```bash
cd ~/mughees-portfolio
nvm use
npm install
npm run dev
```

Open [http://localhost:4321](http://localhost:4321).

## Deploy (Vercel)

```bash
npm i -g vercel
cd ~/mughees-portfolio
vercel
```

Or push to GitHub and import the repo in Vercel. Framework preset: Astro. Output: static.

## Content rules (do not "improve" away)

- 45 farmers is the first credit cohort. 3,069 acres is that same rice programme (Jhang and Chiniot). 40,000+ is platform users. Different numbers.
- PKR 150M is across those 45 farmers / 3,069 acres. Do not present 40,000 users as borrowers.
- Dawn article is the MoU (12 Feb 2026). Production go-live is 5 July 2026. Faysal financing: about seven days to same day. State all three.
- Licensing: more than a month to under three days; ~95% fewer physical visits; 40,000+ paper backlog. 200,000+ is practitioners on the digital register, not annual applications.
- Title is "Product & delivery · 6 yrs", not "Product Manager · 6 yrs".
- The two caveats stay: recovery still in progress; "I build with AI tools, I haven't owned an ML product."
- Do not publish the PKR 250M EWR proposal, salary history, or Chevening career-plan copy on this site.

## Photos

| File | Use |
|------|-----|
| `public/photos/headshot-wide.jpg` | Hero |
| `public/photos/casual.png` | Closing section |
| `public/photos/headshot.jpg` | Spare closer crop |
| `public/photos/portrait.jpg` | Spare navy-blazer standing |

## CV

Drop a one-page PDF at `public/Mughees_Dewan_CV.pdf` and add a button in `Hero.astro` / `Close.astro` if you want a download. The `.docx` sources live in the earlier Claude portfolio zip under `cv/`.
