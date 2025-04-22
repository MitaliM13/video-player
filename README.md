A video player that does not allow skipping of the video
**Made use of useState for managing the**
1.watch interval stored in the array based on the watch time interval such that the watch time is tracked. 
2. current interval to track the moment when the new interval starts
**Made use of the useEffect for managing the side effects
Made use of useRef to get a direct reference to the video element.**

**fetchProgress()**
made a function for tracking the progress by first fetching the video and then checking whether the video was played or not

**mergeIntervals()**
made a function to check that the overlapping intervals are merged. by checking whether the end of previously watched time interval is greater than the start of the new time interval. if so then merge both the time intervals to create a new time interval array.

**calculateProgress()**
for looping through the merged intervals by adding the previous time with the new one 
and then converting it into percentage based on the total watch time
