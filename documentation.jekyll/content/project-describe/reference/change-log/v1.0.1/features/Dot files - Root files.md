---
layout: page
title: Dot files - Root files
permalink: /language/reference/versioning/v101/features/feature-2/
exclude: true
---
<br>_FEATURE: Dot files are root files_<br>

How do we determine which file's productions are the root ones to start building the productions from, when translating? Well, it is the one that comes first alphabetically, as it will be picked up  and parsed first. However, it will be good if we can explicitly specify a root file for a parse operation, and this is what we do with this feature.<br>

The root file in a parse-folder operation is a file in the root folder that either contains the `project-root` directive, or has a filename starting with a dot - `.`
When parsing multiple strings, always the first one is the root. If having multiple files that start with a dot, the first one alphabetically will be picked up as root.<br>

The project-root directive have not been implemented yet - it will be the subject of another feature, in the future. However, it should take precedence over the dot start of the filename method, as this is a way for users to choose not to use that feature.<br>

<br>
### Links
[Back](/language/reference/versioning/v101/transpiler101/)