---
title: "📢 stay tuned"
---

<style type="text/css">
/* 主容器样式 */
.dashed-border {
    border: dashed 1px var(--color-btn-border);
    border-radius: 4px;
    padding: 1em;
    margin-bottom: 1em;
}

/* 表单布局 */
.email-signup-form {
    display: flex;
    justify-content: center;
}

.email-signup-form form {
    display: flex;
    align-items: baseline;
    gap: 0.5em;
}

.email-signup-form label,
.email-signup-form input[type="email"],
.email-signup-form button[type="submit"] {
    font-family: inherit;
    font-size: inherit;
    line-height: 1.4;
    margin: 0;
}

.email-signup-form label {
    color: var(--color-text);
    white-space: nowrap;
}

.email-signup-form input[type="email"] {
    background-color: var(--color-sheet-bg);
    border: solid 1px var(--color-border-generic);
    border-radius: 2px;
    color: var(--color-text);
    padding: .25em .5em;
    box-sizing: border-box;
}

.email-signup-form input[type="email"]::placeholder {
    opacity: .5;
}

.email-signup-form button[type="submit"] {
    box-shadow: 0 5px 5px -5px var(--color-boxshadow);
    border: solid 1px var(--color-btn-border);
    color: var(--color-text);
    background-color: var(--color-desktop-bg);
    border-radius: 4px;
    padding: .25em .5em;
    cursor: pointer;
    box-sizing: border-box;
}

.email-signup-form button[type="submit"]:hover {
    box-shadow: 0 7px 5px -5px var(--color-boxshadow);
    background-color: var(--color-btn-hover-bg);
    transition: all .1s;
}

@media(max-width: 680px) {
    .email-signup-form form {
        display: flex;
        flex-direction: column; 
        width: 100%;
        max-width: 300px; 
    }
    
    .email-signup-form label,
    .email-signup-form input[type="email"],
    .email-signup-form button[type="submit"] {
        margin-top: .25em;
        margin-bottom: .25em;
        width: 100%;  
    }
    
    .email-signup-form button[type="submit"] {
        margin-bottom: .4em;  
    }
}
</style>

## 通过邮箱订阅

留下你的收件地址，在本站更新时接收「海鸥来信」。

<div class="dashed-border">
    <div class="email-signup-form">
        <form action="https://app.kit.com/forms/8378820/subscriptions" method="post" target="_blank">
            <input type="hidden" name="utf8" value="✓">
            <label>To: </label>
            <input type="email" name="email_address" placeholder="you@example.com" required>
            <button type="submit">Subscribe</button>
        </form>
    </div>
</div>

💡 确认邮件可能不会即时送达，也可能出现在垃圾箱里，请多多留意。

---

## 通过 RSS 订阅
在 feedly、inoreader 等 rss 阅读器中直接搜索本站域名，或者手动添加<a href="https://lmnlnlmns.org/posts/index.xml" target="_blank">订阅源</a>。
