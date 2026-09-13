# 夸克

用于夸克相关的环境变量配置指引。

---

## ⚙️ 环境变量列表

| 变量名 | 是否必填 | 默认值 / 示例 | 说明 |
| :--- | :---: | :--- | :--- |
| `QUARK_COOKIE` | **是** | - | 账号凭据。多账号支持换行或使用 `&` 分隔，末尾可追加 `#备注名`（例如：`cookie_str#账号1`）。 |
| `QUARK_SIGN` | 否 | `http://[IP_ADDRESS]` | 接口地址，留空使用默认地址。 |
| `QUARK_EXCHANGE_TARGET` | 否 | `none` | 兑换目标权益 |
| `QUARK_EXCHANGE_RUSH` | 否 | `false` | 是否开启抢购模式（`true` / `false`）。 |
| `QUARK_CHEST_WAIT` | 否 | `0` | 🪎开启策略：`0` 为快速扫荡模式，`1` 为冷却等待模式。 |
| `QUARK_FORCE_DEVICE` | 否 | `auto` | 指定：`auto`、`android`、`ios`。 |
| `QUARK_UPDATE_CORE` | 否 | `0` | 强制拉取最新so（`1` 或 `true`）。 |

---

## 运行环境要求

- **Python 版本**：Python 3.11 及以上
- **架构支持**：`x86_64` / `amd64`、`aarch64` / `arm64`
