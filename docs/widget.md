# 控件文档
By cym919 2025/3/31

## 简介

这里存放的是cym919的CoCo控件文档


## 作者

<script setup>
import { VPTeamMembers } from 'vitepress/theme'

const members = [
  {
    name: 'cym919',
    title: '建站+文档编写',
    avatar: '/avatar.png',
    links: [
      { icon: 'github', link: 'https://github.com/cym919' },
      { icon: 'bilibili', link: 'https://space.bilibili.com/401652755' }
    ]
  },
]
</script>

<VPTeamMembers size="medium" :members="members" />

## Custom Containers

**Input**

```md
::: info
This is an info box.
:::

::: tip
This is a tip.
:::

::: warning
This is a warning.
:::

::: danger
This is a dangerous warning.
:::

::: details
This is a details block.
:::
```

**Output**

::: info
This is an info box.
:::

::: tip
This is a tip.
:::

::: warning
This is a warning.
:::

::: danger
This is a dangerous warning.
:::

::: details
This is a details block.
:::