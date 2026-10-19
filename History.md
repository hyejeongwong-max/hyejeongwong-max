# History

## V0.3.3 (2026-10-20)
- 修复英文版 Hero 的 XML 转义 Bug：`AI Product Builder & Educator` 中的 `&` 未转义导致 GitHub 渲染报 xmlParseEntityRef 错误（线上英文版角色卡图显示异常）
- 生成脚本 build_variants.py 增加 `esc()` 转义函数，所有文本输出统一转义
- 预览页文案更新：英文标题两行「Hi, I'm Hyejeong. / AI Product Builder & Educator」，中文标题两行「HI ! 我是王惠晶👋 / AI 产品经理 & 独立开发者」，副标题字号 20px

## V0.3.2 (2026-10-19)
- 新增「冒险地图」组件（ADVENTURE MAP / 冒险地图）：像素 RPG 风格 52 周贡献热力图（map-contributions-{en,zh}-light.svg）+ 配套分区标题（section-map-{en,zh}-light.svg）
- README 结构插入位置：技术栈（已装备）之后、任务日志之前
- 地图数据为确定性示例数据，SVG 内已标注可替换为真实贡献数据

## V0.3.1 (2026-10-19)
- Hero 排版从左右分栏改为上下排版：角色卡在上、技能栏整排在下（画布 1200×640）
- 角色人设文案更新为 AI 产品方向：`AI Product Builder & Educator` / `AI 产品构建者与布道者`
- 预览页：标题随语言切换（中文「你好我是，王惠晶👋」/ 英文「Hi, I'm Hyejeong. AI Product Builder & Educator」）、副标题「从用户体验到商业化」、文件链接竖排、移除说明文字

## V0.3.0 (2026-10-19)
- 主页升级为「像素 RPG 角色卡」风格（浅色主题，中英双语）：顶部角色卡 Hero + 像素风分区标题（TECH STACK / QUEST LOG / GUILD HALL）
- 保留 V0.2.0 的占位结构：打字动画、一句话介绍、语言切换、左右双栏（我在做什么 / 代表开源项目）、底部标语
- 技术标签移入「已装备」分区；新增 `assets/readme/` 资产目录（8 个 SVG，中英各 4 类）
- 生成脚本与组件包位于本地 `pixel-rpg-components/`（`build_variants.py` / `build_hero.py`），可改数据重跑

## V0.2.0 (2026-10-19)
- 主页样式整体更换：一比一复刻 chusimin 主页结构（打字动画标题、标签、左右双栏、底部标语）
- 个人信息与项目全部改为占位符 `[方括号]`，由用户自行填写
- 联系方式（小红书/邮箱）随旧版一并移除，待用户在新版中补充

## V0.1.1 (2026-10-19)
- 确定主页 Bio 文案：英文 `UX to business ｜ AI Product Manager`；中文 `从用户体验到商业落地 ｜ AI产品经理`（填写在 GitHub Settings 账户信息中）

## V0.1.0 (2026-10-19)
- 创建 GitHub 主页 README（英文版 `README.md` + 中文版 `README.zh-CN.md`），仿照参考主页结构
- 自我介绍主线：从用户体验到商业落地
- 联系方式：小红书 / 邮箱（手机号因公开隐私风险未放入主页）
- 精选项目、写作、关于我：待补充（源码中以注释占位）
