# FaceFriend
## APP的主要功能有三点
### 1.美颜相机
### 2.相册分类管理
### 3.基于相册分类、用户标签及用户行为的人物画像的社交功能
## APP的设计思路是：
### 1.首先用户注册时必须上传一张自己的人脸照片，照片的人脸识别使用腾讯优图的优图人脸检测API，并且每个用户设置自己的兴趣标签
### 2.其次获取每个用户手机相册里的照片，使用腾讯优图的图片标签识别API，将用户的照片上传至优图服务器，返回用户照片信息进行分类，建立手机照片分类管理工具，并且在APP后台建立云相册，便于用户照片管理与保存
### 3.开发自定义的相机，实现美颜等功能
### 4.根据用户的信息、标签、照片信息在后台建立用户画像，基于用户的地理位置，推荐位置相近并且画像相似的用户给本用户，方便进一步的社交。
