# 📌 Versioning

We use **Semantic Versioning**: `x.y.z[-beta.n]`

## 🎯 Definitions

- **Major (`x`)** – Breaking changes (API changes, refactors)
- **Minor (`y`)** – New features, backwards compatible
- **Patch (`z`)** – Bugfixes and small adjustments

## 🧪 Beta Releases (Pre-releases)

Beta versions use a suffix like `-beta.1`:

- `1.3.0-beta.2`: testing a minor feature
- `2.0.0-beta.1`: testing a breaking rewrite
- `1.2.4-beta.3`: patch fix under testing

> Never tag a beta version as `latest` for VCC.

---

## 💡 Examples
#### Major	`1.0.0` → `2.0.0`
- Rewriting the tool's API to use ScriptableObjects instead of MonoBehaviours, breaking existing integration.
- Changing the method signatures used by Udon or editor tooling.
- Renaming or removing a public class or namespace used by world creators.

#### Minor	`2.3.0` → `2.4.0`	
- Adding a new editor window for VRChat avatar optimization.
- Adding support for a new Unity version (e.g., 2023 LTS), but keeping compatibility.
- Introducing a new feature toggle in the settings panel (non-breaking).

#### Patch	`2.4.1` → `2.4.2`	
- Fixing a null reference exception when clicking a button in the editor UI.
- Adjusting default values in generated UdonBehaviours without changing the API.
- Fixing layout bugs in the Unity Inspector using EditorGUILayout.

> 🔧 Patch updates can include optimizations or typo fixes in logs/tooltips, as long as they don’t change user-facing behavior or break integrations.
