# Obsidian Web Clipper Templates

Templates for [Obsidian Web Clipper](https://github.com/obsidianmd/obsidian-clipper). Works with the templates in my Obsidian vault.

To install templates, see instructions in the official [Obsidian Web Clipper documentation](https://help.obsidian.md/web-clipper/templates) repo.

You can find more templates from [Obsidian Community](https://github.com/obsidian-community/web-clipper-templates/tree/main/templates).

## Work with AI

Obsidian Web Clipper 最吸引人的地方在於它的 AI 整合能力，可以讓我們在擷取網頁時，直接呼叫 AI 來協助我們處理擷取的內容。

1. 設定 AI 模型

    選擇「解譯器」加入 AI 與他的模型，我使用的是 Azure OpenAI 服務。
    - 點擊「新增提供者」新增 AI 服務與 API 金鑰，預設就提供了許多知名的 AI 服務，也可以自訂，所以我們也能使用本機的 AI 服務唷！
    - 新增模型

2. 自定義範本與 Prompt

    選擇要用的範本，以 `Default` 為例，可以直接在變數中執行 Prompt。
    例如擷取的網站標題如果是英文，希望能透過 AI 自動翻譯成中文，可以將原本的網站標題變數 `{{title}}` 改寫成 `{{"return title into Traditional Chinese"}}`，這段話的意思是告訴 AI 將標題翻譯成繁體中文並回傳

3. 自訂摘要與其他應用

    除了標題外，也可以在「筆記內容」呼叫 AI，裡如使用 `{{"summary the content and return in Traditional Chinese"}}`，請 AI 摘要文章並回傳繁體中文，也可以適當用 Markdown 語法排版
