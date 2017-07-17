HMSegmentedControl
===

https://github.com/HeshamMegid/HMSegmentedControl

# Usage

The code below will create a segmented control with the default looks:

```  objective-c
HMSegmentedControl *segmentControl5 = [[HMSegmentedControl alloc] initWithFrame:CGRectMake(0, 320, viewWidth, 50)];
    segmentControl5.sectionTitles = @[@"(123)", @"", @"", @"", @""];
    segmentControl5.selectedSegmentIndex = 0;
    segmentControl5.backgroundColor = [UIColor whiteColor];
    segmentControl5.titleTextAttributes = @{NSForegroundColorAttributeName : [UIColor colorWithWhite:74.0f/255.0f alpha:1.0], NSFontAttributeName : [UIFont systemFontOfSize:13]};
    segmentControl5.selectedTitleTextAttributes = @{NSForegroundColorAttributeName : [UIColor whiteColor], NSFontAttributeName : [UIFont systemFontOfSize:13]};
//    segmentControl5.selectionStyle = HMSegmentedControlSelectionStyleBox;
    
    segmentControl5.cornerRadiusEnable = true;
    segmentControl5.cornerUnSelectColor = [UIColor colorWithRed:237.0f/255.0f green:249.0f/255.0f blue:242.0f/255.0f alpha:1.0f];
    segmentControl5.cornerSelectedColor = [UIColor colorWithRed:39.0f/255.0f green:174.0f/255.0f blue:95.0f/255.0f alpha:1.0f];
    segmentControl5.horizontalOffset = 6.0f;
    segmentControl5.verticalOffset = 5.0f;
    segmentControl5.radiusSpace = 4.0f;
    segmentControl5.selectionIndicatorLocation = HMSegmentedControlSelectionIndicatorLocationNone;
    [self.view addSubview:segmentControl5];
```

Included is a demo project showing how to fully customise the control.

![HMSegmentedControl](https://github.com/new-soul/HMSegmentedControl/blob/master/Screenshot.png)


