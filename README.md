# MetaFoxes-Online-PS
## 小狐狸合影在线 P 狐狸头
一个简单的 html 页面，通过调用 Canvas API 和 Fabric.js 库，实现在线编辑图片功能。
为原来的照片，添加对应编号的 #MetaFoxes 的「狐狸头」，，可以进行拖拽、旋转、缩放、镜像等处理。
整个程序可以是纯前端的单页面应用（SPA），不需要后端服务器，图片合成在浏览器里就能完成，并将合成图片保存至本地。

小狐狸头像，使用 @Next-DAO 的在线仓库，https://github.com/Next-DAO/meta-foxes-contract/main/parts
通过指定编号，向图片添加一个图层。
