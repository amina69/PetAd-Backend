# PetAd Development Workspace 🐾

Welcome to the PetAd development workspace! This is the home for both the frontend and backend repositories.

---

## 📦 Repository Structure

This workspace contains two separate projects:

```
petad-workspace/
├── frontend/          # React + TypeScript + Vite
│   ├── README.md     # Frontend documentation
│   └── CONTRIBUTING.md
│
├── backend/           # NestJS + TypeScript
│   ├── README.md     # Backend documentation
│   └── CONTRIBUTING.md
│
├── package.json       # Workspace scripts
```

---

## 🎯 Want to Contribute?

**Choose the project you want to contribute to:**

### 🎨 **Contributing to Frontend**

👉 **[Read Frontend README](Frontend/README.md)**  
👉 **[Read Frontend CONTRIBUTING.md](Frontend/CONTRIBUTING.md)**

The frontend is built with:
- React
- TypeScript
- Vite
- TailwindCSS
- React Query

**Quick start:**
```bash
cd frontend
npm install
npm run dev
```

---

### ⚙️ **Contributing to Backend**

👉 **[Read Backend README](backend/README.md)**  
👉 **[Read Backend CONTRIBUTING.md](backend/CONTRIBUTING.md)**

The backend is built with:
- NestJS
- TypeScript
- PostgreSQL
- Prisma
- Stellar SDK

**Quick start:**
```bash
cd backend
npm install
docker-compose up -d postgres redis
npx prisma migrate dev
npm run start:dev
```

---

## Focuse on the one you are suppose towork on alone



**Access:**
- Frontend: http://localhost:5173
- Backend: http://localhost:3000
- Prisma Studio: http://localhost:5555
---

## 📚 Documentation by Project

| What You Want to Do | Where to Look |
|---------------------|---------------|
| **Understand the frontend architecture** | [frontend/README.md](frontend/README.md) |
| **Contribute to React components** | [frontend/CONTRIBUTING.md](frontend/CONTRIBUTING.md) |
| **Work on UI/UX** | [frontend/README.md](frontend/README.md) |
| **Understand the backend architecture** | [backend/README.md](backend/README.md) |
| **Contribute to API endpoints** | [backend/CONTRIBUTING.md](backend/CONTRIBUTING.md) |
| **Work on blockchain integration** | [backend/README.md](backend/README.md) |
---

## 🔀 Contribution Workflow

### Frontend Guidelines

Please read **[frontend/CONTRIBUTING.md](frontend/CONTRIBUTING.md)** for:
- ✅ React component structure
- ✅ TypeScript conventions
- ✅ Styling with Tailwind
- ✅ State management patterns
- ✅ Testing components

### Backend Guidelines

Please read **[backend/CONTRIBUTING.md](backend/CONTRIBUTING.md)** for:
- ✅ NestJS module structure
- ✅ Database schema changes (Prisma)
- ✅ API endpoint conventions
- ✅ Authentication patterns
- ✅ Testing APIs

---

## 🛠️ Development Tools

### Shared Tools

- **Docker Desktop** - For PostgreSQL, Redis
- **Git** - Version control
- **Node.js 20+** - Runtime environment

### Frontend Tools

- **VS Code** - Recommended editor
- **Vite** - Build tool
- **ESLint** - Linting
- **Prettier** - Code formatting

### Backend Tools

- **Prisma Studio** - Database GUI
- **Postman/Insomnia** - API testing
- **NestJS CLI** - Code generation
---

## 🎯 Quick Links

### Frontend
- 📖 [Frontend README](frontend/README.md)
- 🤝 [Frontend Contributing Guide](frontend/CONTRIBUTING.md)


### Backend
- 📖 [Backend README](backend/README.md)
- 🤝 [Backend Contributing Guide](backend/CONTRIBUTING.md)

---

## 🎉 Thank You!

Thank you for your interest in contributing to PetAd! Whether you're fixing bugs, adding features, improving documentation, or just spreading the word, we appreciate your help in building a better platform for pet adoption.

**Every contribution matters! 🐶🐱**

---

## 📄 License

Both projects are licensed under the MIT License.

- Frontend: [MIT License](frontend/LICENSE)
- Backend: [MIT License](backend/LICENSE)

---

**Happy coding! 🚀🐾**

Built with ❤️ by the PetAd community
