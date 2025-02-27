# Bocchi The Rock Theme

VS Code 主题包，灵感来自《孤独摇滚！》动画。包含了四个主要角色的深色和浅色主题版本。

## 灵感来源

主题的配色方案基于动画中角色的特征配色：

### 后藤一里 (Hitori Gotoh)
- 基于角色的粉色系配色
- 主色调：`#F4A5B0`（粉红色）
- 强调色：`#FE01FE`（亮粉色）
- 辅助色：`#B4698C`（暗玫瑰色）
- 配色灵感来自后藤标志性的粉色头发和校服配色
- 参考图片:
![](https://pic1.imgdb.cn/item/67bff29cd0e0a243d406b828.jpg)

### 伊地知虹夏 (Nijika Ijichi)
- 基于角色的金色系配色
- 主色调：`#F4E8DE`（浅米色）
- 强调色：`#FEFE01`（金黄色）
- 辅助色：`#EDCE60`（暗金色）
- 配色灵感来自虹夏金色的头发和阳光般的性格
- 参考图片:
>浅色参考
![](https://pic1.imgdb.cn/item/67bff29cd0e0a243d406b82a.jpg)
>深色参考
![](https://pic1.imgdb.cn/item/67bff347d0e0a243d406b879.jpg)
### 山田凉 (Ryo Yamada)
- 基于角色的蓝色系配色
- 主色调：`#375B9D`（深蓝色）
- 强调色：`#035555`（深青色）
- 辅助色：`#0C7D7D`（青色）
- 配色灵感来自凉冷静沉着的性格和深色系穿着
- 参考图片:
![](https://pic1.imgdb.cn/item/67bff29bd0e0a243d406b826.jpg)

### 喜多郁代 (Ikuyo Kita)
- 基于角色的红色系配色
- 主色调：`#FF0000`（亮红色）
- 强调色：`#A52A2A`（深红色）
- 辅助色：`#F4A5B0`（粉红色）
- 配色灵感来自喜多充满活力的性格和红色主题
- 参考图片:
![](https://pic1.imgdb.cn/item/67bff29bd0e0a243d406b827.jpg)


## 主题特点

### 语法高亮
- 关键字使用角色主题色，加粗显示
- 类型和类名使用强调色
- 函数和方法使用辅助色
- 字符串和注释使用柔和的配色
- 变量使用基础文本色
- 特殊语法（如装饰器、正则表达式）使用特殊高亮

### UI 设计
- 编辑器背景采用柔和的基色
- 活动栏和状态栏使用主题色
- 文件树和面板使用渐变色
- 选中和高亮使用半透明主题色
- 图标和徽章使用对比色

### 多语言支持
为以下语言提供优化的语法高亮：
- JavaScript/TypeScript
- Python
- Java
- C/C++
- HTML/CSS
- Markdown
- JSON/YAML
- 等更多语言

## 安装

1. 打开 VS Code
2. 按下 `Ctrl+P` / `Cmd+P`
3. 输入 `ext install bocchi-the-rock-theme`

## 使用方法

1. 按下 `Ctrl+K Ctrl+T` / `Cmd+K Cmd+T` 打开主题选择器
2. 选择你喜欢的 Bocchi 主题：
   - Bocchi - Hitori (Dark/Light)
   - Bocchi - Nijika (Dark/Light)
   - Bocchi - Ryo (Dark/Light)
   - Bocchi - Ikuyo (Dark/Light)

## 自定义

如果你想要自定义主题，可以在设置中覆盖颜色配置：
```json
{
    "workbench.colorCustomizations": {
        "[Bocchi - Character Theme]": {
            // 你的自定义颜色
        }
    }
}
```

## 贡献

欢迎在 [GitHub](https://github.com/your-username/bocchi-the-rock-theme) 上提交问题和建议。

## 许可

MIT License

## 致谢

- 《孤独摇滚！》原作：はまじあき
- 动画制作：CloverWorks
- 特别感谢所有为这个主题提供建议和反馈的用户

## 更新日志

### 1.0.0
- 初始发布
- 包含四个角色的深色和浅色主题
- 支持多种编程语言
- 优化的 UI 配色
