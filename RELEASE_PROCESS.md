# 🚦 Release Process

All releases must be approved by the **staff team** after **Discord-based beta testing**.

---

## 📋 Checklist

1. ✅ Finish development in `feature/*` or `hotfix/*`
2. 📦 Bump version in `package.json` or `.vccpackage` manifest
4. 🧪 Share build in Discord test group
5. ⏳ Wait for staff review and feedback
6. ✅ If approved:
   - Merge to `main`
   - Tag version (e.g., `v1.2.3`)
   - Publish to VCC-compatible package registry
7. 📣 Announce release (internal or public)

---

## 🛑 Notes

- Do not skip beta testing or publish without approval.
- Beta builds must use `-beta.n` suffix and **never be tagged as stable**.
