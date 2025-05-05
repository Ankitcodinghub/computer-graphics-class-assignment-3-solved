# computer-graphics-class-assignment-3-solved
**TO GET THIS SOLUTION VISIT:** [Computer-Graphics Class Assignment 3 Solved](https://www.ankitcodinghub.com/product/computer-graphics-class-assignment-3-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;99643&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Computer-Graphics Class Assignment 3 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
1. Implement your own bvh file viewer.

<ol start="2">
<li>The window size doesn’t need to be (480, 480). Use the larger window that is enough to see the details of the viewer.</li>
<li>DO NOT set the window title to your student ID.</li>
<li>Total points: 105 pts (+20 pts for extra credits)</li>
</ol>
2. Requirements

A. Manipulate the camera in the same way as in ClassAssignment1 using your ClassAssignment1 code (10 pts).

i. Also draw the reference grid plane.

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>+ 2020_ITE0000_2019000001
  + ClassAssignment1/
</pre>
<pre>   - main.py
   - report.docx
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
A. You have to implement all requirements in a single program. This assignment DOES NOT require each requirement to be a separate program

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
B.

</div>
<div class="column">
Load a bvh file and render it (80 pts)

<ol>
<li>Open a bvh file by drag-and-drop to your bvh viewer window (10 pts)
<ol>
<li>Google glfwSetDropCallback to see how to do it</li>
<li>The viewer should render only one bvh file at a time. If a bvh file B is drag-and- dropped to the viewer while it is rendering another bvh file A, the viewer should only render the new bvh file B.</li>
<li>This feature is essential for scoring your assignment, so if not implemented, you won’t get any score for “Load a bvh file and render it (80 pts)”</li>
</ol>
</li>
<li>Read the bvh file and render the “skeleton” (t-pose) of the motion when you load the file by drag-and-drop (30 pts).
<ol>
<li>Do not automatically animate the character. Just draw its skeleton (t-pose) when you open a file.</li>
<li>Just draw joints with offsets between them only using the HIERARCHY section of the bvh file.</li>
<li>In other words, draw a pose of the motion with zero translation (0,0,0) and no rotation (identity matrix) being applied to transitional joints and rotational joints, respectively.</li>
<li>Draw the skeleton by line segments. Each line segment should connect each pair of parent-child joints.</li>
<li>For end-effector joints such as foot, a line segmented should connect the end- effector joint and the “end site”.</li>
<li>An example screenshot for sample-walk.bvh</li>
</ol>
</li>
</ol>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
A.

<ol start="3">
<li>Animate the loaded motion if you press the &lt;spacebar&gt; key (30 pts).
<ol>
<li>As time goes by, draw each pose of the motion using each line of frame data in the MOTION of the bvh file, from the start frame to the end frame.</li>
<li>Calling glfw.swap_interval(1) in your main function, then just drawing the pose of each frame for each iteration of the main loop (the while loop in the main function) would be enough for timing of rendering each pose.</li>
<li>After drawing the last frame, just replay the motion again (draw from the first frame to the last frame again).</li>
<li>Example screenshots for sample-walk.bvh</li>
</ol>
</li>
<li>When open a bvh file, print out the following information of the bvh file to stdout (console) (10 pts)
<ol>
<li>File name</li>
<li>Number of frames</li>
</ol>
</li>
</ol>
</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
<ol start="3">
<li>FPS (which is 1/FrameTime)</li>
<li>Number of joints (including root)</li>
<li>List of all joint names</li>
</ol>
3. Report (15 pts)

</div>
</div>
<div class="layoutArea">
<div class="column">
A. B.

</div>
<div class="column">
Submit a report of at most 2 pages in docx file format (MS Word). Do not exceed the limit.

The report should include:

i. Which requirements you implemented (5 pts)

</div>
</div>
<div class="layoutArea">
<div class="column">
ii.

</div>
<div class="column">
A hyperlink to the video uploaded to Internet video streaming services (such as YouTube and Vimeo) by capturing the animating hierarchical model as a video (10 pts).

<ol>
<li>Download bvh files from the Internet and open them with your viewer. For example, A. http://motion.hahasoha.net/

B. http://mocap.cs.sfu.ca/

C. http://dancedb.eu/main/performances</li>
<li>Choose one of the best looking motion plays using your viewer.</li>
<li>Do not use the sample bvh files for this requirement. You must use other bvh files downloaded from internet to get score for this requirement.</li>
<li>The uploaded video MUST be publicly accessible. Otherwise, you won’t get the 10 pts.</li>
</ol>
You do not need to try to write a long report. Just write down the required information. Use either English or Korean.

</div>
</div>
<div class="layoutArea">
<div class="column">
C.

</div>
</div>
<div class="layoutArea">
<div class="column">
4. Extra credits (Only one of two items A, B will be reflected in the score) A. Use a box to draw each body part instead of a line segment (+10 pts).

i. The boxes should be rendered with proper shading and lighting settings.

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
ii.

iii. iv.

</div>
<div class="column">
If you render the body parts without lighting and shading, you cannot get the score for this item.

You can implement this requirement for only one of the sample bvh files provided. An example screenshot for sample-walk.bvh

</div>
</div>
<div class="layoutArea">
<div class="column">
B.

</div>
<div class="column">
Use i.

ii.

iii. iv.

</div>
<div class="column">
1.

2. (You don’t need to draw the shadow and shaded ground plane)

different obj files to draw each body part instead of a line segment (+20 pts). The meshes should be rendered with proper shading and lighting settings.

If you render the body parts without lighting and shading, you cannot get the score for this item.

You can implement this requirement for only one of the sample bvh files provided. Example screenshots (not for sample-walk.bvh)

</div>
</div>
<div class="layoutArea">
<div class="column">
1.

<ol start="2">
<li>(You don’t need to draw the shadow and shaded ground plane)</li>
<li>Search and download cool obj files from the internet and use them.</li>
</ol>
A. If you use simple obj files like box shapes, you’ll only get 10 pts.

</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
<ol start="5">
<li>Runtime Environment
<ol>
<li>Your program should be able to run on systems only with Python 3.7 or later, NumPy, PyOpenGL, glfw. Do not use any other additional python modules.</li>
<li>Only glfw is allowed for event processing and window &amp; OpenGL context management. Do not use glut functions for this purpose.</li>
<li>If your program does not meet this requirement, it will not run on TA’s computer so you will not get any score for this assignment (except report).</li>
</ol>
</li>
<li>Test your viewer with sample bvh files.
<ol>
<li>sample-walk.bvh: A walking motion file</li>
<li>sample-spin.bvh: A walking while spinning around a vertical axis</li>
</ol>
</li>
<li>What you have to submit: A. .py files</li>
</ol>
i. You can use multiple .py files for this assignment. In this case, explain how to run the program in the report.

B. .docx report file

8. Additional information

<ol>
<li>drop_callback in glfw python binding is slightly different from that of original glfw written in C. drop_callback in python takes only two parameters, window and paths. paths is a list of dropped file paths.</li>
<li>Python provides powerful string methods helpful for parsing a bvh file. Among them, split() will be most useful.</li>
</ol>
</div>
</div>
</div>
