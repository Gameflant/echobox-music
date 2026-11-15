# EchoBox Music

EchoBox 的音乐仓库：索引在 `index/`，封面在 `covers/`，音频在 Releases 的 `audio` 标签下。

## 结构

- `index/meta.json`：条目数、生成时间，客户端据此判断是否需要全量同步
- `index/tracks.json`：曲目数组，字段与客户端 schema 一致
- `covers/<name>`：封面，raw 直链读取
- Releases `audio`：音频资产，地址为 `https://github.com/Gameflant/echobox-music/releases/download/audio/<file>`

## 专辑

- **SP!DUSTTALE** — 作者：反正是Sprins就对了
- 内置示例（CC0，自制）

## 使用条款

本仓库的音频、封面与索引数据版权归各自原作者所有，**仅允许非商业使用**。

- 允许：个人收听、非商业引用转载（需注明曲目与出处）、非商业二次创作
- 禁止：任何商业用途、去信息分发、批量镜像、商用模型训练

完整条款见 [LICENSE](LICENSE)。商用请联系对应曲目原作者。
