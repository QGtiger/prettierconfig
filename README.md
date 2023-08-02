## Prettier 的配置项

```
{
	"printWidth": 80,
	"tabWidth": 2,
	"useTabs": true,
	"semi": true,
	"singleQuote": true,
	"quoteProps": "as-needed",
	"jsxSingleQuote": false,
	"bracketSpacing": true,
	"jsxBracketSameLine": false,
	"arrowParens": "always",
	"trailingComma": "all",
	"objectCurlyNewline": "consistent",
	"overrides": [
		{
			"files": ".prettierrc",
			"options": {
				"parser": "json"
			}
		}
	]
}
```

这些是Prettier代码格式化工具的配置项，每个配置项的含义如下：

- `arrowParens`: 在箭头函数中，当只有一个参数时是否需要括号。可选值有 `always` 和 `avoid`。
- `bracketSameLine`: 是否将对象或数组的左括号与第一个元素放在同一行。可选值有 `true` 和 `false`。
- `bracketSpacing`: 是否在对象或数组的括号内添加空格。可选值有 `true` 和 `false`。
- `semi`: 是否在语句末尾添加分号。可选值有 `true` 和 `false`。
- `singleQuote`: 是否使用单引号。可选值有 `true` 和 `false`。
- `jsxSingleQuote`: 在JSX中是否使用单引号。可选值有 `true` 和 `false`。
- `quoteProps`: 对象属性名是否需要用引号括起来。可选值有 `as-needed`、`consistent` 和 `preserve`。
- `trailingComma`: 是否在多行结尾添加逗号。可选值有 `none`、`es5`、`all`。
- `singleAttributePerLine`: 是否将每个属性都放在单独的行上。可选值有 `true` 和 `false`。
- `htmlWhitespaceSensitivity`: HTML标记内的空格敏感度。可选值有 `css`、`strict`、`ignore`。
- `vueIndentScriptAndStyle`: 是否缩进Vue组件中的 `<script>` 和 `<style>` 标签。可选值有 `true` 和 `false`。
- `proseWrap`: 在Markdown文本中，如何换行。可选值有 `always`、`never`、`preserve`。
- `insertPragma`: 是否在文件顶部插入一个特殊的注释，以表明该文件已经使用了Prettier进行格式化。可选值有 `true` 和 `false`。
- `printWidth`: 每行最大字符数。默认为80。
- `requirePragma`: 是否只对带有特定注释的文件进行格式化。可选值有 `true` 和 `false`。
- `tabWidth`: 缩进使用的空格数。默认为2。
- `useTabs`: 是否使用制表符进行缩进。可选值有 `true` 和 `false`。
- `embeddedLanguageFormatting`: 是否自动格式化嵌入式代码块。可选值有 `auto`、`off`、和 `onWithoutIndent`。

## 使用

在项目中的 package.json 配置 prettier =》 你的 npm包名