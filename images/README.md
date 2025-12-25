# 图片资源目录

## 目录结构

```
images/
├── attractions/     # 景点图片
├── food/           # 美食图片  
├── culture/        # 文化历史图片
├── weather/        # 天气图标
├── team/           # 团队成员头像
└── icons/          # 图标资源
```

## 图片命名规范

- 景点图片：景点名称拼音/英文，如 `canton-tower.jpg`
- 美食图片：美食名称拼音/英文，如 `white-cut-chicken.jpg`
- 文化图片：文化主题拼音/英文，如 `cantonese-opera.jpg`
- 天气图片：天气状况拼音/英文，如 `sunny.png`
- 团队头像：成员姓名拼音/英文，如 `zhang-san.jpg`

## 图片尺寸建议

- 景点图片：400x300px (缩略图)，800x600px (大图)
- 美食图片：300x200px (缩略图)，600x400px (大图)
- 团队头像：150x150px (正方形)
- 图标：64x64px (方形图标)

## 使用方法

在Vue组件中使用本地图片：

```javascript
// 使用绝对路径
image: '/images/attractions/canton-tower.jpg'

// 或使用import
import cantonTower from '@/assets/images/attractions/canton-tower.jpg'
```

注意：public目录下的文件会被直接复制到构建输出目录，所以可以使用绝对路径 `/images/...` 来引用。