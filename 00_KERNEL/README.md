# 00_KERNEL (核心公理)

> **Protection Ring**: Ring 0 (Kernel Mode)
> **Nature**: Immutable / Axiomatic (不可变/公理化)
> **Status**: Critical

---

## 🏛️ 定义 (Definition)

此处是 **Decisive Moments** 系统的绝对底层。
存放不证自明的**第一性原理 (First Principles)** 与**元逻辑 (Meta-Logic)**。

不同于 `01_THEORIES` 中的推导模型，本目录下的内容属于 **"定义" (Definitions)** 与 **"公理" (Axioms)**。
它们是逻辑推演的起点，而非终点。

## 📜 固件清单 (Firmware Manifest)

- **[K000_Genesis_LiXin.cn.md](./K000_Genesis_LiXin.cn.md)**
  - **代号**：Genesis / Boot Sector
  - **描述**：系统初始引导扇区。由 AI 分身生成，Zeek 命名并确认。
  - **作用**：确立了本系统的价值观基准与运行“道”理。
  - **权限**：只读 (Read-Only)。

## ⚠️ 操作守则 (Protocol)

1.  **稳定性原则**：内核层不应频繁变动。修改此处的一个定义，可能会导致上层 (`01` - `07`) 的所有逻辑链发生崩塌或重构（蝴蝶效应）。
2.  **引用规范**：上层架构在遇到逻辑冲突时，应回溯至本层寻找最终裁决。

---
> *"Axioms are not proven; they are assumed."*
> *公理无需证明，它们是被确认的起点。*
