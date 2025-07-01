---
layout: post
title: coming soon
subtitle: 스마트팜 혁신을 위한 차세대 로봇
tags: [온실로봇, 스마트팜, 2025]
comments: true
author: AI Lab
---


## 온실로봇 2025 프로젝트

이 페이지는 2025년 온실로봇 프로젝트의 데모와 정보를 공유합니다.

### 프로젝트 개요
온실로봇 2025는 스마트팜 환경에서 자동으로 작물 상태를 모니터링하고, 급수 및 환경 제어를 수행하는 차세대 로봇입니다.

### 주요 기능
- 온실 내 자율 주행
- 작물 상태 실시간 영상 분석
- 자동 급수 및 환경 조절
- 원격 제어 및 모니터링

### 데모 영상
<iframe width="560" height="315" src="https://www.youtube.com/embed/4TKjNrIksCQ" frameborder="0" allowfullscreen></iframe>

### 프로젝트 이미지
![온실로봇 데모](/assets/img/path.jpg)

### 요약
본 프로젝트는 2025년 6월 기준으로 시범 운영 중이며, 스마트팜 혁신을 목표로 하고 있습니다.

Here's a code chunk:

~~~
var foo = function(x) {
  return(x + 5);
}
foo(3)
~~~

And here is the same code with syntax highlighting:

```javascript
var foo = function(x) {
  return(x + 5);
}
foo(3)
```

And here is the same code yet again but with line numbers:

{% highlight javascript linenos %}
var foo = function(x) {
  return(x + 5);
}
foo(3)
{% endhighlight %}

## Boxes
You can add notification, warning and error boxes like this:

### Notification

{: .box-note}
**Note:** This is a notification box.

### Warning

{: .box-warning}
**Warning:** This is a warning box.

### Error

{: .box-error}
**Error:** This is an error box.

## Local URLs in project sites {#local-urls}

When hosting a *project site* on GitHub Pages (for example, `https://USERNAME.github.io/MyProject`), URLs that begin with `/` and refer to local files may not work correctly due to how the root URL (`/`) is interpreted by GitHub Pages. You can read more about it [in the FAQ](https://beautifuljekyll.com/faq/#links-in-project-page). To demonstrate the issue, the following local image will be broken **if your site is a project site:**

![Crepe](/assets/img/crepe.jpg)

If the above image is broken, then you'll need to follow the instructions [in the FAQ](https://beautifuljekyll.com/faq/#links-in-project-page). Here is proof that it can be fixed:

![Crepe]({{ '/assets/img/crepe.jpg' | relative_url }})

<details markdown="1">
<summary>Click here!</summary>
Here you can see an **expandable** section
</details>
