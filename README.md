# Hongchenxian prototype / 红尘仙纯净原型

Python 3.10+, standard library only. Run from this directory or from the root of the extracted ZIP. No install, API key, server, or model required. All inputs are synthetic, and actions are simulated.

只需 Python 3.10+ 标准库。在本目录或 ZIP 解压目录运行；无需安装依赖、配置 API key、启用服务或加载模型。所有输入为合成数据，动作仅模拟。

| Example / 示例 | Command / 命令 |
| --- | --- |
| Base prototype / 基础原型 | `python demo.py` |
| DLC 01 / 局部重建与补丁 | `python dlc01/short_memory.py` |
| DLC 01 / 单独查询补丁 | `python dlc01/rebuild.py --query 周四` |
| DLC 02 / 可见索引图 | `python dlc02/index_map.py` |
| DLC 03 / 事件链协议与反射 | `python dlc03/protocol.py` |

Run `python -m unittest -v` separately in this directory and each of `dlc01`, `dlc02`, and `dlc03`. The three extensions run independently. On Windows, `py -3` also works in place of `python`.

测试：分别进入本目录及 `dlc01`、`dlc02`、`dlc03`，运行 `python -m unittest -v`。三个扩展各自独立运行。Windows 可用 `py -3` 代替 `python`。

[Architecture diagrams / 四阶段架构图](architecture/README.md)
