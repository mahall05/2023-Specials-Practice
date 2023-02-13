# 2023 Specials Practice

This is a Unity recreation of the 2023 Charged Up field for drive practice use. This is designed with Team 4381's control scheme, involving a 3-step process using the d-pad:

1. Select Grid
    1. **Left Grid** — *Left Arrow*
    1. **Middle Grid** — *Up or Down Arrow*
    1. **Right Grid** — *Right Arrow*
1. Select Column
    1. **Left Column** — *Left Arrow*
    1. **Middle Column** — *Up or Down Arrow*
    1. **Right Column** — *Right Arrow*
1. Select Row
    1. **Bottom Row** — *Down Arrow*
    1. **Middle Row** — *Right or Left Arrow*
    1. **Top Row** — *Up Arrow*
    
It will pick a random scoring location, and the goal is to select the correct combination as fast as possible, and at that time it will pick a new scoring location. Currently it contains 2 modes: **timed** and **unlimited**. Unlimited allows the user to continue indefinetely until they decide to quit. Timed is the same gameplay, but limits it to 30 seconds. Both modes track the number of correct choices, the number of incorrect choices, and the average time to pick the **correct goal**. The timed mode also calculates **% accuracy**.