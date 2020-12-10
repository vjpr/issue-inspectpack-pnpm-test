https://github.com/FormidableLabs/inspectpack/issues/151

```
pnpm install
cd packages/cra
npm start
```

Bug:

```
Missing sources: Expected 4, found 0.
Found map: {}
```

Message:

```
Compiled with warnings.

Missing sources: Expected 4, found 0.
Found map: {}

Duplicate Sources / Packages - Duplicates found! ⚠️

* Duplicates: Found 3 similar files across 4 code sources (both identical + similar)
  accounting for 46736 bundled bytes.
* Packages: Found 0 packages with 0 resolved, 0 installed, and 0 depended versions.

* Understanding the report: Need help with the details? See:
  https://github.com/FormidableLabs/inspectpack/#diagnosing-duplicates
* Fixing bundle duplicates: An introductory guide:
  https://github.com/FormidableLabs/inspectpack/#fixing-bundle-duplicates

Search for the keywords to learn more about each warning.
To ignore, add // eslint-disable-next-line to the line before.

```
