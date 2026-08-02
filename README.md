# SkyScript

> 专为高效能自动化、快速任务执行与网页嵌入所设计的轻量级直译式脚本语言。
> 💡 **提示**：點擊網頁中的 **Editor** 按鈕即可开启编辑器。

---

## 🌟 核心特性

* **轻量快捷**：具备极低的运行开销，专为高效的文本与脚本解析打造。
* **现代网页 IDE 支援**：完美相容带有自定义语法突显与代码格式化的网页开发环境。
* **智能流程控制**：内建灵活的脚本区块与区块略过机制（`skip to ... here`）。
* **跨平台支援**：能够轻松嵌入并部署于各种系统环境之中。

---

## 📖 快速入门

以下是一个简单的 SkyScript (`.sky`) 脚本範例：

```skyscript
set prog
    set window.title "SkyScript 平台"
    set window.size "1200x800"
    
    ## 这是一个测试批注
    print "欢迎来到 SkyScript 中文网页 IDE！"
    
    def class UserDemo
        name = "Sky"
        score = "100"
        print name
    
    skip to
        这段代码区块将会被自动略过。
    here
    
    print "程序执行完毕！"
end prog
