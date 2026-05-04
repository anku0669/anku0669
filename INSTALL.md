# 🚀 Install — @anku0669 Profile v4 ELITE

## 1. Drop these files into your `anku0669/anku0669` repo

```
README.md                           ← top of repo
assets/matrix-banner.svg            ← animated header
assets/terminal-boot.svg            ← terminal boot SVG
assets/matrix-footer.svg            ← animated footer
.github/workflows/snake.yml         ← snake animation
.github/workflows/profile-3d.yml    ← 3D contribution graph
.github/workflows/metrics.yml       ← metrics dashboard
```

The fastest way: **drag the unzipped folder contents into your repo on GitHub.com → Add file → Upload files** (preserves folder structure).

Or via git CLI:
```bash
git clone https://github.com/anku0669/anku0669.git
cd anku0669
unzip -o /path/to/profile_v4_ELITE.zip
git add .
git commit -m "feat: AI hacker dark theme v4"
git push
```

## 2. Run the workflows once (manually)

Open your repo → **Actions tab** → for each workflow click **Run workflow**:

- ✅ Generate Snake Animation         → creates `output` branch with snake SVG
- ✅ Generate 3D Contribution Graph   → creates `profile-3d-contrib/` folder
- ✅ Generate Metrics Dashboard       → creates `github-metrics.svg`

After all three succeed, your README will display every dynamic widget automatically.

## 3. (Optional) Better metrics

For private contribution stats and richer achievements, create a Personal Access Token:
- GitHub → Settings → Developer settings → Personal access tokens → **Fine-grained**
- Permissions: `read:user`, `repo`, `read:org`
- Save it as a repo secret named `METRICS_TOKEN` in your `anku0669/anku0669` repo

Without this, the workflow falls back to `GITHUB_TOKEN` (still works, public-only).

## 4. Done — refresh your profile

Visit https://github.com/anku0669 — top-notch AI hacker mode activated. 🟢
