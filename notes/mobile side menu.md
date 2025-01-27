
a mobile version of SideMenu that works in the following ways:
1. only appears after the Hero - so utilize the useSticky() hook from SideMenu such that if isSticky = it means that this mobile side menu is visible. toggle the visibility as opacity on spring animation (use framer motion).
2. the MobileSideMenu has a collapsed and expanded state. In the collapsed state, it's simply an IconButton with the menu icon within. In the expanded state, it's the TableOfContents with all of the sections within, with a close icon at the top.