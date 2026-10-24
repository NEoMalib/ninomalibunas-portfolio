# Niño Yuhitco Malibunas — Portfolio

A responsive, static personal portfolio built with HTML5, CSS3, and vanilla JavaScript. It is ready for GitHub Pages and does not require a build step, backend, PHP, or database.

## Preview locally

1. Open this folder (`My Portfolio`) in Visual Studio Code.
2. Install the **Live Server** extension if you do not already have it.
3. Right-click `index.html` and select **Open with Live Server**.
4. The page should open in your browser. Changes to HTML, CSS, or JavaScript reload automatically.

You can also open `index.html` directly in a browser; Live Server is recommended for a more realistic local preview.

## Personalize your portfolio

- **Contact email:** Update both `mailto:` links and the displayed email in `index.html` if your address changes.
- **Resume:** Add your real PDF at `assets/Nino_Malibunas_CV.pdf`. The download link is already in the contact section. No resume file has been fabricated or included.
- **Project screenshots:** Add your own image files under `assets/images/`, for example `autowyns-dashboard.jpg` and `brightlink-network.png`. In `index.html`, replace the corresponding `.project-visual` illustration with an `<img>` using a relative path such as `assets/images/autowyns-dashboard.jpg`, and give the image descriptive `alt` text. Keep the project descriptions factual and use only images you are allowed to publish.
- **3D renders:** Add your own render under `assets/images/`, for example `maya-unreal-render.jpg`, and use it in the 3D project card the same way. The existing CSS drawings are visual placeholders, not screenshots or claims about the projects.
- **Certifications:** The entries in the certification section are marked **VERIFY** and are not presented as earned. Confirm each against your certificate, then edit its name/status or remove the corresponding `.credential-item` from `index.html`.
- **Project details and skills:** Edit the relevant card text and tags in `index.html` to keep the portfolio accurate as your experience grows.

All site assets and links use relative paths so the site can live at a GitHub Pages project URL.

## Publish with GitHub Pages

1. Sign in to your GitHub account and create a new repository for the portfolio (for example, `portfolio`). For the free GitHub Pages plan, make the repository public.
2. Upload the contents of this `My Portfolio` folder to the repository root—not the containing parent folder. Include `index.html`, `style.css`, `script.js`, `README.md`, and `assets/`.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**. Select your default branch (usually `main`) and the `/(root)` folder, then save.
5. Wait for GitHub Pages to finish publishing. The site address will be shown on the Pages settings screen, usually `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`.
6. After later edits, commit or upload the changes to the selected branch; GitHub Pages republishes the site.

Before publishing, review all content and verify certification entries, contact details, project claims, and any images or resume you add.
