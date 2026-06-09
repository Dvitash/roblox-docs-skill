# UIPageLayout

**Superclass:** [UIGridStyleLayout](UIGridStyleLayout.md)

This file defines a `UIPageLayout` class, which creates a paged viewing window by parenting it to a `GuiObject`. It supports various easing directions and styles for animations.

## Properties
### `UIPageLayout.Animated`
- **Type:** `boolean`
- **Summary:** Whether or not to animate transitions between pages.

### `UIPageLayout.Circular`
- **Type:** `boolean`
- **Summary:** Whether or not the page layout wraps around at the ends.

### `UIPageLayout.CurrentPage`
- **Type:** `[GuiObject](GuiObject.md)`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** The page that is either currently being displayed or is the target of the current animation.

### `UIPageLayout.EasingDirection`
- **Type:** `EasingDirection`
- **Summary:** The easing direction to use when performing an animation.

### `UIPageLayout.EasingStyle`
- **Type:** `EasingStyle`
- **Summary:** The easing style to use when performing an animation.

### `UIPageLayout.GamepadInputEnabled`
- **Type:** `boolean`
- **Summary:** Controls the overrides of `NextSelection{Up, Down, Left, Right}`. Defaults to true.

### `UIPageLayout.Padding`
- **Type:** `UDim`
- **Summary:** Determines the amount that pages are separated from each other by.

### `UIPageLayout.ScrollWheelInputEnabled`
- **Type:** `boolean`
- **Summary:** Controls the use of scroll wheel, in case that it is intended for something else. Defaults to true.

### `UIPageLayout.TouchInputEnabled`
- **Type:** `boolean`
- **Summary:** Controls touch scrolling, in case this is a non-interactive layout. Defaults to true.

### `UIPageLayout.TweenTime`
- **Type:** `float`
- **Summary:** The length of the animation.

## Methods
### `UIPageLayout:JumpTo(page: [Instance](Instance.md)) -> ()`
- **Summary:** If the `page` is in the UIPageLayout, then it sets `Class.UIPageLayout.CurrentPage` to it and animates to it. If the circular layout is enabled, it will take the shortest path to this page.

### `UIPageLayout:JumpToIndex(index: int) -> ()`
- **Summary:** If the index is `>= 0` and less than the size of the layout, this method acts like `Class.UIPageLayout:JumpTo()`. If it's out of bounds and circular is set, it will animate the full distance between the in-bounds index of `Class.UIPageLayout.CurrentPage` and the new index.

### `UIPageLayout:Next() -> ()`
- **Summary:** Sets `Class.UIPageLayout.CurrentPage` to the page after the current page and animates to it, or does nothing if there isn't a next page.

### `UIPageLayout:Previous() -> ()`
- **Summary:** Sets `Class.UIPageLayout.CurrentPage` to the page before the current page and animates to it, or does nothing if there isn't a previous page.

## Events
### `UIPageLayout.PageEnter(page: [Instance](Instance.md))`
- **Summary:** Fires when a page comes into view, and is going to be rendered.

### `UIPageLayout.PageLeave(page: [Instance](Instance.md))`
- **Summary:** Fires when a page leaves view, and will not be rendered.

### `UIPageLayout.Stopped(currentPage: [Instance](Instance.md))`
- **Summary:** Fires when an animation to `Class.UIPageLayout.CurrentPage` is completed without being canceled, and the view stops scrolling.
