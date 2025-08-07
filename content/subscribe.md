---
title: "📢 stay tuned"
---

<style type="text/css">
.dashed-border {
    border: dashed 1px var(--color-btn-border);
    border-radius: 4px;
    padding: 1em;
    margin-bottom: 1em;
}
    
.email-signup-form {
    display: flex;
    justify-content: center;
}

.email-signup-form input[type="email"] {
    background-color: var(--color-sheet-bg);
    border: solid 1px var(--color-border-generic);
    border-radius: 2px;
    color: var(--color-text);
    padding: .25em .5em;
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
    }

    .email-signup-form input[type="email"],
    .email-signup-form button[type="submit"] {
        width: 200px;
    }
    
    .email-signup-form .small-stack {
        margin-top: .25em;
        margin-bottom: .25em;
    }
}
</style>

## 通过邮箱订阅

留下你的收件地址，在本站更新时接收「海鸥来信」。

<div class="dashed-border">
    <div class="email-signup-form">
        <form action="https://app.kit.com/forms/8378820/subscriptions" method="post" target="_blank">
            <input type="hidden" name="utf8" value="✓">
            <label class="small-stack">致：</label>
            <input type="email" name="email_address" placeholder="you@example.com" required class="small-stack">
            <button type="submit" class="small-stack">订阅</button>
        </form>
    </div>
</div>

💡 确认邮件可能不会即时送达，也可能出现在垃圾箱里，请多多留意。

---

## 通过 RSS 订阅
在 feedly、inoreader 等 rss 阅读器中直接搜索本站域名，或者手动添加<a href="https://lmnlnlmns.org/posts/index.xml" target="_blank">订阅源</a>。
