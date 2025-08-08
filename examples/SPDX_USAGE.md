# How to Use the SPDX Identifier for Stephenson-NC

## What is SPDX?
SPDX (Software Package Data Exchange) is a standard format for identifying software licenses.  
Using SPDX headers makes it easier for humans and automated tools to understand and comply with your license terms.

## Stephenson-NC SPDX Identifier
Identifier: Stephenson-NC  
Version: 1.0 (2025)  
Canonical license text: https://github.com/Stephenson-Software/stephenson-nc-license

## Adding to Source Files
Add the following header at the top of every source file:

// SPDX-License-Identifier: Stephenson-NC  
// Copyright (c) 2025 Daniel McCoy Stephenson  
//  
// This file is part of a Stephenson Software project licensed under the  
// Stephenson Software Non-Commercial License (Stephenson-NC).  
// See https://github.com/Stephenson-Software/stephenson-nc-license for details.

## Adding to README.md
In your project README, add:

**License:** Stephenson-NC © 2025 Daniel McCoy Stephenson  
See https://github.com/Stephenson-Software/stephenson-nc-license for details.

## Adding to package metadata (optional)
For projects with package metadata (e.g., package.json, pyproject.toml, Maven pom.xml), set the license field to `Stephenson-NC` and include a link to this repository.

## Benefits of Using SPDX
- Standardized license identification.
- Easier integration with compliance and scanning tools.
- Makes the license terms clear to collaborators and users.
