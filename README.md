﻿# Infinite Scroll
## Idea 
We can utilize a circular array in order to achieve what we set out to do. Once an element is out of view, remove it from either the front or end of the array, update its viewability, and then add it to the opposite end of the array.

## Current issues
- Need to handle bottom-up case 
- Need to ensure that the browser believes that content still on page, as to not cause the scroller to go haywire
