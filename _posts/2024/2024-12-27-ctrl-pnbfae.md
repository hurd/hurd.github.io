---
title: "ctrl pnbfae"
layout: post
subtitle:
gh-repo:
gh-badge:
comments: true
mathjax: true
cover-img: /assets/img/fishermen-at-sea.jpg
share-img: 
thumbnail-img: ""
date: "2024-12-27"
author: Hurd
categories: 
  - "hack"
tags: 
  - "karabiner"
  - "karabiner-element"
  - "mac-osx"
  - "단축키"
  - "키보드"
---

[Emacs](https://en.wikipedia.org/wiki/Emacs)를 사랑하던 사람이 `ctrl+pnbfae` 단축키를 버릴 수는 없다. 맥북에서 스크리브너로 글을 쓰다보면, 한글 입력 중인 상태에서 `ctrl+a` 가 `ctrl+ㅁ` 으로 인식되어 단축키가 무시되는 문제가 생긴다. 영문입력 상태로 변경해야 제대로 인식되는데 이게 여간 불편한 게 아니었다. 적절한 해법을 찾아보다가 결국 [Karabiner-Element](https://karabiner-elements.pqrs.org/)를 설치.

```
$ brew update
$ brew install --cask karabiner-elements
```

추가 설정.

- Simple Modifications ➡️ Logi POP Keys ➡️ caps\_lock ➡️ left\_control

- Complex Modifications ➡️ Add predefined rule
    - Left\_Ctrl + p/n/b/f/a/e to up/down/left/right/home/end
    
    - Change Won to grave accent (\`) in Korean layout
