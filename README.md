# kpengVerticalView
类似网易严选的竖着选择的列表

#初始化方法和回调

  kpengVerticalView *listView =[[kpengVerticalView alloc] initWithFrame:XXView.bounds withTitle:self.categoryArray];
    
    [XXView addSubview:listView];
    
    listView.selectedInfoCallBack = ^(id callbackInfo) {
    
    NSLog(@"----%@",callbackInfo);
    
    };
   ![](snv.gif)
    ![这里写图片描述](https://github.com/smithgoo/kpengVerticalView/blob/master/snv.gif)
 
