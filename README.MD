# lyre

使用 AI 处理的 RIME 音乐词库

```text


      ||             ||
    @@##===#######===##@@
      ||   |||||||   ||
      ||   |||||||   ||
      \\   |||||||   //
       \\__|||||||__//
        \  |||||||  /
         \_#######_/


```

本词库以音乐相关书籍与专业教材为语料来源，使用 `Deepseek R1` 、 `Gemini` 、`Claude` 进行**分词**和**清洗**。

词库内容涵盖音乐理论术语、乐器名称、作曲家、经典作品、演奏技法等专业领域词汇。

---

## 文件说明

- `lyre.dict.yaml` ： 混合了所有词库的文件
  - `chinese.lyre.dict.yaml` : 中国（传统）音乐
  - `classical.lyre.dict.yaml` ： 古典
  - `electronic.lyre.dict.yaml` ： 电子音乐
  - `jazz.lyre.dict.yaml` ： 爵士音乐 _【待完成】_
  - `mix.lyre.dict.yaml` ： 混音、后期处理
  - `popular.lyre.dict.yaml` ： 流行音乐 _【待完成】_
  - `theory.lyre.dict.yaml` : 音乐理论
- `mini.lyre.dict.yaml` : 精简后的小词库

1. **所有词库相互独立**，所以词库内容相互重叠，如果只想用其中几个词库，请自行去重使用。
2. 除了`mini.lyre.dict.yaml`外，其余词库以大而全为主。
3. 除了已有单独的词库外，大部分体裁或流派都会收录到`popular.lyre.dict.yaml`当中，欢迎提交各种体裁或流派的独立版本。
4. 不收录过度商业化的内容。

---

## 进度

词库还未完成，未来还会继续补充

### 长期任务

- 词库优化，去除无用词
- 查缺补漏

### 完成进度

| 文件名                            |       词库名称       | 完成进度 | 未来计划                                               |
| --------------------------------- | :------------------: | :------: | ------------------------------------------------------ |
| `dicts\classical.lyre.dict.yaml`  |     **古典音乐**     | 部分完成 | 补充艺术家名字及其它词条                               |
| `dicts\electronic.lyre.dict.yaml` |     **电子音乐**     | 部分完成 | 补充合成器词条                                         |
| `dicts\theory.lyre.dict.yaml`      |     **音乐理论**     | 基本完成 | 查缺补漏                                               |
| `dicts\chinese.lyre.dict.yaml`    | **中国（传统）音乐** | 基本完成 | 未来再考虑是否补充词库                                 |
| `dicts\mix.lyre.dict.yaml`        |  **混音及后期处理**  | 基本完成 | 查缺补漏                                               |
| `dicts\jazz.lyre.dict.yaml`       |       **爵士**       |  未开始  | 计划资料多了再做                                       |
| `dicts\popular.lyre.dict.yaml`    |     **流行音乐**     |  未开始  | 计划资料多了再做                                       |
| `mini.lyre.dict.yaml`             |      **小词库**      | 部分完成 | 正在加词中，考虑还是用 AI 加词，手工加词其实做不到全面 |
