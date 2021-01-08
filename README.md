# calculator

---
# Overview

[WritingPublisherSubscriber(python)](http://wiki.ros.org/ja/ROS/Tutorials/WritingPublisherSubscriber%28python%29)を元に作成．

**talker**に入力した式を**listener**がeval関数を使って計算し，結果を出力する．

---
# Version
- ubuntu
  - 20.04.1 LTS

- ROS
  - Noetic

- Python
  - 3.8.5
  
---
# Run

```
terminal1:
$ roscore

terminal2:
$ rosrun calculator talker.py

terminal3:
$ rosrun calculate rosrun calculator listener.py
