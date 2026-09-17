# Profile template maintenance

This repository stores a reusable GitHub profile README and review checklists.
The live profile belongs to [mrsddq](https://github.com/mrsddq/mrsddq).

## Refresh the template

1. Compare [profile/README.md](../profile/README.md) with the live profile.
2. Follow the [refresh checklist](PROFILE_REFRESH_CHECKLIST.md) and confirm dates,
   titles and numerical claims against the owner's source records.
3. Use the [project selection guide](pinned-repos.md) to choose relevant evidence.
4. Open every changed project link and check that its description matches the code.

```bash
make verify
```

This checks whitespace in the working diff; there is no application test suite.
Changing this template does not update the live profile or repository pins.
