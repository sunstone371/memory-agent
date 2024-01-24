# memory-agent
一种通过快速切换性格设定，避免伦理风险的陪伴机器人方案
陪伴机器人以情感功能为主，应用场景为儿童陪伴机器人、老人陪伴机器人、家庭陪伴机器人等，基于人类情感的风险主要为长时间使用会让人类视机器人为自己情感的一部分而无法跳出，最终造成机器人深度参与人类社会，为不法分子及别有用心的人操纵他人以可乘之机。本方案通过快捷的机器人性格设定功能结合机器人性格最长使用时间设定，避免使用者长时间使用陪伴机器人后感情无法跳出的现象。以下以儿童陪伴机器人为例推进方案。
##项目：儿童陪伴机器人
功能方向：儿童在家里缺少玩伴，陪伴机器人具备陪孩子聊天，并且能够从朋友的角度给孩子意见与启发，促进孩子优质成长，比如：要养成良好的卫生习惯等。

	目前demo功能：
1.	跟孩子同龄，具有与孩子相同或者类似思维、说话语气及风格的陪聊机器人
2.	通过输入内容的形式，可以把需要灌输给孩子的道理或孩子学习的知识输入给机器人，机器人将以渐进式，看似无意的日常对话，把上述内容植入，并通过多次重复提及，以期达到目标儿童被动或主动思考后接受的效果。（此处暂定，鉴于大模型输出的多样性及不稳定性，具体以prompt调试后大模型输出结果为依据，进行优化或更改策略）
3.	回答孩子的各种问题。（万事通兼维基百科词典）
4.	具备短时记忆与长时记忆功能，所以能够在一定程度模拟人类与孩子建立情感沟通。


	后续第一阶段的优化：
	记忆部分，细分记忆部分，按优先级划分长时记忆为多个分区。并做更细致的动态管理。

	伦理规避：使用真实伙伴或者亲戚模拟，且支持简单快捷的更换，避免单一性格或模拟角色长时间使用，造成孩子情感深度参与无法跳出（此次不一定成熟，仅为当前粗略应对策略，待定状态）。

	隐私数据问题。

	功能优化：需要灌输给孩子的道理或课程知识能够实时输入或更新，机器人将以渐进式，看似无意的流畅植入日常对话，并通过多次重复提及达到，达到目标儿童被动或主动思考后接受的效果【此处目标植入机器人时需要多重确认，并联网核查，仅适用于未成年人教育】此功能最初版本就有，但是植入流畅度及自然程度等需要根据具体植入内容做单点优化。

	后续第二阶段的优化：
 	多模态与多模型使用，机器人实体外形基于使用场景的优化，更多的输入硬件（摄像头、触觉传感器等）与输出（语音、图像等）硬件。
 	多角色互动，机器人脱离之前以某一个儿童为中心的单一关注，可以增加更多的角色，并在记忆中以同一级别的优先级处理更多的关系（可以是更多的儿童、也可以为机器人），同时体现在机器人计划生成中。
