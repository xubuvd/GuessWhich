# AI图像猜谜游戏 - GuessWhich

GuessWhich 是一个合作性的图像猜测游戏，涉及两个代理：Q-BOT 和 A-BOT。GuessWhich 的目标是让 Q-BOT 通过一系列问题识别从 9,628 张测试图像中选出的目标图像。A-BOT 可以看到目标图像，并对 Q-BOT 的问题做出回应。Q-BOT 只能访问由 Neuraltalk2（Vinyals & Le, 2015）生成的图像描述。在游戏中，A-BOT 从一个更广泛的图像集合中随机选择一张秘密图像，而 Q-BOT 对该图像一无所知。两个代理通过自然语言对话进行交流，Q-BOT 提出自由形式的问题，而 A-BOT 提供自由形式的回答。游戏在 Q-BOT 尝试识别秘密图像时结束。如果 Q-BOT 正确识别了图像，则游戏成功；否则，尝试被视为失败。

GuessWhich is a cooperative image-guessing game involving two agents: Q-BOT and A-BOT. The objective of GuessWhich is for Q-BOT to identify a target image from a set of 9,628 test images by asking a series of questions. A-BOT, who can see the target image, provides responses to Q-BOT's questions. Q-BOT has access only to a caption generated by Neuraltalk2 (Vinyals & Le, 2015) for the image. During the game, A-BOT selects a secret image randomly from a broader set, which remains unknown to Q-BOT. The agents communicate through natural language dialogue, with Q-BOT asking free-form questions and A-BOT providing free-form answers. The game concludes when Q-BOT attempts to identify the secret image. Success is achieved if Q-BOT correctly identifies the image; otherwise, the attempt is deemed a failure.

## 挑战 Challenges
GuessWhich 是一个复杂的视觉语言任务，要求处理大量图像数据集，并通过自然语言对话中的多轮问答对来解读人类的心理图像。

GuessWhich is a complex visual-language task that requires handling extensive image datasets and interpreting human mental imagery through multi-round question-answer pairs generated in natural language dialogue.

## Codes
coming soon...
