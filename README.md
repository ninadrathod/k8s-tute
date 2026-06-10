# Kubernetes — Complete Tutorial from Scratch

A beginner-friendly, single-page Kubernetes tutorial covering every core concept with diagrams, code examples, and MCQ quizzes. Built with pure HTML, CSS, and JavaScript — no frameworks required.

## 📖 What's Covered

| Section | Topic |
|---------|-------|
| 0 | Prerequisites (Linux, Docker, YAML) |
| 1 | What is Kubernetes? |
| 2 | Kubernetes Architecture (Control Plane & Worker Nodes) |
| 3 | Pods |
| 4 | ReplicaSets |
| 5 | Deployments & Rolling Updates |
| 6 | Services (ClusterIP, NodePort, LoadBalancer) |
| 7 | Namespaces |
| 8 | ConfigMaps & Secrets |
| 9 | Volumes & PersistentVolumeClaims |
| 10 | Ingress |
| 11 | Health Probes (Liveness, Readiness, Startup) |
| 12 | Resource Requests & Limits |
| 13 | StatefulSets |
| 14 | DaemonSets |
| 15 | Jobs & CronJobs |
| 16 | RBAC |
| 17 | Helm |

---

## 🚀 Publishing on GitHub Pages

### Step 1 — Make the repository public (required for free GitHub Pages)

> **GitHub Pages is free for public repositories.** Private repository GitHub Pages requires a GitHub Pro, Team, or Enterprise account.

1. Go to your repository on GitHub: `https://github.com/<your-username>/k8s-tute`
2. Click **Settings** (top navigation bar of the repo)
3. Scroll down to the **Danger Zone** section at the bottom
4. Click **Change repository visibility** → **Make public**
5. Type the repository name to confirm, then click **I understand, make this repository public**

> ✅ If you already have a **GitHub Pro/Team/Enterprise** account, you can skip Step 1 — Pages works on private repos too. Jump straight to Step 2.

---

### Step 2 — Enable GitHub Pages

1. In your repository, click **Settings**
2. In the left sidebar, click **Pages** (under *Code and automation*)
3. Under **Source**, select **Deploy from a branch**
4. Under **Branch**, choose `main` (or `master`) from the dropdown
5. For the folder, select `/ (root)` — this is where `index.html` lives
6. Click **Save**

---

### Step 3 — Wait for deployment (~1–2 minutes)

GitHub Actions will automatically build and deploy your site. You can monitor progress:

1. Go to the **Actions** tab of your repository
2. Look for a workflow called **pages-build-deployment**
3. Wait for it to show a green ✅ checkmark

---

### Step 4 — Visit your live tutorial

Your site will be available at:

```
https://<your-github-username>.github.io/k8s-tute/
```

For example, if your GitHub username is `janesmith`:
```
https://janesmith.github.io/k8s-tute/
```

> The URL is shown directly on the **Settings → Pages** page once deployment completes.

---

## 🛠️ Local Development

No build step needed — open `index.html` directly in any browser:

```bash
# macOS
open index.html

# Linux
xdg-open index.html

# Or simply drag index.html into your browser
```

---

## 📁 Project Structure

```
k8s-tute/
├── index.html   # The complete tutorial (self-contained)
└── README.md    # This file
```

All CSS, JavaScript, and SVG diagrams are embedded in `index.html`. The only external dependencies are:
- Google Fonts (Inter + Fira Code) — for typography
- Prism.js (CDN) — for syntax highlighting

Both load from CDN and require an internet connection to display correctly.

---

## 🔄 Updating the Tutorial

1. Edit `index.html` locally
2. Commit and push to `main`:

```bash
git add index.html
git commit -m "Update tutorial content"
git push origin main
```

GitHub Pages will automatically redeploy within ~1–2 minutes.

---

## 📄 License

This tutorial is open-source and free to use for learning purposes.
