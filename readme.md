# 开发laravel扩展教程
## 用法
<pre>
<code>
    composer require coder-mu-yao/hasher
</code>
</pre>
或者在你的composer.json的require部分添加：
<pre>
    <code>
        "coder-mu-yao/hasher": "~1.0"
    </code>
</pre>
下载完毕之后，直接配置app/config.php的providers:
<pre>
    <code>
        Laravist\Hasher\MD5HasherProvider::class,
    </code>
</pre>