# 提示模板模块

该模块存储了用于引导AI生成内容的提示模板。这些模板定义了游戏的背景设定、角色信息、故事风格等，帮助AI模型生成符合游戏主题的内容。

## 文件说明

* act\_game\_prompts.txt：定义游戏行为和互动的基本提示
* images\_prompts.txt：图像生成的提示模板
* martial\_arts\_prompts.txt：武侠风格故事的提示模板
* start\_prompts.txt：游戏开始时的初始提示
* load\_prompts.py：加载提示模板的代码

## 使用方法

在代码中，通过*load\_prompts*函数加载所需的提示模板：

```
prompt = load_prompts("act_game")
```

## 自定义提示

* 可以根据游戏的设计需求修改现有提示模板，或添加新的提示模板文件
* 修改后，确保在代码中正确引用新的提示类别
