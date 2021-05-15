---
title: React-Redux Paint
subtitle: Paint, design windows XP
date: 2021-11-11
slug: react-design-paint
author: Diego22
rating: 4
coverImage: https://import.cdn.thinkific.com/335268/llo44iPiRBCsYnf3wYEk_c%23_Logo.jpg
---

## Movie_Portfolio_Web_Developer_№17: React-Redux | Paint-XP

``` tsx
const onProjectSave = async () => {
    const file = await getCanvasImage(canvasRef.current)
    if (!file) {
      return
    }
    const thumbnail = await getBase64Thumbnail({ file, scale: 0.1 })
    dispatch(saveProject(projectName, thumbnail))
    setProjectName("")
    dispatch(hide())
  }
```


```
https://www.youtube.com/watch?v=_cvBYDlYCos

```