# whitescreen-fouc-test
 写一个 server，验证白屏和 Fouc效果

## start
#### 第一步

```
node index.js
```
#### 第二步

在浏览器中打开 http://localhost:8080/public/index.html

#### 第三步

修改 index.html 里面的引入的文件链接，加上参数 t=秒数，如
```
<script src="a.js?t=3"></script
```
表示延迟3秒加载 a.js

将script放到css之前之后分别测试

放到之前加 defer / async 后在进行测试 

#### 第四步

分别用 chrome 和 firefox 浏览器测试白屏 和 Fouc 效果
