# 📘 Math-Programmer

An experimental **math programming environment** that combines:

- 📝 **Editor** (React + Monaco) for writing code and math  
- 🎨 **Renderer** for LaTeX/Asymptote outputs, including animations  
- ⚙️ **API services** for authentication, storage, and premium downloads  
- 📦 **Shared packages** (UI components, utilities, configs)

## 🚀 Monorepo Layout
- `apps/` → core applications (editor, renderer, backend API)  
- `packages/` → shared libraries (UI, utils, configs)  
- `docker/` → container configs for deployment  

## 📦 Tech Stack
- **Frontend** → React + Tailwind + Monaco Editor  
- **Backend** → Node.js + Express  
- **Containers** → Docker, orchestrated later with Compose/Kubernetes  
- **Workspace management** → Yarn workspaces / Turborepo (planned)  

---

## 🔧 Getting Started
```bash
# install deps
npm install

# run dev server (example, editor app)
cd apps/editor && npm start
