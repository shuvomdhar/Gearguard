# GearGuard

A comprehensive gear management system developed as a final year project.

## 📋 Project Overview

GearGuard is a modern web application designed to help users manage and track their gear efficiently. The project is built with a React frontend and will include a robust backend system.

## 🏗️ Project Structure

```
GearGuard/
├── Frontend/
│   └── gearguard-frontend/          # React application
│       ├── src/
│       ├── public/
│       ├── package.json
│       └── ...
├── Backend/                         # Backend application (to be added)
├── docs/                           # Project documentation
├── README.md
└── ...
```

## 🌿 Branching Strategy

This project follows a structured branching strategy to ensure smooth collaboration between frontend and backend teams:

### Main Branches

- **`main`** - Production-ready code. All final merges happen here.
- **`frontend`** - Frontend development branch. All React/UI related work happens here.
- **`backend`** - Backend development branch. All server-side development happens here.

### Workflow

1. **Initial Setup**: Currently, all code is in the `main` branch
2. **Development Phase**: 
   - Frontend team creates and works on the `frontend` branch
   - Backend team creates and works on the `backend` branch
3. **Integration Phase**: When both frontend and backend are ready, they will be merged back to `main`

## 🚀 Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn
- Git

### Frontend Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/shuvomdhar/Gearguard.git
   cd Gearguard
   ```

2. **Create and switch to frontend branch** (Frontend team)
   ```bash
   git checkout -b frontend
   ```

3. **Navigate to frontend directory**
   ```bash
   cd Frontend/gearguard-frontend
   ```

4. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

5. **Start development server**
   ```bash
   npm start
   # or
   yarn start
   ```

### Backend Setup

1. **Create and switch to backend branch** (Backend team)
   ```bash
   git checkout -b backend
   ```

2. **Create backend directory structure**
   ```bash
   mkdir Backend
   cd Backend
   # Initialize your backend project here
   ```

3. **Set up your backend framework** (Node.js/Express etc.)

## 👥 Team Guidelines

### For Frontend Team

- **Branch**: Work exclusively on the `frontend` branch
- **Directory**: All frontend changes should be in `Frontend/gearguard-frontend/`
- **Commits**: Use descriptive commit messages with prefix `[Frontend]`
- **Example**: `[Frontend] Add user authentication component`

### For Backend Team

- **Branch**: Work exclusively on the `backend` branch
- **Directory**: All backend changes should be in `Backend/`
- **Commits**: Use descriptive commit messages with prefix `[Backend]`
- **Example**: `[Backend] Implement user authentication API`

## 📝 Development Guidelines

### Commit Message Format
```
[Team] Brief description of changes

Detailed description if necessary
- Feature added
- Bug fixed
- Improvement made
```

### Pull Request Process

1. **Create feature branches** from your team's main branch:
   ```bash
   # For frontend team
   git checkout frontend
   git checkout -b feature/user-dashboard
   
   # For backend team
   git checkout backend
   git checkout -b feature/user-api
   ```

2. **Make your changes** and commit regularly

3. **Push to remote** and create pull request to your team's branch

4. **Code review** by team members before merging

### Branch Protection Rules

- Direct pushes to `main` branch are restricted
- All changes must go through pull requests
- Code review required before merging
- Automated tests must pass (when implemented)

## 🔧 Available Scripts

### Frontend Scripts (in `Frontend/gearguard-frontend/`)

- `npm start` - Runs the app in development mode
- `npm test` - Launches the test runner
- `npm run build` - Builds the app for production
- `npm run eject` - Ejects from Create React App (use with caution)

### Common Git Commands

```bash
# Switch between branches
git checkout main
git checkout frontend
git checkout backend

# Pull latest changes
git pull origin <branch-name>

# Push your changes
git push origin <branch-name>

# Merge branches (for project leads)
git checkout main
git merge frontend
git merge backend
```

## 📚 Documentation

- **Frontend Documentation**: `Frontend/gearguard-frontend/README.md`
- **Backend Documentation**: `Backend/README.md` (to be created)
- **API Documentation**: `docs/api.md` (to be created)

## 🛠️ Technologies Used

### Frontend
- React.js
- HTML5/CSS3
- JavaScript (ES6+)
- [Add other frontend technologies as you implement them]

### Backend
- [To be determined - Node.js/Express etc.]
- [Database - MongoDB, PostgreSQL, etc.]
- [Add other backend technologies as you implement them]

## 📋 Project Timeline

1. **Phase 1**: Initial setup and basic React app ✅
2. **Phase 2**: Frontend development (UI/UX, components, routing)
3. **Phase 3**: Backend development (API, database, authentication)
4. **Phase 4**: Integration and testing
5. **Phase 5**: Deployment and final documentation

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch from the appropriate team branch
3. Commit your changes with descriptive messages
4. Push to your branch
5. Create a Pull Request with detailed description

## 📄 License

This project is developed as part of a final year academic project.

---

**Note**: This README will be updated as the project progresses. Make sure to check for updates regularly and keep your local repository in sync with the remote repository.