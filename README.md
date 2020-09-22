# live2dAPI
页面动漫精灵接口文件
模型在model 目录

使用前提 是  引入  live2d.js   将model目录 里的  角色json文件  路径传进去即可

例子：


    const tips = {
        mouseover: ["想干嘛呢~", "言胖子还没给我任何能力哦~专心看网页吧~", "我会学习，我会成长，我会成为，妮蔻~"],
        welcome: "欢迎来到<span style='color:aqua;'>" + document.title + "</span>~",
        click: ["再乱点的话我可要报警了！⌇●﹏●⌇", "110吗，这里有个变态一直在碰我(ó﹏ò｡)"],
    }
    const model = {
        nepnep: ["https://cdn.jsdelivr.net/gh/dengkangyan/live2dAPI@1.0.7/model/HyperdimensionNeptunia/neptune_classic/index.json"]
    }
    // 设置3秒才能出发一次监听
    let time = !0;
    loadlive2d('live2d', model.nepnep[0]);
    
    
    点击事件 、触摸事件  按需求开发即可。可以调用相关网站，如古诗词 之类的  API 接口  写需求
