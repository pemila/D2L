# D2L

### 学习资料

[动手学深度学习](https://zh.d2l.ai/chapter_introduction/index.html)

### Git忽略`ipynb`文件的输出内容

```
# 安装过滤器
pip install nbstripout

# 进入当前git库根目录
cd ../D2L/

# 配置过滤器
nbstripout --install

# 配置过滤器作用的文件类型
nbstripout --install --attributes .gitattributes
```