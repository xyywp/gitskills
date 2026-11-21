# gitskills

一个用于练习 Git 常用操作的示例仓库。

## 项目简介

本仓库不包含实际业务代码，所有文件仅作为练习素材，用来熟悉日常开发中最常用的 Git 工作流：

- 创建、切换与删除分支
- 提交改动、查看提交历史与文件差异
- 合并分支，并处理合并时产生的冲突
- 在本地分支与远端仓库之间同步代码

## 目录说明

| 文件 | 说明 |
| --- | --- |
| `1.txt`、`2.txt`、`3.txt` | 简单的文本文件，用于练习修改与提交 |
| `gg.txt`、`yxx.txt` | 用于练习多分支并行修改、合并与冲突处理 |
| `README.md` | 项目说明 |

## 练习方式

1. 克隆仓库：

   ```bash
   git clone https://github.com/xyywp/gitskills.git
   ```

2. 新建一个练习分支：

   ```bash
   git checkout -b practice
   ```

3. 修改任意文件并提交：

   ```bash
   git add .
   git commit -m "practice: 修改示例文件"
   ```

4. 切回 `master` 并合并练习分支，观察合并结果：

   ```bash
   git checkout master
   git merge practice
   ```

## 说明

仓库没有构建、测试或部署流程，克隆后即可直接开始练习。
