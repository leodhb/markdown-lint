---
title: MD023 - Headers must start at the beginning of the line
tags:  [headers, spaces]
alias: header-start-left
---

This rule is triggered when a header is indented by one or more spaces:

    Some text

      # Indented header

To fix this, ensure that all headers start at the beginning of the line:

    Some text

    # Header

Rationale: Headers that don't start at the beginning of the line will not be
parsed as headers, and will instead appear as regular text.
