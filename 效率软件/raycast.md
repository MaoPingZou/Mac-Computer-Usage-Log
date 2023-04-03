本指南记录一些日常会用到的，短期看似不重要，但长期来看，能极大提升效率的扩展（extension）。

- [Clipboard History](#clipboard-history)
- [Snippets](#snippets)

</br>

# Clipboard History
快捷键设置为 `Ctrl + Command + V`。
> 延续了以往我使用 `CCboard` 的快捷键设置。（ `CCboard` 是一款专门管理剪贴板历史的 `Mac` 应用）。

</br>

# Snippets
可以将日常用频繁需要输入的字符，进行关键字替换。

> 如果想在苹果生态中多设备共用同一套字符替换规则的话，使用苹果自带的`Text Replacements`功能是最好的。

举一个使用场景：
比如，自从发现 `ChatGPT` 能极大提高我理解英文句子原意时，我开始频繁向 `ChatGPT` 提问，让它辅助我理解我看不大懂的英文句子。
但要让 `ChatGPT` 理解我的意图，我需要在每次提问的开头都加上：如何理解下面的句子：

比如：
> 如何理解下面的句子：Some sentences that you need chatGPT to help you understand.

假设，我一天会问 `ChatGPT` 100 次，那么，我需要重复输入 "如何理解下面的句子：" 100 次。那么：

- 使用双拼输入法输入 “如何理解下面的句子：” 所需要的按键次数。

    | 如何 | 理解 | 下面 |  的  | 句子 |             ：              | 每次按键数 | 那么一天下来 |
    | :--: | :--: | :--: | :--: | :--: | :-------------------------: | :------: | :-------: |
    | luh  | lij  | xwm  |  d   | juz  | <kbd>⇧</kbd> + <kbd>:</kbd> |   15次   | 1500 |

- 使用 `Snippets` 替换输入需要的按键数（不受当前中英文输入影响）。

    | 如何理解下面的句子： | 每次按键数 | 那么一天下来 |
    | :------------------: | :------: | :-------: |
    |         htu          |   3次    | 300 |


## 配置Snippets
通过调整`settings`，可以更大的提升效率。

- ⓵ 是否开启 `snippet` 扩展
- ⓶ 是否在单词中展开
- ⓷ 展开速度配置
- ⓸ 注入延迟速度
- ⓹ 展开声效
- ⓺ 禁用 `snippet` 的应用

![image](https://user-images.githubusercontent.com/43558972/229464924-107c7de8-e5aa-4cbf-9293-7ee0896316c2.png)


