#仿小美到家的广告轮播，不一样轮播效果哦
##看腻了的轮播？试试带点推拉效果的轮播吧
###可无限循环
###可拉伸放大
###可外部加载网络图片
###可设置页面指示位置
###自定义页面指示样式动效
### 简单使用


    [_adPageView setAdsWithImages:@[@"m1", @"m2", @"m3", @"m4", @"m5"]
                            block:^(NSInteger clickIndex){
                                NSLog(@"%ld", (long)clickIndex);
                            }];
                            
                            
##pod 'xiaomeiADPage', :git => 'https://github.com/emilyZhouwm/xiaomeiADPage.git'
                            
欢迎star交流
图片版权：考满分网
 
![](./xmADPage.gif)
![](./xiaomeiADPage.gif)
