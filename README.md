# ThreeKingdomsWerewolfGame

三国狼人杀，多 agents 架构学习项目。

## Python

- Python 3.12
- 独立虚拟环境：`.venv`

## 当前目录结构

- `src/main.py`: 项目入口
- `src/game_roles.py`: 角色定义
- `src/prompt_cn.py`: 中文提示词
- `src/structured_output_cn.py`: 结构化输出定义
- `src/utils_cn.py`: 工具函数和游戏常量
- `tests/`: 测试目录
- `requirements.txt`: 依赖清单

## 初始化

进入项目目录：

```powershell
cd .\projects\ThreeKingdomsWerewolfGame
```

激活虚拟环境：

```powershell
.\.venv\Scripts\Activate.ps1
```

安装依赖：

```powershell
python -m pip install -r requirements.txt
```

## 运行

当前项目采用直接运行脚本的方式启动：

```powershell
python .\src\main.py
```

## 说明

- 当前 `src` 使用的是扁平脚本结构，不是 `src/package_name/...` 的包结构
- 因此当前更适合用 `python .\src\main.py`，而不是 `python -m package.module`
