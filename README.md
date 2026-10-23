# 产品发布与渠道获客 · Global Launch & Acquisition

把产品送到合适的海外用户面前：选首批渠道、安排发布、组织社媒与社区运营、推进创作者合作，并确认每次动作是否真正完成。

这个 Skill 适合已经知道产品做什么、需要启动或改进获客的人。可以只做一次产品上线，也可以运营一个账号、组织一批 KOL 合作，或打通搜索、应用商店和开源生态入口。提供普通产品资料即可独立使用，不要求先安装其他 Skill。

## 安装与第一次使用

将 `skills/global-launch-acquisition` 整个目录复制到支持 Agent Skills 的客户端。例如：

```bash
git clone https://github.com/NextVariable/global-launch-acquisition-skill.git
mkdir -p ~/.agents/skills
cp -R global-launch-acquisition-skill/skills/global-launch-acquisition ~/.agents/skills/
```

已有同名目录时先检查版本，避免覆盖自己的修改。重新加载客户端后调用 `$global-launch-acquisition`。

```text
使用 $global-launch-acquisition。我们做面向英语独立开发者的日志排查工具，
已有可运行示例、英文 README 和一段演示，官网能免费试用。
下周上线，一人每天能投入 2 小时，现金预算 300 美元。
请选最值得先试的渠道，给出具体发布包、安排和停止条件。
目前只准备，不发布、不联系他人。
```

如果要执行，在后续说明具体账号、目标、可用素材和动作范围；已经给过的授权会延续。Skill 使用客户端现有搜索、文件与发布工具，本身不附带账号或凭证。工具不支持某项动作时，会交付待执行包并明确阻塞。

## 它会帮你完成什么

先看目标用户在哪里、产品能否接住他们，再决定渠道和投入。发布前检查实际路径，发布中组织素材、合作与答疑，发布后记录真实状态，把主动需求交给销售、把可比较的数据交给实验复盘。

按任务加载五份方法： [发布与渠道选择](skills/global-launch-acquisition/references/launch-and-channels.md)、[社媒与社区](skills/global-launch-acquisition/references/social-and-community.md)、[合作与创作者](skills/global-launch-acquisition/references/partners-and-creators.md)、[持续发现与生态分发](skills/global-launch-acquisition/references/discovery-and-ecosystems.md)、[执行与恢复](skills/global-launch-acquisition/references/execution-and-recovery.md)。

交付可以是一条具体渠道方案、一份可执行发布包，或经授权完成的操作与核验结果。已排期、已提交、实际发布和收到回复会分开报告；不会把热度、排名、Star 或下载量直接写成业务增长。

本 Skill 聚焦渠道与发布。市场选择和 GTM 战略、完整内容制作、销售与客户留存、实验统计分别由其他任务负责；无需安装它们才能完成本 Skill 的职责。

## 开发与验证

```bash
python3 scripts/validate.py
```

结构检查与业务任务的验证范围分别见 [验证记录](validation/README.md)；测试情景见 [scenarios.md](validation/scenarios.md)。目录与边界见 [设计说明](docs/design.md)。客户资料、联系方式和执行回执应保存在私有工作目录，不提交到公共仓库。

## English

An Agent Skill for overseas product launches and channel acquisition: select relevant channels, coordinate social and community operations, manage creator partnerships, and verify publishing or submission outcomes. It works independently from ordinary product inputs and uses tools already available in the client. Public actions and spending stay within the user's authorization. Instructions are primarily in Chinese; deliverables can match the target audience's language.

## License

[MIT](LICENSE).
