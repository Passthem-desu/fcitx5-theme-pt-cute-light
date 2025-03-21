# Fcitx5 PT's cute light 主题

个人审美向的可爱主题，工作在水平候选模式：

（编辑 `~/.config/fcitx5/conf/classicui.conf` 或在 `fcitx5` 相关设置页面）

```
Vertical Candidate List=False
```

我使用的字体：[Maple Mono NF CN](https://github.com/subframe7536/maple-font) 15pt

## 预览

![Preview Image](preview.svg)

## 实际效果

### PT's Kagami

![Preview Image](imgs/kagami.png)

### PT's Konata

![Preview Image](imgs/konata.png)

### PT's Minami

![Preview Image](imgs/minami.png)

### PT's Misao

![Preview Image](imgs/misao.png)

## 使用方法

下载本项目到本地：

```bash
git clone https://github.com/passthem/fcitx5-theme-pt-cute-light.git
```

将文件夹复制或连接至 `fcitx5` 主题文件夹：

```bash
# 方法1 复制
cd fcitx5-theme-pt-cute-light
cp ./kagami ~/.local/share/fcitx5/themes/
cp ./konata ~/.local/share/fcitx5/themes/
cp ./minami ~/.local/share/fcitx5/themes/
cp ./misao ~/.local/share/fcitx5/themes/

# 方法2 建立软链接
cd fcitx5-theme-pt-cute-light
ln -s ./kagami ~/.local/share/fcitx5/themes/
ln -s ./konata ~/.local/share/fcitx5/themes/
ln -s ./minami ~/.local/share/fcitx5/themes/
ln -s ./misao ~/.local/share/fcitx5/themes/
```

## 客制化

如果你喜欢其他颜色，那么大可以先修改 `preview.svg` 试验试验，然后直接复制其中的一个文件夹，然后修改以下内容：

### background.svg

修改两个 `<path />` 元素的 `style` 的 `fill` 颜色，分别是下半的颜色和上半的颜色。

### candidate.svg

修改 `<path />` 元素的 `sytle` 的 `fill` 颜色。是「当前选中的选项」的背景色。

### theme.conf

修改第 6 行 `Name` 成你喜欢的名字。

修改第 10 行 `Author` 作者名字。

修改第 12 行 `Description` 描述。

修改第 16 行 `NormalColor` 文字颜色。
