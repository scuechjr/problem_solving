#1、解决Sublime Install Package的There are no packages available for install问题(channel_v3.json)
##原因：
channel_v3.json无法访问
##解决方案：
Preferences->Package Setting->Package Control ->Setting User添加配置：
(```)
"channels":
    [
        "http://static.bolin.site/channel_v3.json"
    ]
(```)
全部配置如：
(```)
{
    "bootstrapped": true,
    "channels":
    [
        "http://static.bolin.site/channel_v3.json"
    ],
    "in_process_packages":
    [
    ],
    "installed_packages":
    [
        "HTML-CSS-JS Prettify",
        "MarkdownEditing",
        "Package Control"
    ]
}
(```)