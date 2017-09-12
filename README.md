# kpengVerticalView
类似网易严选的竖着选择的列表

#初始化方法和回调
  kpengVerticalView *listView =[[kpengVerticalView alloc] initWithFrame:_leftView.bounds withTitle:self.categoryArray];
    [_leftView addSubview:listView];
    listView.selectedInfoCallBack = ^(id callbackInfo) {
        NSLog(@"----%@",callbackInfo);
    };
