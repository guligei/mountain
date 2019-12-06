# runloop



```text
-(void)brainTheory
{
    static int score = 80;
    int doScore = 0;
    int hour = 8;
    while (hour) {
        BOOL result = [self doValuableThing];
        if (result) {
            int x = arc4random() % 20;
            doScore = doScore + x;
        }
        hour--;
    }
    while(doScore < score) {
        NSLog(@"人活着为了什么???");
        NSLog(@"bad feeling!!!");
    }
    NSLog(@"happy!!!");
}

-(BOOL)doValuableThing
{
    if ([self loadTask]) {
        return YES;
    }
    return NO;
}

-(BOOL)loadTask
{
    if ([self writeCode]) {
        return YES;
    }
    return NO;
}

-(BOOL)writeCode
{
    NSLog(@"hello world");
    return YES;
}
```

