# Blog Graphics Storage

This repository serves as a cloud-based graphics storage solution for use with blogs, especially when the blog platform does not natively support SVG graphics. For example, [Blogger.com](https://www.blogger.com/) does not allow direct uploads or embedding of SVG files in posts and pages. By hosting SVG (and other) graphics here, you can link to them from your blog using their GitHub Pages URLs.

## Why Use This Repository?

- **SVG Support**: Store and serve SVG graphics, which are often unsupported by popular blogging platforms.
- **Public Access via GitHub Pages**: All graphics stored here will have publicly available URLs through GitHub Pages.
- **Version Control**: Easily update, track, and manage changes to your graphics.
- **Cloud-Hosted**: No need for paid hosting services—GitHub provides reliable cloud storage.

## How to Use

1. **Upload Graphics**
   - Add your SVG (or other image) files to the `docs` folder in this repository. You can organize them into subfolders if needed.

2. **Make the Repository Public via GitHub Pages**
   - Go to your repository on GitHub.
   - Click on the **Settings** tab.
   - In the sidebar, select **Pages** (or scroll down to the "GitHub Pages" section).
   - Under **Source**, select the branch you want to use (usually `main` or `master`), and set the folder to `/docs`.
   - Click **Save**.
   - GitHub will provide you with a public URL for your site (e.g., `https://<username>.github.io/<repo>/`).
   - Your graphics will now be accessible at URLs such as:
     ```
     https://<username>.github.io/<repo>/<path-to-graphic>.svg
     ```
     For example, a file at `docs/logo.svg` will be available at:
     ```
     https://<username>.github.io/<repo>/logo.svg
     ```

3. **Embed in Your Blog**
   - Use the GitHub Pages URL for your SVG in your blog post or page.
   - Example for embedding an SVG image in HTML:
     ```html
     <img src="https://<username>.github.io/<repo>/logo.svg" alt="Description">
     ```
   - Note: Some blogging platforms may restrict loading SVGs directly. If you encounter issues, consider converting SVGs to PNGs or use an `<object>` or `<iframe>` tag.

## Best Practices

- **Organize Graphics**: Group images by topic or post for easier management within the `docs` folder.
- **Descriptive Filenames**: Use clear, descriptive names for your SVG files.
- **Optimize SVGs**: Minimize file size by removing unnecessary metadata.
- **Licensing**: If your graphics are reusable or open-source, consider including a LICENSE file.

## Disclaimer

- **Public Access**: All files in this repository are publicly accessible. Do not upload sensitive or private images.
- **GitHub Pages Limits**: GitHub Pages is intended for static content. For large-scale use or high bandwidth, consider a dedicated CDN.

---

Happy blogging!
