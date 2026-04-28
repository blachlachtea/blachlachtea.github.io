**搭建流程**
微博帖子索引（含大致步骤）：https://weibo.com/7900749078/5050967191982458

①注册Github账号
https://github.com/

②打开这份【Gmeek快速上手】攻略，从【2.1从模板创建仓库】到【2.3开始写作】按照指示
https://breathiness.github.io/post/ke-neng-shi-mu-qian-zui-fang-bian-de-ge-ren-bo-ke-da-jian-fang-fa-%E2%80%94%E2%80%94Gmeek%20-bo-ke-kuang-jia.html?continueFlag=4b5a7ff1e230616c9d64f217b9d2ffd6

> [!TIP]
>清晰索引※https://blog.meekdai.com/post/Gmeek-kuai-su-shang-shou.html

<img width="678" alt="cf01497096bfcdc611bdfd3146e1abf" src="https://github.com/blachlachtea/blachlachtea.github.io/assets/174589953/d054ce0f-f7b0-4186-b074-4b3c23079e24">

③最后生成的个人博客网址是：https://XXX.github.io/（XXX为注册Github的用户名）


**写作使用**

*个性化主页设置
在【Code-config.json】里修改代码（见Gmeek上手攻略）
我的自定义代码可直接复制 见微信收藏 #博客
ps：改代码的时候一定注意，只有最后一行句尾不需要英文逗号，其他前面的都需要加

*头像主页图片替换
在代码中要以 url的链接形式 放图片
图片链接转换网站→ https://picui.cn/upload

*手动全局生成：
操作→Actions->build Gmeek->Run workflow
修改config.json文件之后需要操作，其他时候有什么不对劲就可以重启一下
![image](https://github.com/blachlachtea/blachlachtea.github.io/assets/174589953/7ea781e5-2b62-4e60-810e-ce8d917ddc5b)

*发布文章：
Issues-创建新的，发布时一定记得加#Labels标签
![image](https://github.com/blachlachtea/blachlachtea.github.io/assets/174589953/fe7bbc3f-b641-4568-a718-71de547a54ba)
![image](https://github.com/blachlachtea/blachlachtea.github.io/assets/174589953/77b3497e-787b-4457-b31e-cdc5916822c0)

添加图片=直接复制或拖进来就可以，会自动生成对应链接

置顶= Pin issue（编辑文章时在右侧下方可选）
删除=Close issue/Delete issue（编辑文章时在右侧下方可选）
![image](https://github.com/blachlachtea/blachlachtea.github.io/assets/174589953/275aa24e-6ebf-4998-87f9-c4cb2053c6d2)

*修改文章发布时间：
文章末尾一行加代码
![image](https://github.com/blachlachtea/blachlachtea.github.io/assets/174589953/200b3b16-ee57-47b9-bc02-235cce7e62e0)
中间的数字自行替换，时间戳数字转换网站→ https://tool.lu/timestamp/

*打高亮小标签
加代码> [!NOTE]
加代码> Useful information that users should know, even when skimming content.

加代码> [!TIP]
加代码> Helpful advice for doing things better or more easily.

加代码> [!IMPORTANT]
加代码> Key information users need to know to achieve their goal.

加代码> [!WARNING]
加代码> Urgent info that needs immediate user attention to avoid problems.

加代码> [!CAUTION]
加代码> Advises about risks or negative outcomes of certain actions.

效果如下↓
![image](https://github.com/blachlachtea/blachlachtea.github.io/assets/174589953/af88ffc3-e582-44fb-a521-0873dc0bbc67)


*进阶需求
https://blog.meekdai.com/tag.html#Gmeek
