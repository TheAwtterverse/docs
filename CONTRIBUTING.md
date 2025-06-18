# 🛠 Contribution Guidelines

These guidelines apply to all Unity/VRChat tool repositories in this organization.

---

## 📌 Versioning

We use Semantic Versioning: `x.y.z`

- `x` – Major (breaking changes)
- `y` – Minor (new features, backwards compatible)
- `z` – Patch (bugfixes and tweaks)

Beta versions use the format: `1.2.4-beta.1`

See [Versioning details →](./VERSIONING.md)

---

## ✅ Review & Release Approval

All versions must be reviewed **in Discord** by the beta-testing group.

### Release flow:
1. Prepare your changes.
2. Bump the version + update changelog.
3. Share beta build in Discord test channel.
4. After testing, wait for **staff approval**.
5. Once approved, proceed with release.

> ⚠️ No contributor should publish packages without staff team approval.

---

## 🧪 Testing with VRChat Creator Companion

- Beta versions should be clearly marked and **not pushed to `latest`**.
- Use `-beta.n` tags and test within VCC via Discord-shared builds.

---

## 🗃️ Branching

- `main` or `release`: stable
- `develop`: active development
- `feature/*`: feature branches
- `hotfix/*`: urgent fixes

---

## 📝 Commits

Use [Conventional Commits](https://www.conventionalcommits.org/):
- `feat: add scene validation tool`
- `fix: resolve crash when importing avatar`
- `chore: update metadata`
