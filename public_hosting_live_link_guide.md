# How to Get a Public Shareable Website Link in 30 Seconds

Because I run in a secure sandboxed environment and cannot register external public domains on your behalf, I have compiled your entire **Biomedical Knowledge Graph Explorer** into a single, zero-build **`index.html`** file (`Standalone Biomedical Graph Explorer`).

You can host it for free and get a permanent, shareable HTTPS URL in less than 30 seconds using any of the options below.

---

## Option 1: Instant Drag-and-Drop (No Account or Coding Required)

### **Tiiny.host** or **Netlify Drop**
1. Copy or download the `index.html` file I just generated for you in the editor panel.
2. Go to **[app.netlify.com/drop](https://app.netlify.com/drop)** or **[tiiny.host](https://tiiny.host/)**.
3. Drag and drop your `index.html` file (or a folder containing `index.html`) directly onto the page.
4. It will immediately generate a live public URL (for example, `https://biograph-explorer.netlify.app`) that you can share with professors, reviewers, or teammates.

---

## Option 2: Free Permanent Hosting via GitHub Pages

1. Create a new public repository on **[GitHub](https://github.com/new)** named `biograph-explorer`.
2. Upload the `index.html` file to the root of the repository and commit it.
3. Open your repository's **Settings** $\rightarrow$ **Pages** (on the left sidebar).
4. Under **Build and deployment**, select **Deploy from a branch** and choose `main` / `(root)`, then click **Save**.
5. Within 60 seconds, your live application will be hosted permanently at:
   `https://<your-github-username>.github.io/biograph-explorer/`

---

## Option 3: Instant Live Preview Inside This Workspace

If you want to demonstrate or use the application right now without leaving this window:
1. Select either **`Standalone Biomedical Graph Explorer` (`index.html`)** or **`Biomedical Graph Explorer` (`App.jsx`)** in the file selector on the right.
2. Click the **Preview** button in the top-right corner of the editor panel.