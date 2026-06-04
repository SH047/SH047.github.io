# Shreyas S Rai — Portfolio

Personal portfolio site hosted via GitHub Pages.

🌐 **Live at:** `https://SH047.github.io`

## Folder Structure

```
portfolio/
├── index.html          ← main portfolio file
├── README.md
├── assets/
│   └── Shreyas_S_Rai_Resume.pdf
└── images/
    ├── profile/
    │   └── profile.jpeg         ← Your photo
    └── projects/
        ├── amr.jpeg             ← Wheeled AMR project photo
        ├── echoq.jpeg           ← ECHO-Q quadruped photo
        ├── arraybutton.png      ← ArrayButton/IISc project photo
        ├── waam.jpeg            ← IIT Dharwad WAAM cell photo
        └── emg.jpeg             ← EMG prosthetic arm photo
```

## How to Add Your Photos

1. Take photos / screenshots of each project
2. Rename them exactly as shown above
3. Drop them into the `images/projects/` folder
4. Push to GitHub — they appear automatically

## How to Deploy (GitHub Pages)

```bash
# 1. Create repo named exactly: SH047.github.io
#    Go to github.com/new → name it "SH047.github.io" → Public → Create

# 2. Clone it
git clone https://github.com/SH047/SH047.github.io.git
cd SH047.github.io

# 3. Copy all portfolio files in
cp -r /path/to/portfolio/* .

# 4. Push
git add .
git commit -m "launch: portfolio site"
git push origin main

# 5. Enable GitHub Pages
#    Repo → Settings → Pages → Source: main → / (root) → Save

# Done — live at https://SH047.github.io in ~60 seconds
```

## Updating Later

```bash
# Edit index.html, add new project images, then:
git add .
git commit -m "update: added new project"
git push origin main
```
