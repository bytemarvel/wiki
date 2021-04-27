---
title: "九章算法课件"
date: 2021-04-27 11:46
---

**算法基础班**

<!--

import os
wikiPath = "/wiki/attach/九章算法/动态规划v2.0/"
localFilePath = "/Users/lintaofang/wiki/attach/九章算法/动态规划v2.0/"
def generate(localFilePath,wikPath):
	res = ""
	template = "* [**Title**](Path)"
	files = [x for x in os.listdir(localFilePath) if x.endswith('.pdf')]
	files = sorted(files)
	for f in files:
		title = f.replace(".pdf","")
		path = wikiPath + f.replace(" ","_")
		res += template.replace("Title",title).replace("Path",path)
		os.rename(localFilePath + f, localFilePath + f.replace(" ","_"))
		print(template.replace("Title",title).replace("Path",path))
	
		

-->
* [**Lecture_2 二分法**](/wiki/attach/九章算法/九章算法-基础班/Lecture_2_二分法.pdf)
* [**Lecture_3 二叉树**](/wiki/attach/九章算法/九章算法-基础班/Lecture_3_二叉树.pdf)
* [**Lecture_4 动态规划上**](/wiki/attach/九章算法/九章算法-基础班/Lecture_4_动态规划上.pdf)
* [**Lecture_5 动态规划下**](/wiki/attach/九章算法/九章算法-基础班/Lecture_5_动态规划下.pdf)
* [**Lecture_6 链表**](/wiki/attach/九章算法/九章算法-基础班/Lecture_6_链表.pdf)
* [**Lecture_7 数组与数**](/wiki/attach/九章算法/九章算法-基础班/Lecture_7_数组与数.pdf)
* [**Lecture_8 数据结构**](/wiki/attach/九章算法/九章算法-基础班/Lecture_8_数据结构.pdf)
* [**Lecture_9 图与搜索**](/wiki/attach/九章算法/九章算法-基础班/Lecture_9_图与搜索.pdf)



**算法强化班**

* [**Lecture_1 简介**](/wiki/attach/九章算法/九章算法-强化班/1._简介.pdf)
* [**Lecture_2 数据结构上**](/wiki/attach/九章算法/九章算法-强化班/2._数据结构上.pdf)
* [**Lecture_3 数据结构下**](/wiki/attach/九章算法/九章算法-强化班/3._数据结构下.pdf)
* [**Lecture_4 Two Pointers**](/wiki/attach/九章算法/九章算法-强化班/4._Two_Pointers.pdf)
* [**Lecture_5 动态规划上**](/wiki/attach/九章算法/九章算法-强化班/5._动态规划上.pdf)
* [**Lecture_6 动态规划下**](/wiki/attach/九章算法/九章算法-强化班/6._动态规划下.pdf)
* [**Lecture_7 Follow Up 问题**](/wiki/attach/九章算法/九章算法-强化班/7._Follow_Up_问题.pdf)

**动态规划v2.0**

* [**Lecture_1 简介**](/wiki/attach/九章算法/动态规划v2.0/九章动态规划1_简介_170916.pdf)
* [**Lecture_2 坐标型&位操作型**](/wiki/attach/九章算法/动态规划v2.0/九章动态规划2_坐标型&位操作型_170923.pdf)
* [**Lecture_3 序列型**](/wiki/attach/九章算法/动态规划v2.0/九章动态规划3_序列型_170924.pdf)
* [**Lecture_4 划分型&博弈型&背包型**](/wiki/attach/九章算法/动态规划v2.0/九章动态规划4_划分型&博弈型&背包型_170930.pdf)
* [**Lecture_5 背包型&区间型**](/wiki/attach/九章算法/动态规划v2.0/九章动态规划5_背包型&区间型_171001.pdf)
* [**Lecture_6 双序列型**](/wiki/attach/九章算法/动态规划v2.0/九章动态规划6_双序列型_171007.pdf)
* [**Lecture_7 难题**](/wiki/attach/九章算法/动态规划v2.0/九章动态规划7_难题_171008.pdf)