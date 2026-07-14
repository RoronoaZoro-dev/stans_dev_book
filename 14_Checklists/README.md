# ✅ Checklists

> **Section 14** · Pre-flight checklists for projects, deployments, code reviews, and more.

---

## 📋 Table of Contents

- [Overview](#-overview)
- [What You'll Find Here](#-what-youll-find-here)
- [Checklists](#-checklists)
- [New Project Checklist](#-new-project-checklist)
- [Code Review Checklist](#-code-review-checklist)
- [Pre-Deployment Checklist](#-pre-deployment-checklist)
- [Related Sections](#-related-sections)

---

## 🔍 Overview

Checklists prevent mistakes. Before starting a project, deploying code, or submitting a pull request, use these checklists to make sure nothing is missed. This section contains reusable checklists for every stage of the development lifecycle.

---

## 📂 What You'll Find Here

| Topic | Description |
|-------|-------------|
| New Project Checklist | What to set up before writing code |
| Code Review Checklist | What to check during code reviews |
| Pre-Deployment Checklist | What to verify before going live |
| Security Checklist | Security audit before deployment |
| Performance Checklist | Performance optimization checks |
| Interview Checklist | Pre-interview preparation |
| Release Checklist | Version release process |
| Git Checklist | Branch, commit, and PR best practices |

---

## 📚 Checklists

> 📝 *Detailed checklists will be added here as they are created.*

| # | Checklist | Status |
|---|----------|--------|
| 1 | New Project Setup | ✅ Available Below |
| 2 | Code Review | ✅ Available Below |
| 3 | Pre-Deployment | ✅ Available Below |
| 4 | Security Audit | 🔲 Planned |
| 5 | Performance Optimization | 🔲 Planned |
| 6 | Interview Day | 🔲 Planned |
| 7 | Version Release | 🔲 Planned |
| 8 | API Launch | 🔲 Planned |

---

## 🚀 New Project Checklist

Use this when starting any new project:

### Repository Setup
- [ ] Create GitHub repository
- [ ] Add README.md with project description
- [ ] Add .gitignore (language-specific)
- [ ] Add LICENSE file
- [ ] Set up branch protection rules
- [ ] Create `develop` branch

### Project Configuration
- [ ] Initialize project with package manager
- [ ] Set up folder structure
- [ ] Configure linting (ESLint, Pylint, etc.)
- [ ] Configure formatting (Prettier, Black, etc.)
- [ ] Add environment variable template (.env.example)
- [ ] Set up pre-commit hooks

### Development Setup
- [ ] Create virtual environment (if Python)
- [ ] Install dependencies
- [ ] Set up testing framework
- [ ] Configure CI/CD pipeline
- [ ] Set up database (if needed)
- [ ] Create initial documentation

---

## 🔍 Code Review Checklist

Use this when reviewing pull requests:

### Code Quality
- [ ] Code is readable and well-organized
- [ ] Functions are small and single-purpose
- [ ] Variable names are descriptive
- [ ] No hardcoded values (use constants/env vars)
- [ ] No commented-out code
- [ ] No console.log / print statements in production code

### Logic & Correctness
- [ ] Business logic is correct
- [ ] Edge cases are handled
- [ ] Error handling is proper
- [ ] No infinite loops or recursion issues
- [ ] API responses follow expected format

### Security
- [ ] No sensitive data in code (passwords, API keys)
- [ ] Input validation is present
- [ ] SQL injection prevention
- [ ] XSS prevention
- [ ] Proper authentication/authorization checks

### Performance
- [ ] No unnecessary database queries
- [ ] No N+1 query problems
- [ ] Large data sets are paginated
- [ ] Heavy operations are async where possible

### Testing
- [ ] Unit tests are included
- [ ] Tests cover happy path and edge cases
- [ ] All tests pass
- [ ] Test coverage meets standards

---

## 🚀 Pre-Deployment Checklist

Use this before deploying to production:

### Code
- [ ] All tests pass
- [ ] Code reviewed and approved
- [ ] No merge conflicts
- [ ] Build succeeds without errors
- [ ] Dependencies are up to date

### Configuration
- [ ] Environment variables are set
- [ ] Database migrations are applied
- [ ] API keys and secrets are configured
- [ ] CORS settings are correct
- [ ] SSL/TLS certificates are valid

### Performance & Security
- [ ] Performance benchmarks met
- [ ] Security scan completed
- [ ] No known vulnerabilities
- [ ] Rate limiting is configured
- [ ] Logging and monitoring are active

### Communication
- [ ] Team is notified of deployment
- [ ] Rollback plan is documented
- [ ] Monitoring dashboards are ready
- [ ] On-call engineer is available

---

## 🔗 Related Sections

| Section | Why It's Related |
|---------|-----------------|
| [01 · Project Setup](../01_Project_Setup/README.md) | New project checklist |
| [02 · Git & GitHub](../02_Git_GitHub/README.md) | Git and PR checklists |
| [09 · Cybersecurity](../09_Cybersecurity/README.md) | Security checklists |
| [10 · Cloud & DevOps](../10_Cloud_DevOps/README.md) | Deployment checklists |

---

<p align="center">
  <a href="../README.md">⬅️ Back to Home</a>
</p>
