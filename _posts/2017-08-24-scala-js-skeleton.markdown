---
title: "ScalaJS App Skeleton"
date: 2017-08-24
categories: [scala,js,programming]
tags: [scala,js,sbt,electron,express,skeleton]
---
I've had a lot of fun with [Scala][scala] over the past couple years doing little side things here and there. When I want to do some FP (and still be productive), Scala is my goto language.

In the past I've tried to pick up [ScalaJS][scalajs], but it was always just a bit of an annoyance to get all the tooling together, and I was anxiously waiting for [Scala][scala] 2.12 features. Well, not only is 2.12 out, but [ScalaJS][scalajs] is very close to 1.0!

So, I decided to just sit down over the past couple days and crank out a [Giter8][g8] [template][skeleton] that's pre-setup for use the [ScalaJS Bundler][bundler] plugin and that can be launched with [Electron][electron] (for desktop apps) or served with [Express][express] without copying files around. It's also has launch configurations for use with [VSCode][vscode] out-of-the-box.

![screenshot](https://raw.githubusercontent.com/massung/codeninja/master/_posts/images/scala-js-skeleton.png)
[https://github.com/massung/scala-js-skeleton.g8/][skeleton]

I hope this gets a few more people using [ScalaJS][scalajs] and/or [Scala][scala]!

If you find something wrong - or a better way of doing something in the skeleton - please, open an issue and tell me about it.

[g8]:           http://www.foundweekends.org/giter8
[skeleton]:     https://github.com/massung/scala-js-skeleton.g8
[scala]:        http://www.scala.org
[scalajs]:      http://www.scala-js.org
[nodejs]:       https://nodejs.org
[electron]:     https://electron.atom.io
[express]:      http://expressjs.com
[sbt]:          http://www.scala-sbt.org
[bundler]:      https://scalacenter.github.io/scalajs-bundler
[vscode]:       https://code.visualstudio.com
