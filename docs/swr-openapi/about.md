---
title: About swr-openapi
description: swr-openapi Project Goals and contributors
---
<script setup>
  import { VPTeamMembers } from 'vitepress/theme';
  import contributors from '../data/contributors.json';
</script>

# {{ $frontmatter.title }}

## Project Goals

1. Types should be strict and inferred automatically from OpenAPI schemas with the absolute minimum number of generics needed.
2. Respect the original `swr` APIs while reducing boilerplate.
3. Be as light and performant as possible.

## Contributors

This library wouldn’t be possible without all these amazing contributors:

<VPTeamMembers size="small" :members="contributors['swr-openapi']" />
