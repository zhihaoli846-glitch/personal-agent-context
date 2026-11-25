# MiniMax H3 提示词编写框架
先按平台支持选择T2VA、I2VA、FL2VA、L2VA、Ref2VA等模式，查当前官方格式。历史多参考示例：
```text
subject_definitions:
[逐一绑定主体与参考素材，锁定同一身份、服装和风格]
summary:
[任务类型、总时长、比例、场景、主要动作与视角]
retention_analysis:
[保留参考视频动作、节奏、运镜；替换角色、环境；明确素材分工]
detailed_description:
[按时间轴拆动作、机位、转场、音效、对白和表情]
[Additional constraints if supported]
[身份稳定、自然动作、正确手部、连续性、不得额外添加内容]
```
按当次需求中文或英文主体，保持对白/画面文字原语言。不硬套不适用字段，目标秒数内完成动作，避免模糊慢动作；未见视频不捏造动作。
