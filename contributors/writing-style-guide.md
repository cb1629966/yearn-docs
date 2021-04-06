# 写作风格指南

向往社区写作风格指南总结了标准和最佳实践 **作家** 向“年度文档”资源捐款时应遵循的原则.

## 写作意图和语气

怀念社区的资料应迎合对怀念生态系统不熟悉的读者.作家还应该假设他们的读者安排的时间紧，关注时间短，因为毕竟耕种是诚实但辛勤的工作.

因此，作家应集中精力尽可能清晰，简洁地交流概念.

- 使用简单的语言.
- 使用简短的句子.
- 避免不必要的话.
- 保持开放和客观.
- 尽可能提供示例.
- 提供示例以帮助解释概念，但避免使它们过于复杂.
  - 必要时使用数学，但请保持简单且直观易懂.
- 必要时链接到基本术语.

## 作家指南

### 通用规则

- 贯穿所有草稿 [文法](https://app.grammarly.com/) 定期且在最终提交之前.
  - 文法将捕获大多数拼写和语法错误.
  -将渲染的文本复制到语法中，并解决它所标记的任何错误
    - HackMD无法识别拼写和语法错误.
    - 如果给其语法为降价促销的原始文本，语法将错失任何错误.
    - 注意将代码从文法复制并粘贴到VScode，文法可能会干扰格式化.

**请注意**

- 迁移到新文档时（即从谷歌文档迁移到HackMD）:
  - 在旧文件中留下笔记.
  - 提供指向最新版本的链接.
- 不要盲目接受语法建议.
  - 审核编辑以确保它们有意义.

**采用:**

- [牛津逗号](https://en.wikipedia.org/wiki/Serial_comma).
- [多元，不分性别的代词](https://en.wikipedia.org/wiki/Singular_they).
  - 使用“他们/他们”代替“他/她/他/她的”.”
  - **例子:** “当他们……”或“如果用户选择X，则他们的……”
- “％”符号.不要拼出“百分比."
  - **正确的:** 15%
  - **不正确的:** 15 percent
- 双引号 `" "` 短语，引号等.
  - 不要使用单 `' '` 引号.

**避免:**

- [第一人称语言.](https://en.wikipedia.org/wiki/Grammatical_person)
  - **例子:** I, we, our, etc.
- [Second-person language](https://en.wikipedia.org/wiki/Grammatical_person) (unless it is appropriate for a guide or action page).
  - **例子:** "然后是你..." 或者 "现在你应该..."
- 感叹号.
- 脚注.
- 对向往组件不推荐使用的名称的引用.
  - **例子:** yyCRV 或者 yUSD 代替 yvCurve-Y (看: [年度命名约定](../deve到lopers/naming-convention.md)).
- 括号用于说明其他信息.
  - **不正确的:** 发展补助金规模较大 ($5,000 到 $50,000) 针对个人或团队建立围绕金库和更广泛的向往生态系统的项目的赠款.
  - **正确的:** 发展赠款通常是较大规模的赠款，范围从 $5,000 到 $50,000, 针对个人或团队围绕金库和更广泛的向往生态系统建设项目.

### 缩略语

- 使用括号定义缩写词首次出现在给定文档中.
  - **例子:** 年度改进提案（ÿ一世P）是一个提案框架，用于支持新计划并扩大现有计划的范围.

### 首字母缩写词，十年和案例

请勿使用撇号将首字母缩写词复数或表示数十年。最后加一个“ s”.

#### 缩略语

- 使首字母缩略词复数:
  - **正确的:** YIPs
  - **不正确的:** YIP's

#### 几十年

- To indicate a decade:
  - **正确的:** 1990s
  - **不正确的:** 1990's

#### 大写

- 名称和专有名词.
- 城市，国家，民族和语言.
- 由向往提供的具有定义的术语.

#### 标题案例

- **这 [标题案例 转炉](https://titlecaseconverter.com/) 将保持标题一致.**
- 遵循《纽约时报》标准.
- 大写第一个和最后一个词，所有名词，代词，动词，副词和形容词.
- 小写所有文章，连词和介词.

### 货币

以下示例使用美元，但相同的规则适用于所有全球货币.

- 使用小写字母，但写“美元”时除外.”
- 除临时参考外，所有数字均使用数字和“ \ $”号或无数字的金额.
  - **标准:** "书籍费用 \$4."
  - **随意的:** "请给我一美元."
- 对于金额 \100万美元，采用这种格式:
  - **矫正:** $4, $25, $500, $1,000, \$650,000.
- 对于超过 \$1 million, 使用单词，而不是数字.
  - **正确的:** "他值得 \$4 million."
  - **不正确的:** "他值得 \$4,000,000."

### Naming Conventions

#### Cryptocurrencies

- When directly referring to the creation, destruction, or manipulation of a token (particularly as it relates to tooling) or when referencing the token as a currency, in an instructional or conversational setting, or as a conceptual product of the Foundation or its systems:
  - Use the proper prefix if necessary and capitalized TLA version: `wETH`
  - **Example:** “wETH is a token that represents Ether 1:1 and conforms to the ERC20 token standard.”
- Similarly, when referring to exchange pairs:
  - Use: `wETH/DAI`

#### Yearn Products

Please see [Yearn Naming Conventions](../developers/naming-convention.md).

#### Yearn

- When referring to Yearn as a smart contract system, use "The Yearn Protocol."
  - **Example:** “The Yearn Protocol is a set of contracts for yield optimization."
- When referring to Yearn as a body of YFI voters and the general stakeholder community, use "Yearn Community" or simply "Yearn."
  - **Example:** "Yearn passed a vote to decrease the yCRV vault performance fee."
  - **Example:** "The Yearn Community passed a vote to add an additional vault."
- Use "Yearn" for casual references to Yearn and the Yearn Protocol as a whole.

### Numbers

- Spell out numbers below 10.
  - **Examples:** one, two, three, etc.
- Use numerals for numbers above 10, unless starting a sentence.
- For numbers with million, billion, or trillion, use figures in all except casual cases.
  - **Standard:** "The nation has 1 million citizens."
  - **Casual:** "I'd like to make a billion dollars."

### Lists

When bulleted and numbered lists contain complete sentences, capitalize the first word, and follow each with a period. If list items are phrases, no capitalization or punctuation is required.

- _Don't_ use a list with only 1 item.
- Use [parallel construction](https://en.wikipedia.org/wiki/Parallelism_%28grammar%29) for each item in a list.
- Start with the same [part of speech](https://en.wikipedia.org/wiki/Part_of_speech) for each item (in this case, a verb).
- Use the same verb [tense](https://en.wikipedia.org/wiki/Grammatical_tense#English) for each item.
- Use the same [voice](https://en.wikipedia.org/wiki/Voice_%28grammar%29) for each item.
- Use the same sentence type (statement, question, exclamation) for each item.
- List items that include definitions should look like this:
  - **Team:** Yearn Protocol Developers and Contributors
  - **Community**: General participants in Yearn forums and chat
- Use dashes rather than asterisks for unordered lists.
  - **Correct:** `-`
  - **Incorrect:** `*`
- Alphabetize lists of names unless there is a clear priority at work.
- Do not use ordered (numbered) lists unless order matters.
- Ordered list items should use the `1. ` repeated.
  - Markdown will automatically generate numbers.

**Example:**

```markdown
1.  Item 1
1.  Item 2
1.  Item 3
1.  Item 3a
1.  Item 3b
```

### Links

- Use [absolute links](https://docs.microsoft.com/en-us/contribute/how-to-write-links) and standard web URLs when referencing external resources.
- Create descriptive hyperlinks and avoid generic language.
  - **Correct - Descriptive:** (Learn more at [Yearn Documentation](https://docs.yearn.finance/)
  - **Incorrect - Generic:** Learn more [here](https://docs.yearn.finance/).
- Include a `.`outside the link for sentences that end with a link.
- When creating links for parallel translated documents, make sure to update relative links to reflect the correct heading.

### Tables of Contents

- Include a table of contents for documents that span several pages and multiple sections.
- Use the raw Markdown from the Table of Contents above as a template.
  - Be sure to include the line breaks `---` as well to keep formatting consistent.
- The table of contents should list relevant sections for easy navigation.

## Markdown Guide

Yearn documents posted on GitHub are written in Markdown, a text-to-HTML conversion tool for web writers.

- Include line breaks above and below headings.
- Use top-level headers (`#`) only once per document.
  - Do not make multiple top-level headings.
- Avoid repeat headings.
  - They will break auto-generated navigation.
- Avoid trailing spaces.
- Do not use:
  - Em or en [dashes:](https://en.wikipedia.org/wiki/Wikipedia:Hyphens_and_dashes) `—`
  - Ampersands `&` in titles and headers.
  - Pipes `|` in titles and headers.
  - Curly quotes. Use the plaintext version.
    - **Correct:** `"`
    - **Incorrect:** `“`
  - Escaping parentheses. Use normal parentheses.
    - **Correct:** `(SOMETHING)`
    - **Incorrect:** `\(SOMETHING\)`
- Ensure there is a single hard return at the end of a .md file.
- Use emojis to call attention to an important point, when necessary.
  - Practice discretion and use them sparingly.
  - This [cheat sheet](https://gist.github.com/rxaviers/7360908) lists emojis and their Markdown shortcuts.

## Best Practices and Resources

Writers and contributors familiar with Yearn and cryptocurrency basics will have a better sense of where to apply their skills best.

- Spend some time learning about Yearn's function, history, and any recent events before contributing.
- In-depth knowledge is appreciated but not required.

### Learn the Basics of Markdown

- [Daring Fireball](https://daringfireball.net/projects/markdown/)
- [Markdown Syntax Guide](https://guides.github.com/features/mastering-markdown/)
- [Practice Communicating Using Markdown](https://lab.github.com/githubtraining/communicating-using-markdown)

### Helpful Writing Tools

Make use of any writing tools that help improve workflow and writing quality. See the list below for some recommendations.

#### Text Editors

- [Grammarly](https://app.grammarly.com/) - Mistake-free writing editor
- [HemingwayApp](https://www.hemingwayapp.com/) - Make writing bold and clear

#### Word Choice

- [Thesaurus](https://www.thesaurus.com/) - Synonyms
- [Powerthesaurus](https://www.powerthesaurus.org/) - Synonyms and phrase suggestions
- [WordHippo](https://www.wordhippo.com/) - Synonyms and phrase suggestions

### Review Community Guides

Review the respective Contribute.md for each repository where pertinent before starting work on any Yearn project.

- Yearn contributor guides outline writing standards and help simplify the writing process.

#### Document-Specific Maintenance Guides

- Check for an associated maintenance guide before starting work on a given document if applicable.
- A document maintenance guide outlines standards to help Reviewers and contributors when maintaining a given resource.
  - The rules described within a document-specific maintenance guide supersede other guides.
  - If a discrepancy is glaring or unreasonable, bring the issue to an admin in the [#documentation](https://discord.com/channels/734804446353031319/748476302121762866) channel on Yearn's discord.

#### Contributor Tools

- The [Contributor Tools Guide](contributor-tools.md) guide introduces the tools regularly used by Yearn contributors.

### Express Interest

- Check out the [Getting Started guide]() for contributing to Documentation.
- Join the [#documentation](https://discord.com/channels/734804446353031319/748476302121762866) channel on Yearn's Discord, read the pinned messages, and reach out to a channel admin.
- Yearn community team members and senior contributors help onboard new contributors via Discord or Telegram chats where applicable.
- Feel free to discuss personal interests and relevant skills to help determine a well-suited project/issue and jump right in.
- To understand strengths you can also provide relevant examples of past projects, work, and experience.
  - Demonstrate a reliable work ethic and offer quality work that speaks for itself.
  - Stand out by suggesting projects and adding insight to public discussions.

### Collaborate

- When accepting an assignment, be sure to collaborate early and often.
- Visit [#documentation](https://discord.com/channels/734804446353031319/748476302121762866) or corresponding Telegram chat regularly.
- Coordinate with other members.
  - Ask as many questions as necessary
  - Ask for feedback when stuck.
  - Provide frequent progress updates.
- Develop a plan that defines an approach for an assignment.
  - Produce a project outline. Clarify the what so we can agree on the how.
  - Set achievable deadlines. Timeboxing is good :)
  - Assign and divide tasks with other contributors.
    - Multiple contributors should not start work on similar projects individually. Please check that the same issue does not already exist in the Github Issues for that Repository, and if it does please coordinate with whoever is working on it to divide the work if needed.

#### Track Progress

- Track projects and progress with [GitHub Issues.](https://github.com/orgs/yearn/projects/2)
  - Keep GitHub issues updated with comments and feedback.
- Take advantage of version history when working in HackMD or Google Docs.

#### Final Drafts and Submissions

- Transfer approved final drafts from Google Docs to HackMD or DrawIO(for diagrams) if need be.
- Let the team know when a project is ready for final review by moving your issue to the status of `Pending Review` on Github and messaging in the appropriate Discord or Telegram channel.
- Once reviewed, submit completed projects for approval as a [Pull Request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request) on GitHub.
  - Ensure to update any relevant issues and the project board on GitHub

### Acknowledgements

This document could not be possible without the amazing work done by the MakerDAO team as this document is mostly based on their [Writing Style Guide](https://github.com/makerdao/community-portal/blob/r2d/content/en/contribute/content/writing-style-guide.mdx).
