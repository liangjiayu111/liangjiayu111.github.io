# Jiayu Liang's Academic Homepage

Personal homepage for Jiayu Liang (梁佳钰), an undergraduate student at Harbin Institute of Technology studying Big Data Management and Application.

Contact: jiayu_liang@stu.hit.edu.cn

## GitHub Pages

Repository: `liangjiayu111/liangjiayu111.github.io`

Public homepage: https://liangjiayu111.github.io/

`site.zip` contains the complete static export of a customized PRISM site, including the photo and bilingual content. The `.github/workflows/deploy.yml` workflow unpacks it and deploys it to GitHub Pages. In Settings → Pages, keep Source set to **GitHub Actions**.

`source.zip` preserves the editable PRISM source without Git metadata, dependencies, or hosting credentials. To add publications or change your profile, unpack it, edit `content/` and `content_zh/`, run `npm ci` and `npm run build`, then zip the contents of `out/` as `site.zip`. Replacing `site.zip` on the `main` branch automatically updates the homepage. Retain `.nojekyll` in the static export.

PRISM: https://github.com/xyjoey/PRISM

The PRISM MIT license is preserved in `LICENSE`.
