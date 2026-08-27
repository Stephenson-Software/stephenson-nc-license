# How to Use the SPDX Identifier for Stephenson-NC

## What is SPDX?
SPDX (Software Package Data Exchange) is a standard format for identifying software licenses.  
Using an SPDX-style header makes the license of a file easy for a reader to spot and gives automated tools a consistent place to look for it.

## Stephenson-NC SPDX Identifier
Identifier: Stephenson-NC  
Version: 1.0 (2025)  
Canonical license text: https://github.com/Stephenson-Software/stephenson-nc-license

`Stephenson-NC` is a custom identifier coined by this repository. It is **not** on the official SPDX License List, so a scanner that encounters it will generally report it as unrecognized rather than resolve it to known terms. The canonical text linked above remains the only statement of what the license permits.

## Adding to Source Files
Add the following header at the top of every source file:

```
// SPDX-License-Identifier: Stephenson-NC
// Copyright (c) 2025 Daniel McCoy Stephenson
//
// This file is part of a Stephenson Software project licensed under the
// Stephenson Software Non-Commercial License (Stephenson-NC).
// See https://github.com/Stephenson-Software/stephenson-nc-license for details.
```

The `//` markers above suit languages that use them. [LICENSE_HEADER.txt](./LICENSE_HEADER.txt) carries a fuller notice with no comment markers at all, ready to be prefixed with whatever marker the target language uses.

## Adding to README.md
In your project README, add:

```
**License:** Stephenson-NC © 2025 Daniel McCoy Stephenson
See https://github.com/Stephenson-Software/stephenson-nc-license for details.
```

## Adding to package metadata (optional)
For projects with package metadata (e.g., package.json, pyproject.toml, Maven pom.xml), set the license field to `Stephenson-NC` and include a link to this repository.

## Benefits of Using SPDX
- Standardized placement and syntax for license identification.
- A consistent field for compliance and scanning tools to read, though those tools cannot resolve `Stephenson-NC` to known terms on their own.
- Makes the license terms clear to collaborators and users.
