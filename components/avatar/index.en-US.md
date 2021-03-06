---
category: Components
type: Data Display
title: Avatar
cover: https://gw.alipayobjects.com/zos/antfincdn/aBcnbw68hP/Avatar.svg
---

Avatars can be used to represent people or objects. It supports images, `Icon`s, or letters.

## API

| Property | Description | Type | Default | Version |
| --- | --- | --- | --- | --- |
| icon | custom icon type for an icon avatar | ReactNode | - |  |
| shape | the shape of avatar | `circle` \| `square` | `circle` |  |
| size | the size of the avatar | number \| `large` \| `small` \| `default` | `default` |  |
| src | the address of the image for an image avatar | string | - |  |
| srcSet | a list of sources to use for different screen resolutions | string | - |  |
| alt | This attribute defines the alternative text describing the image | string | - |  |
| onError | handler when img load error, return false to prevent default fallback behavior | () => boolean | - |  |
| gap | Letter type unit distance between left and right sides | number | 4 | 4.3.0 |

> Tip: You can set `icon` or `children` as the fallback for image load error, with the priority of `icon` > `children`
