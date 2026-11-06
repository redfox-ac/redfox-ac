[init]
version = 1

[terminal]
preset = "nord"
theme = "dark"
chrome = "linux"

[[module]]
type = "header"
title = "README.md"
font = "code"

[[module]]
type = "cmd"
cmd = "whoami"
ps = "$"
color = ""
font = "code"

[[module]]
type = "name"
text = "@redfox-ac"
color = "bright-blue"
size = 26
font = "code"

[[module]]
type = "gap"
h = 24

[[module]]
type = "cmd"
cmd = "cat about"
ps = "$"
color = ""
font = "code"

[[module]]
type = "text"
t = "카페라테 마시면서 공부하는 중 — 알고리즘 문제 풀고, 가끔 글 쓰기"
color = ""
font = "sans"

[[module]]
type = "gap"
h = 24

[[module]]
type = "cmd"
cmd = "cat tech"
ps = "$"
color = ""
font = "code"

[[module]]
type = "kv"
rows = ["major: 소프트웨어 · 핀테크"]
font = "sans"
fontKey = "code"

[[module]]
type = "stack"
key = "stack"
style = "dots"
items = ["Rust #bright-red", "Python #bright-blue", "Linux #bright-yellow", "Flutter #bright-cyan"]
font = "code"
fontItems = "code"

[[module]]
type = "gap"
h = 24

[[module]]
type = "cmd"
cmd = "cat favs"
ps = "$"
color = ""
font = "code"

[[module]]
type = "kv"
rows = ["listening: 산들산들 — 언니네이발관 🎧", "season: 눈 내리는 겨울 ☃️", "weather: 구름 조금 있는 날 🌤️"]
font = "sans"
fontKey = "code"

[[module]]
type = "gap"
h = 24

[[module]]
type = "cmd"
cmd = "solved-ac redfox"
ps = "$"
color = ""
font = "code"

[[module]]
type = "solved"
handle = "redfox"
streak = true
tags = true
link = true
fRank = "code"
fStreak = "code"
fTags = "sans"
fLink = "code"

[[module]]
type = "gap"
h = 24

[[module]]
type = "cmd"
cmd = "ls -l links/"
ps = "$"
color = ""
font = "code"

[[module]]
type = "text"
t = "total 0"
color = "bright-black"
font = "code"

[[module]]
type = "li"
prefix = "lrwxrwxrwx 1 redfox-ac"
name = "velog"
to = "https://velog.io/@sound/posts"
font = "code"
fontName = "code"
fontTo = "code"

[[module]]
type = "li"
prefix = "lrwxrwxrwx 1 redfox-ac"
name = "mail"
to = "mailto:redfox@yonsei.ac.kr"
font = "code"
fontName = "code"
fontTo = "code"

[[module]]
type = "gap"
h = 24

[[module]]
type = "cursor"
blink = true

[[module]]
type = "footer"
