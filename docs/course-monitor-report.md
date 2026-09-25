# 课程记录工具

本仓库的 main 和各实验分支均提供同步自 [leeehh/course-tool](https://github.com/leeehh/course-tool) 的工具，版本 `6d68289f601a76b51f33efed3ad13198ae57a579`。
在本仓库运行 `python3 course.py` 仍会安装到本仓库；也可用 `--project` 指定其他 Git 项目。
安装后的 `git course` 和 `git agent-plugins` 使用 `.ai/course-tools/`，可跨全部章节分支运行。
升级时在当前分支拉取更新，再运行 `python3 course.py`（或指定 `--agent`）；原记录和配置会保留。
插件仍使用原有 `rcore-session-archive@rcore-tutorial-2025s` 标识，避免已有配置另起一套插件。
