## Overview

I am developing this Portable Registry Over Git Information System (PROGit-IS) because I wanted to make a web-based app harnessing the power of Git that handles information registries without requiring explicit databases to maintain its portability.  It must handle data items in plain-text only.  It must handle registry items in a flexible manner, with tags and customizable filter sets.

## Design Considerations

### Comments
1. Newer comment threads should always float on top but replies to comment-threads should lay naturally from top to bottom in a threaded manner.
2. Each comment thread should be collapsible and expandable to hide and/or expose all replies thereto.

###

## Get column order from .config directory.  Column sequence file columns.cfg should contain names that correspond to directories from base folder.  If alternative column sequences are desired, these can be kept in columns-ii.cfg where ii is a 2-digit sequential number starting from 01. 
## 
##

## .filteredlists contains configurable filter sets for listing registries in a flexible manner and according to user preference.  Example: filter by Tags containing "Project ABC" and by Reference Year="2020" and by Status="Open"
## .log directory contains audit information regarding who edited what and when it happened, because the session account will be used to git-commit the entire registry.