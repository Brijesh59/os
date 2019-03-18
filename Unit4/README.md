# Operating System <br />
## Unit 4 <br />
#### 1. Deadlock
- <a href="https://www.youtube.com/watch?v=zb2JDY-vNl0&list=PLWPirh4EWFpGkHH9JTKH9KsnfAA471Fhy&index=26&t=0s">Deadlock Introduction & Deadlock Characterisation(Necessary conditions for Deadlock to happen)</a>
- <a href="https://www.youtube.com/watch?v=-VksGXfiK7k&list=PLWPirh4EWFpGkHH9JTKH9KsnfAA471Fhy&index=26">Resource Allocation Graph</a>
> Methods of Handling Deadlock
   1. Deadlock Prevention
   2. Deadlock Avoidance
   3. Deadlock Detection
   4. Deadlock Recovery
- <a href="https://www.youtube.com/watch?v=_sKaad5GrYc&list=PLWPirh4EWFpGkHH9JTKH9KsnfAA471Fhy&index=27">Deadlock Prevention</a>
- <a href="https://www.youtube.com/watch?v=-VoZvNvYt-A&list=PLWPirh4EWFpGkHH9JTKH9KsnfAA471Fhy&index=28">Deadlock Avoidance and Banker's Algorithm</a>
- <a href="https://www.youtube.com/watch?v=2N8iiDiHjXw&list=PLWPirh4EWFpGkHH9JTKH9KsnfAA471Fhy&index=29">Banker's Algorithm Example</a>
- <a href="https://www.youtube.com/watch?v=ETS0HCFFss4&list=PLWPirh4EWFpGkHH9JTKH9KsnfAA471Fhy&index=30">Request Resource Algorithm</a>
- <a href="https://www.youtube.com/watch?v=2St4eKZ_VVQ&list=PLWPirh4EWFpGkHH9JTKH9KsnfAA471Fhy&index=31">Deadlock Detection</a>
- <a href="https://www.youtube.com/watch?v=KBFrWu_gejE&list=PLWPirh4EWFpGkHH9JTKH9KsnfAA471Fhy&index=32">Deadlock Recovery</a>

#### 2. Information Management

#### 3. File Management
- Allocation Methods: The allocation methods define how the files are stored in the disk blocks. There are three main disk space or file allocation methods - 
   1. Contiguous Allocation
   2. Linked Allocation
   3. Indexed Allocation <br />

   Video Link - <a href="https://www.youtube.com/watch?v=LWPMnCNd1q8">https://www.youtube.com/watch?v=LWPMnCNd1q8</a> <br />
   Notes Link - <a href="https://www.geeksforgeeks.org/file-allocation-methods/">https://www.geeksforgeeks.org/file- allocation-methods/</a>

   #NOTE - Take a look at First Fit, Best Fit and Worst Fit in the video. That is part of the Syllabus.

- Free-Space Management: Since disk space is limited, we need to reuse the space from deleted files for new files, if possible. To keep track of free disk space, the system maintains a free-space list. <br />
The free-space list records all free disk blocks—those not allocated to some file or directory. To create a file, we search the free-space list for the required amount of space and allocate that space to the new file. This space is then removed from the free-space list. When a file is deleted, its disk space is added to the free-space list. <br />
Five Different Methods to implement free-space list - <br />
   - Bit Vector
   - Linked List
   - Grouping
   - Counting
   - Space Maps

