# -vant-
基于vant已有的上传文件组件优化上传图片的大小进行压缩后上传

自己最近在做一个移动H5的项目，其中有上传图片的小功能，前端基于vue + vant 进行开发
因为vant自带了Uploader 文件上传表单组件，展现形式也比较美观，用户操作逻辑也比较合理，
但是针对目前手机相机拍照图片大小都比较高，对上传时，效率上对用户的感官和服务器响应不是特别美好，
需要对上传前的图片进行一定的压缩，减轻服务端的压力的同时，也让使用者体验更佳。

