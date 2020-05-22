---
layout: post
title:  "OmsAgentForLinux の設定から workspaceid, workspacekey を取得するスクリプト"
date:   2019-12-24 23:35:00 +0900
categories: azure CLI LogAnalytics
---

log-analytics は未だプレビュー段階のようですので、インストールが必要です。
`az vm extension show` コマンドの `--name` オプションに指定する名前は設定時で異なる場合があります。

{% gist 3229b126874fd954d2992065596491d7 %}
