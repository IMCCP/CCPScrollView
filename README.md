# CCPScrollView

文字无限轮播,适用于广播消息的上下无限轮播展示。

### DEMO GIF：

![Image text]( https://github.com/IMCCP/CCPScrollView/blob/master/CCPScrollView/CCPScrollView/scrollView.gif)

### DEMO 描述：

### DEMO方法介绍：
```
/**
 *  文字数组
 */
@property (nonatomic,strong) NSArray *titleArray;
```
```
/**
 *  拼接后的文字数组
 */
@property (nonatomic,strong) NSMutableArray *titleNewArray;
```
```
/**
 *  是否可以拖拽
 */
@property (nonatomic,assign) BOOL isCanScroll;
```
```
/**
 *  block回调
 */
@property (nonatomic,copy)void(^clickLabelBlock)(NSInteger index);
```
```
/**
 *  字体颜色
 */
@property (nonatomic,strong) UIColor *titleColor;
```
```
/**
 *  背景颜色
 */
@property (nonatomic,strong) UIColor *BGColor;
```
```
/**
 *  字体大小
 */
@property (nonatomic,assign) CGFloat titleFont;
```
```
/**
 *  关闭定时器
 */
- (void)removeTimer;
```
```
/**
 *  添加定时器
 */
- (void)addTimer;
```
```
/**
 *  label的点击事件
 */

- (void) clickTitleLabel:(clickLabelBlock) clickLabelBlock;
```
