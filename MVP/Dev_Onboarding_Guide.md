# Developer Onboarding Guide

Welcome to the UNITY repo. Here's how to get started:

## 1. Clone the Repo
```bash
git clone https://github.com/YOUR-USERNAME/unity-vault.git
```

## 2. Install Dependencies
Navigate to the `UI/` folder and run:
```bash
npm install
npm run dev
```

## 3. Contract Environment
- Contracts in `/Contracts`
- Use Hardhat or Foundry
- Environment setup: `.env` file + local keys

## 4. Branching Strategy
- `main` = stable code
- `dev` = working branch
- Feature branches: `feature/vault-redemption`, `feature/ui-wallet`

## 5. PR Reviews
- Always open a Pull Request to `dev`
- At least one peer review required