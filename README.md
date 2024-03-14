<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><p align="center" dir="auto">
  <a target="_blank" rel="noopener noreferrer" href="/ai-winter/ros_motion_planning/blob/master/assets/cover.png"><img src="/ai-winter/ros_motion_planning/raw/master/assets/cover.png" style="max-width: 100%;"></a>
</p>
<p align="center" dir="auto">
    <a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/32726402c2ef647119d3754eb05cca1a60f3d04bf8d9347a5c054f0246f5b3fd/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f5562756e74752d32302e30342d6f72616e67653f6c6f676f3d5562756e7475265562756e74752d32302e3034"><img width="100px" height="20px" src="https://camo.githubusercontent.com/32726402c2ef647119d3754eb05cca1a60f3d04bf8d9347a5c054f0246f5b3fd/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f5562756e74752d32302e30342d6f72616e67653f6c6f676f3d5562756e7475265562756e74752d32302e3034" alt="乌班图" data-canonical-src="https://img.shields.io/badge/Ubuntu-20.04-orange?logo=Ubuntu&amp;Ubuntu-20.04" style="max-width: 100%;"></a>
    <a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/dc9cf1410d0eeb6cb314017d8b650a8442f235dd8f9366d9eaf1c4601a2d8fdc/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f524f532d6e6f657469632d626c75653f6c6f676f3d524f5326524f533d6e6f65746963"><img width="100px" height="20px" src="https://camo.githubusercontent.com/dc9cf1410d0eeb6cb314017d8b650a8442f235dd8f9366d9eaf1c4601a2d8fdc/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f524f532d6e6f657469632d626c75653f6c6f676f3d524f5326524f533d6e6f65746963" alt="活性氧" data-canonical-src="https://img.shields.io/badge/ROS-noetic-blue?logo=ROS&amp;ROS=noetic" style="max-width: 100%;"></a>
</p>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ROS运动规划</font></font></h1><a id="user-content-ros-motion-planning" class="anchor" aria-label="永久链接：ROS 运动规划" href="#ros-motion-planning"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">机器人运动规划</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是一个计算问题，涉及找到一系列有效配置以将机器人从源移动到目的地。</font><font style="vertical-align: inherit;">一般包括</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">路径搜索</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">轨迹优化</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<ul dir="auto">
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">路径搜索</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：基于障碍物等路径约束，找到机器人从源点到目的地且不发生任何碰撞的最佳顺序。</font></font></p>
</li>
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">轨迹规划</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：基于运动学、动力学和障碍物，根据路径优化从源到目的地的运动状态轨迹。</font></font></p>
</li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该存储库提供了常见运动规划</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">算法的实现</font><font style="vertical-align: inherit;">。</font></font><a href="https://blog.csdn.net/frigidwinter/category_11410243.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">理论分析可以在运动规划</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中找到</font><font style="vertical-align: inherit;">。</font><font style="vertical-align: inherit;">此外，我们还提供</font></font><a href="https://github.com/ai-winter/python_motion_planning"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Python</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><a href="https://github.com/ai-winter/matlab_motion_planning"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MATLAB</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">版本。</font></font></p>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">欢迎您的星星、分叉和 PR！</font></font></strong></p>
<p dir="auto"><animated-image data-catalyst=""><a target="_blank" rel="noopener noreferrer" href="/ai-winter/ros_motion_planning/blob/master/assets/demo.gif" data-target="animated-image.originalLink"><img src="/ai-winter/ros_motion_planning/raw/master/assets/demo.gif" alt="演示.gif" style="max-width: 100%; display: inline-block;" data-target="animated-image.originalImage"></a>
      <span class="AnimatedImagePlayer" data-target="animated-image.player" hidden="">
        <a data-target="animated-image.replacedLink" class="AnimatedImagePlayer-images" href="https://github.com/ai-winter/ros_motion_planning/blob/master/assets/demo.gif" target="_blank">
          
        <span data-target="animated-image.imageContainer">
            <img data-target="animated-image.replacedImage" alt="演示.gif" class="AnimatedImagePlayer-animatedImage" src="https://github.com/ai-winter/ros_motion_planning/raw/master/assets/demo.gif" style="display: block; opacity: 1;">
          <canvas class="AnimatedImagePlayer-stillImage" aria-hidden="true" width="800" height="355"></canvas></span></a>
        <button data-target="animated-image.imageButton" class="AnimatedImagePlayer-images" tabindex="-1" aria-label="Play demo.gif" hidden=""></button>
        <span class="AnimatedImagePlayer-controls" data-target="animated-image.controls" hidden="">
          <button data-target="animated-image.playButton" class="AnimatedImagePlayer-button" aria-label="Play demo.gif">
            <svg aria-hidden="true" focusable="false" class="octicon icon-play" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M4 13.5427V2.45734C4 1.82607 4.69692 1.4435 5.2295 1.78241L13.9394 7.32507C14.4334 7.63943 14.4334 8.36057 13.9394 8.67493L5.2295 14.2176C4.69692 14.5565 4 14.1739 4 13.5427Z">
            </path></svg>
            <svg aria-hidden="true" focusable="false" class="octicon icon-pause" width="16" height="16" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg">
              <rect x="4" y="2" width="3" height="12" rx="1"></rect>
              <rect x="9" y="2" width="3" height="12" rx="1"></rect>
            </svg>
          </button>
          <a data-target="animated-image.openButton" aria-label="在新窗口中打开" class="AnimatedImagePlayer-button" href="https://github.com/ai-winter/ros_motion_planning/blob/master/assets/demo.gif" target="_blank">
            <svg aria-hidden="true" class="octicon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
              <path fill-rule="evenodd" d="M10.604 1h4.146a.25.25 0 01.25.25v4.146a.25.25 0 01-.427.177L13.03 4.03 9.28 7.78a.75.75 0 01-1.06-1.06l3.75-3.75-1.543-1.543A.25.25 0 0110.604 1zM3.75 2A1.75 1.75 0 002 3.75v8.5c0 .966.784 1.75 1.75 1.75h8.5A1.75 1.75 0 0014 12.25v-3.5a.75.75 0 00-1.5 0v3.5a.25.25 0 01-.25.25h-8.5a.25.25 0 01-.25-.25v-8.5a.25.25 0 01.25-.25h3.5a.75.75 0 000-1.5h-3.5z"></path>
            </svg>
          </a>
        </span>
      </span></animated-image></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">内容</font></font></h2><a id="user-content-contents" class="anchor" aria-label="永久链接： 内容" href="#contents"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><a href="#0"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">3分钟快速启动</font></font></a></li>
<li><a href="#1"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文档</font></font></a></li>
<li><a href="#2"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">工具链</font></font></a></li>
<li><a href="#3"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">版本</font></font></a></li>
<li><a href="#4"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">致谢</font></font></a></li>
<li><a href="#5"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">执照</font></font></a></li>
<li><a href="#6"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">维护</font></font></a></li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><span id="user-content-0"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">0. 3分钟快速启动</font></font></span></h2><a id="user-content-0-quick-start-within-3-minutes" class="anchor" aria-label="永久链接：0. 3 分钟内快速启动" href="#0-quick-start-within-3-minutes"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 ROS Noetic 在 ubuntu 20.04 LTS 上进行测试。</font></font></em></p>
<ol dir="auto">
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装</font></font><a href="http://wiki.ros.org/ROS/Installation" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ROS （</font></font></a><font style="vertical-align: inherit;"></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">建议</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">桌面完整版</font><font style="vertical-align: inherit;">）。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装 git。</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>sudo apt install git</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="sudo apt install git" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装依赖</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">OSQP</font></font></li>
</ul>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>git clone -b release-0.6.3 --recursive https://github.com/oxfordcontrol/osqp
<span class="pl-c1">cd</span> osqp <span class="pl-k">&amp;&amp;</span> mkdir build <span class="pl-k">&amp;&amp;</span> <span class="pl-c1">cd</span> build
cmake .. -DBUILD_SHARED_LIBS=ON
make -j6
sudo make install
sudo cp /usr/local/include/osqp/<span class="pl-k">*</span> /usr/local/include</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="git clone -b release-0.6.3 --recursive https://github.com/oxfordcontrol/osqp
cd osqp &amp;&amp; mkdir build &amp;&amp; cd build
cmake .. -DBUILD_SHARED_LIBS=ON
make -j6
sudo make install
sudo cp /usr/local/include/osqp/* /usr/local/include" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">OSQP-本征</font></font></li>
</ul>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>git clone https://github.com/robotology/osqp-eigen.git
<span class="pl-c1">cd</span> osqp-eigen <span class="pl-k">&amp;&amp;</span> mkdir build <span class="pl-k">&amp;&amp;</span> <span class="pl-c1">cd</span> build
cmake ..
make
sudo make install</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="git clone https://github.com/robotology/osqp-eigen.git
cd osqp-eigen &amp;&amp; mkdir build &amp;&amp; cd build
cmake ..
make
sudo make install" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">其他依赖。</font></font></li>
</ul>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>sudo apt install python-is-python3 \
ros-noetic-amcl \
ros-noetic-base-local-planner \
ros-noetic-map-server \
ros-noetic-move-base \
ros-noetic-navfn</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="sudo apt install python-is-python3 \
ros-noetic-amcl \
ros-noetic-base-local-planner \
ros-noetic-map-server \
ros-noetic-move-base \
ros-noetic-navfn" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">克隆存储库。</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>git clone https://github.com/ai-winter/ros_motion_planning.git</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="git clone https://github.com/ai-winter/ros_motion_planning.git" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">编译代码。</font></font></p>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">注意：如果遇到 libignition 依赖错误，</font><font style="vertical-align: inherit;">请参阅</font></font><a href="https://github.com/ai-winter/ros_motion_planning/issues/48" data-hovercard-type="issue" data-hovercard-url="/ai-winter/ros_motion_planning/issues/48/hovercard"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">#48 。</font></font></a><font style="vertical-align: inherit;"></font></strong></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c1">cd</span> ros_motion_planning/
catkin_make
<span class="pl-c"><span class="pl-c">#</span> or catkin build</span>
<span class="pl-c"><span class="pl-c">#</span> you may need to install it by: sudo apt install python-catkin-tools</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="cd ros_motion_planning/
catkin_make
# or catkin build
# you may need to install it by: sudo apt install python-catkin-tools" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">执行代码。</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c1">cd</span> scripts/
./main.sh</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="cd scripts/
./main.sh" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<blockquote>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">注意：修改启动文件可能不会产生任何效果，因为它们是由 Python 脚本根据</font></font><code>src/user_config/user_config.yaml</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您运行</font></font><code>main.sh</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">. </font><font style="vertical-align: inherit;">因此，您应该修改配置而</font></font><code>user_config.yaml</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不是启动文件。</font></font></p>
</blockquote>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用RViz 中的</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2D 导航目标</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">来选择目标。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">移动！</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可以使用其他脚本快速关闭它们。</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>./killpro.sh</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="./killpro.sh" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</li>
</ol>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1.</font></font><span id="user-content-1"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文件</font></font></span></h2><a id="user-content-1-document" class="anchor" aria-label="永久链接：1.文档" href="#1-document"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">整体文件结构如下所示。</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>ros_motion_planner
├── assets
├── scripts
└── src
    ├── core
    │&nbsp;&nbsp; ├── global_planner
    │&nbsp;&nbsp; ├── local_planner
    │&nbsp;&nbsp; ├── curve_generation
    │&nbsp;&nbsp; └── utils
    ├── sim_env             # simulation environment
    │&nbsp;&nbsp; ├── config
    │&nbsp;&nbsp; ├── launch
    │&nbsp;&nbsp; ├── maps
    │&nbsp;&nbsp; ├── meshes
    │&nbsp;&nbsp; ├── models
    │&nbsp;&nbsp; ├── rviz
    │&nbsp;&nbsp; ├── urdf
    │&nbsp;&nbsp; └── worlds
    ├── third_party
    │&nbsp;&nbsp; ├── dynamic_rviz_config
    │&nbsp;&nbsp; ├── dynamic_xml_config
    │&nbsp;&nbsp; ├── gazebo_plugins
    │&nbsp;&nbsp; └── rviz_plugins
    └── user_config         # user configure file
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="ros_motion_planner
├── assets
├── scripts
└── src
    ├── core
    │&nbsp;&nbsp; ├── global_planner
    │&nbsp;&nbsp; ├── local_planner
    │&nbsp;&nbsp; ├── curve_generation
    │&nbsp;&nbsp; └── utils
    ├── sim_env             # simulation environment
    │&nbsp;&nbsp; ├── config
    │&nbsp;&nbsp; ├── launch
    │&nbsp;&nbsp; ├── maps
    │&nbsp;&nbsp; ├── meshes
    │&nbsp;&nbsp; ├── models
    │&nbsp;&nbsp; ├── rviz
    │&nbsp;&nbsp; ├── urdf
    │&nbsp;&nbsp; └── worlds
    ├── third_party
    │&nbsp;&nbsp; ├── dynamic_rviz_config
    │&nbsp;&nbsp; ├── dynamic_xml_config
    │&nbsp;&nbsp; ├── gazebo_plugins
    │&nbsp;&nbsp; └── rviz_plugins
    └── user_config         # user configure file" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为了更好地理解项目代码，可以使用doxygen工具生成详细的接口文档。</font><font style="vertical-align: inherit;">首先安装 doxygen 和 graphviz。</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>sudo apt-get install doxygen graphviz</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="sudo apt-get install doxygen graphviz" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">然后启动 doxygen，你可以在 中找到文档</font></font><code>./docs/html/index.html</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>doxygen</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="doxygen" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有关项目用途的更多信息，请参阅下表。</font></font></p>
<table>
<thead>
<tr>
<th align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">指数</font></font></th>
<th align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文档</font></font></th>
<th align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">介绍</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">0</font></font></td>
<td align="center"><a href="https://github.com/ai-winter/ros_motion_planning/blob/master/docs/configuration.md"><img src="https://camo.githubusercontent.com/17893cfb392fcbd206f602173dbc44ae87657e8b3bbedb028007ae531c63c264/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f636f6e6669672d677265793f6c6f676f3d524f53" alt="地位" data-canonical-src="https://img.shields.io/badge/config-grey?logo=ROS" style="max-width: 100%;"></a></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">介绍如何动态配置机器人类型、规划算法、环境障碍物等参数。</font></font></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1</font></font></td>
<td align="center"><a href="https://github.com/ai-winter/ros_motion_planning/blob/master/docs/docker.md"><img src="https://camo.githubusercontent.com/7e633e5520e61fac7bb05a659029fe3235be390169157d3f2a5258a812dbbf28/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f646f636b65722d677265793f6c6f676f3d524f53" alt="地位" data-canonical-src="https://img.shields.io/badge/docker-grey?logo=ROS" style="max-width: 100%;"></a></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">介绍如何使用Docker方便地搭建项目环境并进行模拟。</font></font></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2</font></font></td>
<td align="center"><a href="https://github.com/ai-winter/ros_motion_planning/blob/master/docs/realworld.md"><img src="https://camo.githubusercontent.com/5e01c89e310a64bbad5c41416bac4fdad60fec60e4cf5c2e74fb8bfb6a3d81e6/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f7265616c2d677265793f6c6f676f3d524f53" alt="地位" data-canonical-src="https://img.shields.io/badge/real-grey?logo=ROS" style="max-width: 100%;"></a></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">介绍如何基于此存储库中提供的算法构建真实的机器人应用程序。</font></font></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">3</font></font></td>
<td align="center"><a href="https://github.com/ai-winter/ros_motion_planning/blob/master/docs/history.md"><img src="https://camo.githubusercontent.com/820d8cda21c60f85972277ab0abbfc172ee316a6275a7338f4b0d0d988d2e0a4/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f686973746f72792d677265793f6c6f676f3d524f53" alt="地位" data-canonical-src="https://img.shields.io/badge/history-grey?logo=ROS" style="max-width: 100%;"></a></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">重要更新。</font></font></td>
</tr>
</tbody>
</table>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">02.</font></font><span id="user-content-2"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">工具链</font></font></span></h2><a id="user-content-02-tool-chains" class="anchor" aria-label="永久链接：02.工具链" href="#02-tool-chains"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为了运动规划系统的高效运行，我们提供了一系列用户友好的模拟工具，允许按需选择这些轻量级存储库。</font></font></p>
<table>
<thead>
<tr>
<th align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">工具版本</font></font></th>
<th align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">介绍</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td align="center"><a href="https://github.com/ai-winter/ros_pedestrians_simulation"><img src="https://camo.githubusercontent.com/1bc6c93deef999688ab9addcbb843a0ec5417b168f975bf82c014824c80a9690/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f5065646573747269616e2d76322e302d3841324245323f6c6f676f3d696c6564656672616e63656d6f62696c69746573" alt="地位" data-canonical-src="https://img.shields.io/badge/Pedestrian-v2.0-8A2BE2?logo=iledefrancemobilites" style="max-width: 100%;"></a></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这是一个针对具有碰撞属性的行人的 Gazebo 插件。</font><font style="vertical-align: inherit;">您可以使用插件轻松地在 ROS 中构建动态环境。</font></font></td>
</tr>
<tr>
<td align="center"><a href="https://github.com/ai-winter/path_visualization_plugins"><img src="https://camo.githubusercontent.com/058e962864330d68e8e04021119a3f3347e5d9cac03a84b18a2643a7188a4633/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f524d50562d76322e302d3841324245323f6c6f676f3d76" alt="地位" data-canonical-src="https://img.shields.io/badge/RMPV-v2.0-8A2BE2?logo=v" style="max-width: 100%;"></a></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该存储库提供了基于 ROS 的可视化 Rviz 插件，用于路径规划和曲线生成算法。</font></font></td>
</tr>
</tbody>
</table>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><span id="user-content-3"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">03.版本</font></font></span></h2><a id="user-content-03-version" class="anchor" aria-label="永久链接：03.版本" href="#03-version"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">全局规划师</font></font></h3><a id="user-content-global-planner" class="anchor" aria-label="永久链接：全球规划师" href="#global-planner"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<table>
<thead>
<tr>
<th align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">规划师</font></font></th>
<th align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">版本</font></font></th>
<th align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">动画片</font></font></th>
<th align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文件</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td align="center"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">GBFS</font></font></strong></td>
<td align="center"><a href="https://github.com/ai-winter/ros_motion_planning/blob/master/src/core/global_planner/graph_planner/src/a_star.cpp"><img src="https://camo.githubusercontent.com/e312b1e6ef783ffbf72cf17901860d5a912e2c1e2e756a1d51236fe0c39c654f/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f646f6e652d76312e302d627269676874677265656e" alt="地位" data-canonical-src="https://img.shields.io/badge/done-v1.0-brightgreen" style="max-width: 100%;"></a></td>
<td align="center"><animated-image data-catalyst=""><a target="_blank" rel="noopener noreferrer" href="/ai-winter/ros_motion_planning/blob/master/assets/gbfs_ros.gif" data-target="animated-image.originalLink"><img src="/ai-winter/ros_motion_planning/raw/master/assets/gbfs_ros.gif" alt="gbfs_ros.gif" style="max-width: 100%; display: inline-block;" data-target="animated-image.originalImage"></a>
      <span class="AnimatedImagePlayer" data-target="animated-image.player" hidden="">
        <a data-target="animated-image.replacedLink" class="AnimatedImagePlayer-images" href="https://github.com/ai-winter/ros_motion_planning/blob/master/assets/gbfs_ros.gif" target="_blank">
          
        <span data-target="animated-image.imageContainer">
            <img data-target="animated-image.replacedImage" alt="gbfs_ros.gif" class="AnimatedImagePlayer-animatedImage" src="https://github.com/ai-winter/ros_motion_planning/raw/master/assets/gbfs_ros.gif" style="display: block; opacity: 1;">
          <canvas class="AnimatedImagePlayer-stillImage" aria-hidden="true" width="314" height="236"></canvas></span></a>
        <button data-target="animated-image.imageButton" class="AnimatedImagePlayer-images" tabindex="-1" aria-label="Play gbfs_ros.gif" hidden=""></button>
        <span class="AnimatedImagePlayer-controls" data-target="animated-image.controls" hidden="">
          <button data-target="animated-image.playButton" class="AnimatedImagePlayer-button" aria-label="Play gbfs_ros.gif">
            <svg aria-hidden="true" focusable="false" class="octicon icon-play" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M4 13.5427V2.45734C4 1.82607 4.69692 1.4435 5.2295 1.78241L13.9394 7.32507C14.4334 7.63943 14.4334 8.36057 13.9394 8.67493L5.2295 14.2176C4.69692 14.5565 4 14.1739 4 13.5427Z">
            </path></svg>
            <svg aria-hidden="true" focusable="false" class="octicon icon-pause" width="16" height="16" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg">
              <rect x="4" y="2" width="3" height="12" rx="1"></rect>
              <rect x="9" y="2" width="3" height="12" rx="1"></rect>
            </svg>
          </button>
          <a data-target="animated-image.openButton" aria-label="Open gbfs_ros.gif in new window" class="AnimatedImagePlayer-button" href="https://github.com/ai-winter/ros_motion_planning/blob/master/assets/gbfs_ros.gif" target="_blank">
            <svg aria-hidden="true" class="octicon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
              <path fill-rule="evenodd" d="M10.604 1h4.146a.25.25 0 01.25.25v4.146a.25.25 0 01-.427.177L13.03 4.03 9.28 7.78a.75.75 0 01-1.06-1.06l3.75-3.75-1.543-1.543A.25.25 0 0110.604 1zM3.75 2A1.75 1.75 0 002 3.75v8.5c0 .966.784 1.75 1.75 1.75h8.5A1.75 1.75 0 0014 12.25v-3.5a.75.75 0 00-1.5 0v3.5a.25.25 0 01-.25.25h-8.5a.25.25 0 01-.25-.25v-8.5a.25.25 0 01.25-.25h3.5a.75.75 0 000-1.5h-3.5z"></path>
            </svg>
          </a>
        </span>
      </span></animated-image></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">-</font></font></td>
</tr>
<tr>
<td align="center"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">迪克斯特拉</font></font></strong></td>
<td align="center"><a href="https://github.com/ai-winter/ros_motion_planning/blob/master/src/core/global_planner/graph_planner/src/a_star.cpp"><img src="https://camo.githubusercontent.com/e312b1e6ef783ffbf72cf17901860d5a912e2c1e2e756a1d51236fe0c39c654f/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f646f6e652d76312e302d627269676874677265656e" alt="地位" data-canonical-src="https://img.shields.io/badge/done-v1.0-brightgreen" style="max-width: 100%;"></a></td>
<td align="center"><animated-image data-catalyst=""><a target="_blank" rel="noopener noreferrer" href="/ai-winter/ros_motion_planning/blob/master/assets/dijkstra_ros.gif" data-target="animated-image.originalLink"><img src="/ai-winter/ros_motion_planning/raw/master/assets/dijkstra_ros.gif" alt="dijkstra_ros.gif" style="max-width: 100%; display: inline-block;" data-target="animated-image.originalImage"></a>
      <span class="AnimatedImagePlayer" data-target="animated-image.player" hidden="">
        <a data-target="animated-image.replacedLink" class="AnimatedImagePlayer-images" href="https://github.com/ai-winter/ros_motion_planning/blob/master/assets/dijkstra_ros.gif" target="_blank">
          
        <span data-target="animated-image.imageContainer">
            <img data-target="animated-image.replacedImage" alt="dijkstra_ros.gif" class="AnimatedImagePlayer-animatedImage" src="https://github.com/ai-winter/ros_motion_planning/raw/master/assets/dijkstra_ros.gif" style="display: block; opacity: 1;">
          <canvas class="AnimatedImagePlayer-stillImage" aria-hidden="true" width="340" height="255"></canvas></span></a>
        <button data-target="animated-image.imageButton" class="AnimatedImagePlayer-images" tabindex="-1" aria-label="Play dijkstra_ros.gif" hidden=""></button>
        <span class="AnimatedImagePlayer-controls" data-target="animated-image.controls" hidden="">
          <button data-target="animated-image.playButton" class="AnimatedImagePlayer-button" aria-label="Play dijkstra_ros.gif">
            <svg aria-hidden="true" focusable="false" class="octicon icon-play" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M4 13.5427V2.45734C4 1.82607 4.69692 1.4435 5.2295 1.78241L13.9394 7.32507C14.4334 7.63943 14.4334 8.36057 13.9394 8.67493L5.2295 14.2176C4.69692 14.5565 4 14.1739 4 13.5427Z">
            </path></svg>
            <svg aria-hidden="true" focusable="false" class="octicon icon-pause" width="16" height="16" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg">
              <rect x="4" y="2" width="3" height="12" rx="1"></rect>
              <rect x="9" y="2" width="3" height="12" rx="1"></rect>
            </svg>
          </button>
          <a data-target="animated-image.openButton" aria-label="Open dijkstra_ros.gif in new window" class="AnimatedImagePlayer-button" href="https://github.com/ai-winter/ros_motion_planning/blob/master/assets/dijkstra_ros.gif" target="_blank">
            <svg aria-hidden="true" class="octicon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
              <path fill-rule="evenodd" d="M10.604 1h4.146a.25.25 0 01.25.25v4.146a.25.25 0 01-.427.177L13.03 4.03 9.28 7.78a.75.75 0 01-1.06-1.06l3.75-3.75-1.543-1.543A.25.25 0 0110.604 1zM3.75 2A1.75 1.75 0 002 3.75v8.5c0 .966.784 1.75 1.75 1.75h8.5A1.75 1.75 0 0014 12.25v-3.5a.75.75 0 00-1.5 0v3.5a.25.25 0 01-.25.25h-8.5a.25.25 0 01-.25-.25v-8.5a.25.25 0 01.25-.25h3.5a.75.75 0 000-1.5h-3.5z"></path>
            </svg>
          </a>
        </span>
      </span></animated-image></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">-</font></font></td>
</tr>
<tr>
<td align="center"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">A*</font></font></strong></td>
<td align="center"><a href="https://github.com/ai-winter/ros_motion_planning/blob/master/src/core/global_planner/graph_planner/src/a_star.cpp"><img src="https://camo.githubusercontent.com/76b0b0f688f0d73b64ff1fe06b05fe37112c5a7952efd07c914f1bd07aa28882/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f646f6e652d76312e312d627269676874677265656e" alt="地位" data-canonical-src="https://img.shields.io/badge/done-v1.1-brightgreen" style="max-width: 100%;"></a></td>
<td align="center"><animated-image data-catalyst=""><a target="_blank" rel="noopener noreferrer" href="/ai-winter/ros_motion_planning/blob/master/assets/a_star_ros.gif" data-target="animated-image.originalLink"><img src="/ai-winter/ros_motion_planning/raw/master/assets/a_star_ros.gif" alt="a_star_ros.gif" style="max-width: 100%; display: inline-block;" data-target="animated-image.originalImage"></a>
      <span class="AnimatedImagePlayer" data-target="animated-image.player" hidden="">
        <a data-target="animated-image.replacedLink" class="AnimatedImagePlayer-images" href="https://github.com/ai-winter/ros_motion_planning/blob/master/assets/a_star_ros.gif" target="_blank">
          
        <span data-target="animated-image.imageContainer">
            <img data-target="animated-image.replacedImage" alt="a_star_ros.gif" class="AnimatedImagePlayer-animatedImage" src="https://github.com/ai-winter/ros_motion_planning/raw/master/assets/a_star_ros.gif" style="display: block; opacity: 1;">
          <canvas class="AnimatedImagePlayer-stillImage" aria-hidden="true" width="314" height="236"></canvas></span></a>
        <button data-target="animated-image.imageButton" class="AnimatedImagePlayer-images" tabindex="-1" aria-label="Play a_star_ros.gif" hidden=""></button>
        <span class="AnimatedImagePlayer-controls" data-target="animated-image.controls" hidden="">
          <button data-target="animated-image.playButton" class="AnimatedImagePlayer-button" aria-label="Play a_star_ros.gif">
            <svg aria-hidden="true" focusable="false" class="octicon icon-play" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M4 13.5427V2.45734C4 1.82607 4.69692 1.4435 5.2295 1.78241L13.9394 7.32507C14.4334 7.63943 14.4334 8.36057 13.9394 8.67493L5.2295 14.2176C4.69692 14.5565 4 14.1739 4 13.5427Z">
            </path></svg>
            <svg aria-hidden="true" focusable="false" class="octicon icon-pause" width="16" height="16" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg">
              <rect x="4" y="2" width="3" height="12" rx="1"></rect>
              <rect x="9" y="2" width="3" height="12" rx="1"></rect>
            </svg>
          </button>
          <a data-target="animated-image.openButton" aria-label="Open a_star_ros.gif in new window" class="AnimatedImagePlayer-button" href="https://github.com/ai-winter/ros_motion_planning/blob/master/assets/a_star_ros.gif" target="_blank">
            <svg aria-hidden="true" class="octicon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
              <path fill-rule="evenodd" d="M10.604 1h4.146a.25.25 0 01.25.25v4.146a.25.25 0 01-.427.177L13.03 4.03 9.28 7.78a.75.75 0 01-1.06-1.06l3.75-3.75-1.543-1.543A.25.25 0 0110.604 1zM3.75 2A1.75 1.75 0 002 3.75v8.5c0 .966.784 1.75 1.75 1.75h8.5A1.75 1.75 0 0014 12.25v-3.5a.75.75 0 00-1.5 0v3.5a.25.25 0 01-.25.25h-8.5a.25.25 0 01-.25-.25v-8.5a.25.25 0 01.25-.25h3.5a.75.75 0 000-1.5h-3.5z"></path>
            </svg>
          </a>
        </span>
      </span></animated-image></td>
<td align="center"><a href="https://ieeexplore.ieee.org/document/4082128" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">启发式确定最小成本路径的形式基础</font></font></a></td>
</tr>
<tr>
<td align="center"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">杰普斯</font></font></strong></td>
<td align="center"><a href="https://github.com/ai-winter/ros_motion_planning/blob/master/src/core/global_planner/graph_planner/src/jump_point_search.cpp"><img src="https://camo.githubusercontent.com/e312b1e6ef783ffbf72cf17901860d5a912e2c1e2e756a1d51236fe0c39c654f/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f646f6e652d76312e302d627269676874677265656e" alt="地位" data-canonical-src="https://img.shields.io/badge/done-v1.0-brightgreen" style="max-width: 100%;"></a></td>
<td align="center"><animated-image data-catalyst=""><a target="_blank" rel="noopener noreferrer" href="/ai-winter/ros_motion_planning/blob/master/assets/jps_ros.gif" data-target="animated-image.originalLink"><img src="/ai-winter/ros_motion_planning/raw/master/assets/jps_ros.gif" alt="jps_ros.gif" style="max-width: 100%; display: inline-block;" data-target="animated-image.originalImage"></a>
      <span class="AnimatedImagePlayer" data-target="animated-image.player" hidden="">
        <a data-target="animated-image.replacedLink" class="AnimatedImagePlayer-images" href="https://github.com/ai-winter/ros_motion_planning/blob/master/assets/jps_ros.gif" target="_blank">
          
        <span data-target="animated-image.imageContainer">
            <img data-target="animated-image.replacedImage" alt="jps_ros.gif" class="AnimatedImagePlayer-animatedImage" src="https://github.com/ai-winter/ros_motion_planning/raw/master/assets/jps_ros.gif" style="display: block; opacity: 1;">
          <canvas class="AnimatedImagePlayer-stillImage" aria-hidden="true" width="314" height="236"></canvas></span></a>
        <button data-target="animated-image.imageButton" class="AnimatedImagePlayer-images" tabindex="-1" aria-label="Play jps_ros.gif" hidden=""></button>
        <span class="AnimatedImagePlayer-controls" data-target="animated-image.controls" hidden="">
          <button data-target="animated-image.playButton" class="AnimatedImagePlayer-button" aria-label="Play jps_ros.gif">
            <svg aria-hidden="true" focusable="false" class="octicon icon-play" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M4 13.5427V2.45734C4 1.82607 4.69692 1.4435 5.2295 1.78241L13.9394 7.32507C14.4334 7.63943 14.4334 8.36057 13.9394 8.67493L5.2295 14.2176C4.69692 14.5565 4 14.1739 4 13.5427Z">
            </path></svg>
            <svg aria-hidden="true" focusable="false" class="octicon icon-pause" width="16" height="16" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg">
              <rect x="4" y="2" width="3" height="12" rx="1"></rect>
              <rect x="9" y="2" width="3" height="12" rx="1"></rect>
            </svg>
          </button>
          <a data-target="animated-image.openButton" aria-label="Open jps_ros.gif in new window" class="AnimatedImagePlayer-button" href="https://github.com/ai-winter/ros_motion_planning/blob/master/assets/jps_ros.gif" target="_blank">
            <svg aria-hidden="true" class="octicon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
              <path fill-rule="evenodd" d="M10.604 1h4.146a.25.25 0 01.25.25v4.146a.25.25 0 01-.427.177L13.03 4.03 9.28 7.78a.75.75 0 01-1.06-1.06l3.75-3.75-1.543-1.543A.25.25 0 0110.604 1zM3.75 2A1.75 1.75 0 002 3.75v8.5c0 .966.784 1.75 1.75 1.75h8.5A1.75 1.75 0 0014 12.25v-3.5a.75.75 0 00-1.5 0v3.5a.25.25 0 01-.25.25h-8.5a.25.25 0 01-.25-.25v-8.5a.25.25 0 01.25-.25h3.5a.75.75 0 000-1.5h-3.5z"></path>
            </svg>
          </a>
        </span>
      </span></animated-image></td>
<td align="center"><a href="https://ojs.aaai.org/index.php/AAAI/article/view/7994" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用于网格地图上寻路的在线图修剪</font></font></a></td>
</tr>
<tr>
<td align="center"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">D*</font></font></strong></td>
<td align="center"><a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/e312b1e6ef783ffbf72cf17901860d5a912e2c1e2e756a1d51236fe0c39c654f/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f646f6e652d76312e302d627269676874677265656e"><img src="https://camo.githubusercontent.com/e312b1e6ef783ffbf72cf17901860d5a912e2c1e2e756a1d51236fe0c39c654f/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f646f6e652d76312e302d627269676874677265656e" alt="地位" data-canonical-src="https://img.shields.io/badge/done-v1.0-brightgreen" style="max-width: 100%;"></a></td>
<td align="center"><animated-image data-catalyst=""><a target="_blank" rel="noopener noreferrer" href="/ai-winter/ros_motion_planning/blob/master/assets/d_star_ros.gif" data-target="animated-image.originalLink"><img src="/ai-winter/ros_motion_planning/raw/master/assets/d_star_ros.gif" alt="d_star_ros.gif" style="max-width: 100%; display: inline-block;" data-target="animated-image.originalImage"></a>
      <span class="AnimatedImagePlayer" data-target="animated-image.player" hidden="">
        <a data-target="animated-image.replacedLink" class="AnimatedImagePlayer-images" href="https://github.com/ai-winter/ros_motion_planning/blob/master/assets/d_star_ros.gif" target="_blank">
          
        <span data-target="animated-image.imageContainer">
            <img data-target="animated-image.replacedImage" alt="d_star_ros.gif" class="AnimatedImagePlayer-animatedImage" src="https://github.com/ai-winter/ros_motion_planning/raw/master/assets/d_star_ros.gif" style="display: block; opacity: 1;">
          <canvas class="AnimatedImagePlayer-stillImage" aria-hidden="true" width="314" height="236"></canvas></span></a>
        <button data-target="animated-image.imageButton" class="AnimatedImagePlayer-images" tabindex="-1" aria-label="Play d_star_ros.gif" hidden=""></button>
        <span class="AnimatedImagePlayer-controls" data-target="animated-image.controls" hidden="">
          <button data-target="animated-image.playButton" class="AnimatedImagePlayer-button" aria-label="Play d_star_ros.gif">
            <svg aria-hidden="true" focusable="false" class="octicon icon-play" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M4 13.5427V2.45734C4 1.82607 4.69692 1.4435 5.2295 1.78241L13.9394 7.32507C14.4334 7.63943 14.4334 8.36057 13.9394 8.67493L5.2295 14.2176C4.69692 14.5565 4 14.1739 4 13.5427Z">
            </path></svg>
            <svg aria-hidden="true" focusable="false" class="octicon icon-pause" width="16" height="16" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg">
              <rect x="4" y="2" width="3" height="12" rx="1"></rect>
              <rect x="9" y="2" width="3" height="12" rx="1"></rect>
            </svg>
          </button>
          <a data-target="animated-image.openButton" aria-label="Open d_star_ros.gif in new window" class="AnimatedImagePlayer-button" href="https://github.com/ai-winter/ros_motion_planning/blob/master/assets/d_star_ros.gif" target="_blank">
            <svg aria-hidden="true" class="octicon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
              <path fill-rule="evenodd" d="M10.604 1h4.146a.25.25 0 01.25.25v4.146a.25.25 0 01-.427.177L13.03 4.03 9.28 7.78a.75.75 0 01-1.06-1.06l3.75-3.75-1.543-1.543A.25.25 0 0110.604 1zM3.75 2A1.75 1.75 0 002 3.75v8.5c0 .966.784 1.75 1.75 1.75h8.5A1.75 1.75 0 0014 12.25v-3.5a.75.75 0 00-1.5 0v3.5a.25.25 0 01-.25.25h-8.5a.25.25 0 01-.25-.25v-8.5a.25.25 0 01.25-.25h3.5a.75.75 0 000-1.5h-3.5z"></path>
            </svg>
          </a>
        </span>
      </span></animated-image></td>
<td align="center"><a href="http://web.mit.edu/16.412j/www/html/papers/original_dstar_icra94.pdf" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">部分已知环境的最优高效路径规划</font></font></a></td>
</tr>
<tr>
<td align="center"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">LPA*</font></font></strong></td>
<td align="center"><a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/e312b1e6ef783ffbf72cf17901860d5a912e2c1e2e756a1d51236fe0c39c654f/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f646f6e652d76312e302d627269676874677265656e"><img src="https://camo.githubusercontent.com/e312b1e6ef783ffbf72cf17901860d5a912e2c1e2e756a1d51236fe0c39c654f/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f646f6e652d76312e302d627269676874677265656e" alt="地位" data-canonical-src="https://img.shields.io/badge/done-v1.0-brightgreen" style="max-width: 100%;"></a></td>
<td align="center"><animated-image data-catalyst=""><a target="_blank" rel="noopener noreferrer" href="/ai-winter/ros_motion_planning/blob/master/assets/lpa_star_ros.gif" data-target="animated-image.originalLink"><img src="/ai-winter/ros_motion_planning/raw/master/assets/lpa_star_ros.gif" alt="lpa_star_ros.gif" style="max-width: 100%; display: inline-block;" data-target="animated-image.originalImage"></a>
      <span class="AnimatedImagePlayer" data-target="animated-image.player" hidden="">
        <a data-target="animated-image.replacedLink" class="AnimatedImagePlayer-images" href="https://github.com/ai-winter/ros_motion_planning/blob/master/assets/lpa_star_ros.gif" target="_blank">
          
        <span data-target="animated-image.imageContainer">
            <img data-target="animated-image.replacedImage" alt="lpa_star_ros.gif" class="AnimatedImagePlayer-animatedImage" src="https://github.com/ai-winter/ros_motion_planning/raw/master/assets/lpa_star_ros.gif" style="display: block; opacity: 1;">
          <canvas class="AnimatedImagePlayer-stillImage" aria-hidden="true" width="314" height="236"></canvas></span></a>
        <button data-target="animated-image.imageButton" class="AnimatedImagePlayer-images" tabindex="-1" aria-label="Play lpa_star_ros.gif" hidden=""></button>
        <span class="AnimatedImagePlayer-controls" data-target="animated-image.controls" hidden="">
          <button data-target="animated-image.playButton" class="AnimatedImagePlayer-button" aria-label="Play lpa_star_ros.gif">
            <svg aria-hidden="true" focusable="false" class="octicon icon-play" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M4 13.5427V2.45734C4 1.82607 4.69692 1.4435 5.2295 1.78241L13.9394 7.32507C14.4334 7.63943 14.4334 8.36057 13.9394 8.67493L5.2295 14.2176C4.69692 14.5565 4 14.1739 4 13.5427Z">
            </path></svg>
            <svg aria-hidden="true" focusable="false" class="octicon icon-pause" width="16" height="16" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg">
              <rect x="4" y="2" width="3" height="12" rx="1"></rect>
              <rect x="9" y="2" width="3" height="12" rx="1"></rect>
            </svg>
          </button>
          <a data-target="animated-image.openButton" aria-label="Open lpa_star_ros.gif in new window" class="AnimatedImagePlayer-button" href="https://github.com/ai-winter/ros_motion_planning/blob/master/assets/lpa_star_ros.gif" target="_blank">
            <svg aria-hidden="true" class="octicon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
              <path fill-rule="evenodd" d="M10.604 1h4.146a.25.25 0 01.25.25v4.146a.25.25 0 01-.427.177L13.03 4.03 9.28 7.78a.75.75 0 01-1.06-1.06l3.75-3.75-1.543-1.543A.25.25 0 0110.604 1zM3.75 2A1.75 1.75 0 002 3.75v8.5c0 .966.784 1.75 1.75 1.75h8.5A1.75 1.75 0 0014 12.25v-3.5a.75.75 0 00-1.5 0v3.5a.25.25 0 01-.25.25h-8.5a.25.25 0 01-.25-.25v-8.5a.25.25 0 01.25-.25h3.5a.75.75 0 000-1.5h-3.5z"></path>
            </svg>
          </a>
        </span>
      </span></animated-image></td>
<td align="center"><a href="https://www.cs.cmu.edu/~maxim/files/aij04.pdf" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">终身规划A*</font></font></a></td>
</tr>
<tr>
<td align="center"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">D* 精简版</font></font></strong></td>
<td align="center"><a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/e312b1e6ef783ffbf72cf17901860d5a912e2c1e2e756a1d51236fe0c39c654f/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f646f6e652d76312e302d627269676874677265656e"><img src="https://camo.githubusercontent.com/e312b1e6ef783ffbf72cf17901860d5a912e2c1e2e756a1d51236fe0c39c654f/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f646f6e652d76312e302d627269676874677265656e" alt="地位" data-canonical-src="https://img.shields.io/badge/done-v1.0-brightgreen" style="max-width: 100%;"></a></td>
<td align="center"><animated-image data-catalyst=""><a target="_blank" rel="noopener noreferrer" href="/ai-winter/ros_motion_planning/blob/master/assets/d_star_lite_ros.gif" data-target="animated-image.originalLink"><img src="/ai-winter/ros_motion_planning/raw/master/assets/d_star_lite_ros.gif" alt="d_star_lite_ros.gif" style="max-width: 100%; display: inline-block;" data-target="animated-image.originalImage"></a>
      <span class="AnimatedImagePlayer" data-target="animated-image.player" hidden="">
        <a data-target="animated-image.replacedLink" class="AnimatedImagePlayer-images" href="https://github.com/ai-winter/ros_motion_planning/blob/master/assets/d_star_lite_ros.gif" target="_blank">
          
        <span data-target="animated-image.imageContainer">
            <img data-target="animated-image.replacedImage" alt="d_star_lite_ros.gif" class="AnimatedImagePlayer-animatedImage" src="https://github.com/ai-winter/ros_motion_planning/raw/master/assets/d_star_lite_ros.gif" style="display: block; opacity: 1;">
          <canvas class="AnimatedImagePlayer-stillImage" aria-hidden="true" width="314" height="236"></canvas></span></a>
        <button data-target="animated-image.imageButton" class="AnimatedImagePlayer-images" tabindex="-1" aria-label="Play d_star_lite_ros.gif" hidden=""></button>
        <span class="AnimatedImagePlayer-controls" data-target="animated-image.controls" hidden="">
          <button data-target="animated-image.playButton" class="AnimatedImagePlayer-button" aria-label="Play d_star_lite_ros.gif">
            <svg aria-hidden="true" focusable="false" class="octicon icon-play" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M4 13.5427V2.45734C4 1.82607 4.69692 1.4435 5.2295 1.78241L13.9394 7.32507C14.4334 7.63943 14.4334 8.36057 13.9394 8.67493L5.2295 14.2176C4.69692 14.5565 4 14.1739 4 13.5427Z">
            </path></svg>
            <svg aria-hidden="true" focusable="false" class="octicon icon-pause" width="16" height="16" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg">
              <rect x="4" y="2" width="3" height="12" rx="1"></rect>
              <rect x="9" y="2" width="3" height="12" rx="1"></rect>
            </svg>
          </button>
          <a data-target="animated-image.openButton" aria-label="Open d_star_lite_ros.gif in new window" class="AnimatedImagePlayer-button" href="https://github.com/ai-winter/ros_motion_planning/blob/master/assets/d_star_lite_ros.gif" target="_blank">
            <svg aria-hidden="true" class="octicon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
              <path fill-rule="evenodd" d="M10.604 1h4.146a.25.25 0 01.25.25v4.146a.25.25 0 01-.427.177L13.03 4.03 9.28 7.78a.75.75 0 01-1.06-1.06l3.75-3.75-1.543-1.543A.25.25 0 0110.604 1zM3.75 2A1.75 1.75 0 002 3.75v8.5c0 .966.784 1.75 1.75 1.75h8.5A1.75 1.75 0 0014 12.25v-3.5a.75.75 0 00-1.5 0v3.5a.25.25 0 01-.25.25h-8.5a.25.25 0 01-.25-.25v-8.5a.25.25 0 01.25-.25h3.5a.75.75 0 000-1.5h-3.5z"></path>
            </svg>
          </a>
        </span>
      </span></animated-image></td>
<td align="center"><a href="http://idm-lab.org/bib/abstracts/papers/aaai02b.pdf" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">D* 精简版</font></font></a></td>
</tr>
<tr>
<td align="center"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">沃罗诺伊</font></font></strong></td>
<td align="center"><a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/e312b1e6ef783ffbf72cf17901860d5a912e2c1e2e756a1d51236fe0c39c654f/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f646f6e652d76312e302d627269676874677265656e"><img src="https://camo.githubusercontent.com/e312b1e6ef783ffbf72cf17901860d5a912e2c1e2e756a1d51236fe0c39c654f/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f646f6e652d76312e302d627269676874677265656e" alt="地位" data-canonical-src="https://img.shields.io/badge/done-v1.0-brightgreen" style="max-width: 100%;"></a></td>
<td align="center"><animated-image data-catalyst=""><a target="_blank" rel="noopener noreferrer" href="/ai-winter/ros_motion_planning/blob/master/assets/voronoi_ros.gif" data-target="animated-image.originalLink"><img src="/ai-winter/ros_motion_planning/raw/master/assets/voronoi_ros.gif" alt="voronoi_ros.gif" style="max-width: 100%; display: inline-block;" data-target="animated-image.originalImage"></a>
      <span class="AnimatedImagePlayer" data-target="animated-image.player" hidden="">
        <a data-target="animated-image.replacedLink" class="AnimatedImagePlayer-images" href="https://github.com/ai-winter/ros_motion_planning/blob/master/assets/voronoi_ros.gif" target="_blank">
          
        <span data-target="animated-image.imageContainer">
            <img data-target="animated-image.replacedImage" alt="voronoi_ros.gif" class="AnimatedImagePlayer-animatedImage" src="https://github.com/ai-winter/ros_motion_planning/raw/master/assets/voronoi_ros.gif" style="display: block; opacity: 1;">
          <canvas class="AnimatedImagePlayer-stillImage" aria-hidden="true" width="438" height="425"></canvas></span></a>
        <button data-target="animated-image.imageButton" class="AnimatedImagePlayer-images" tabindex="-1" aria-label="Play voronoi_ros.gif" hidden=""></button>
        <span class="AnimatedImagePlayer-controls" data-target="animated-image.controls" hidden="">
          <button data-target="animated-image.playButton" class="AnimatedImagePlayer-button" aria-label="Play voronoi_ros.gif">
            <svg aria-hidden="true" focusable="false" class="octicon icon-play" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M4 13.5427V2.45734C4 1.82607 4.69692 1.4435 5.2295 1.78241L13.9394 7.32507C14.4334 7.63943 14.4334 8.36057 13.9394 8.67493L5.2295 14.2176C4.69692 14.5565 4 14.1739 4 13.5427Z">
            </path></svg>
            <svg aria-hidden="true" focusable="false" class="octicon icon-pause" width="16" height="16" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg">
              <rect x="4" y="2" width="3" height="12" rx="1"></rect>
              <rect x="9" y="2" width="3" height="12" rx="1"></rect>
            </svg>
          </button>
          <a data-target="animated-image.openButton" aria-label="Open voronoi_ros.gif in new window" class="AnimatedImagePlayer-button" href="https://github.com/ai-winter/ros_motion_planning/blob/master/assets/voronoi_ros.gif" target="_blank">
            <svg aria-hidden="true" class="octicon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
              <path fill-rule="evenodd" d="M10.604 1h4.146a.25.25 0 01.25.25v4.146a.25.25 0 01-.427.177L13.03 4.03 9.28 7.78a.75.75 0 01-1.06-1.06l3.75-3.75-1.543-1.543A.25.25 0 0110.604 1zM3.75 2A1.75 1.75 0 002 3.75v8.5c0 .966.784 1.75 1.75 1.75h8.5A1.75 1.75 0 0014 12.25v-3.5a.75.75 0 00-1.5 0v3.5a.25.25 0 01-.25.25h-8.5a.25.25 0 01-.25-.25v-8.5a.25.25 0 01.25-.25h3.5a.75.75 0 000-1.5h-3.5z"></path>
            </svg>
          </a>
        </span>
      </span></animated-image></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">-</font></font></td>
</tr>
<tr>
<td align="center"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">西塔*</font></font></strong></td>
<td align="center"><a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/e312b1e6ef783ffbf72cf17901860d5a912e2c1e2e756a1d51236fe0c39c654f/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f646f6e652d76312e302d627269676874677265656e"><img src="https://camo.githubusercontent.com/e312b1e6ef783ffbf72cf17901860d5a912e2c1e2e756a1d51236fe0c39c654f/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f646f6e652d76312e302d627269676874677265656e" alt="地位" data-canonical-src="https://img.shields.io/badge/done-v1.0-brightgreen" style="max-width: 100%;"></a></td>
<td align="center"><animated-image data-catalyst=""><a target="_blank" rel="noopener noreferrer" href="/ai-winter/ros_motion_planning/blob/master/assets/theta_star_ros.gif" data-target="animated-image.originalLink"><img src="/ai-winter/ros_motion_planning/raw/master/assets/theta_star_ros.gif" alt="theta_star_ros.gif" style="max-width: 100%; display: inline-block;" data-target="animated-image.originalImage"></a>
      <span class="AnimatedImagePlayer" data-target="animated-image.player" hidden="">
        <a data-target="animated-image.replacedLink" class="AnimatedImagePlayer-images" href="https://github.com/ai-winter/ros_motion_planning/blob/master/assets/theta_star_ros.gif" target="_blank">
          
        <span data-target="animated-image.imageContainer">
            <img data-target="animated-image.replacedImage" alt="theta_star_ros.gif" class="AnimatedImagePlayer-animatedImage" src="https://github.com/ai-winter/ros_motion_planning/raw/master/assets/theta_star_ros.gif" style="display: block; opacity: 1;">
          <canvas class="AnimatedImagePlayer-stillImage" aria-hidden="true" width="314" height="309"></canvas></span></a>
        <button data-target="animated-image.imageButton" class="AnimatedImagePlayer-images" tabindex="-1" aria-label="Play theta_star_ros.gif" hidden=""></button>
        <span class="AnimatedImagePlayer-controls" data-target="animated-image.controls" hidden="">
          <button data-target="animated-image.playButton" class="AnimatedImagePlayer-button" aria-label="Play theta_star_ros.gif">
            <svg aria-hidden="true" focusable="false" class="octicon icon-play" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M4 13.5427V2.45734C4 1.82607 4.69692 1.4435 5.2295 1.78241L13.9394 7.32507C14.4334 7.63943 14.4334 8.36057 13.9394 8.67493L5.2295 14.2176C4.69692 14.5565 4 14.1739 4 13.5427Z">
            </path></svg>
            <svg aria-hidden="true" focusable="false" class="octicon icon-pause" width="16" height="16" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg">
              <rect x="4" y="2" width="3" height="12" rx="1"></rect>
              <rect x="9" y="2" width="3" height="12" rx="1"></rect>
            </svg>
          </button>
          <a data-target="animated-image.openButton" aria-label="Open theta_star_ros.gif in new window" class="AnimatedImagePlayer-button" href="https://github.com/ai-winter/ros_motion_planning/blob/master/assets/theta_star_ros.gif" target="_blank">
            <svg aria-hidden="true" class="octicon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
              <path fill-rule="evenodd" d="M10.604 1h4.146a.25.25 0 01.25.25v4.146a.25.25 0 01-.427.177L13.03 4.03 9.28 7.78a.75.75 0 01-1.06-1.06l3.75-3.75-1.543-1.543A.25.25 0 0110.604 1zM3.75 2A1.75 1.75 0 002 3.75v8.5c0 .966.784 1.75 1.75 1.75h8.5A1.75 1.75 0 0014 12.25v-3.5a.75.75 0 00-1.5 0v3.5a.25.25 0 01-.25.25h-8.5a.25.25 0 01-.25-.25v-8.5a.25.25 0 01.25-.25h3.5a.75.75 0 000-1.5h-3.5z"></path>
            </svg>
          </a>
        </span>
      </span></animated-image></td>
<td align="center"><a href="https://www.jair.org/index.php/jair/article/view/10676" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Theta*：网格上的任意角度路径规划</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="https://ieeexplore.ieee.org/abstract/document/5979769" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">非均匀成本图上的任意角度路径规划</font></font></a></td>
</tr>
<tr>
<td align="center"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">懒惰西塔*</font></font></strong></td>
<td align="center"><a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/e312b1e6ef783ffbf72cf17901860d5a912e2c1e2e756a1d51236fe0c39c654f/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f646f6e652d76312e302d627269676874677265656e"><img src="https://camo.githubusercontent.com/e312b1e6ef783ffbf72cf17901860d5a912e2c1e2e756a1d51236fe0c39c654f/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f646f6e652d76312e302d627269676874677265656e" alt="地位" data-canonical-src="https://img.shields.io/badge/done-v1.0-brightgreen" style="max-width: 100%;"></a></td>
<td align="center"><animated-image data-catalyst=""><a target="_blank" rel="noopener noreferrer" href="/ai-winter/ros_motion_planning/blob/master/assets/lazy_theta_star_ros.gif" data-target="animated-image.originalLink"><img src="/ai-winter/ros_motion_planning/raw/master/assets/lazy_theta_star_ros.gif" alt="懒惰_theta_star_ros.gif" style="max-width: 100%; display: inline-block;" data-target="animated-image.originalImage"></a>
      <span class="AnimatedImagePlayer" data-target="animated-image.player" hidden="">
        <a data-target="animated-image.replacedLink" class="AnimatedImagePlayer-images" href="https://github.com/ai-winter/ros_motion_planning/blob/master/assets/lazy_theta_star_ros.gif" target="_blank">
          
        <span data-target="animated-image.imageContainer">
            <img data-target="animated-image.replacedImage" alt="懒惰_theta_star_ros.gif" class="AnimatedImagePlayer-animatedImage" src="https://github.com/ai-winter/ros_motion_planning/raw/master/assets/lazy_theta_star_ros.gif" style="display: block; opacity: 1;">
          <canvas class="AnimatedImagePlayer-stillImage" aria-hidden="true" width="314" height="309"></canvas></span></a>
        <button data-target="animated-image.imageButton" class="AnimatedImagePlayer-images" tabindex="-1" aria-label="Play 懒惰_theta_star_ros.gif" hidden=""></button>
        <span class="AnimatedImagePlayer-controls" data-target="animated-image.controls" hidden="">
          <button data-target="animated-image.playButton" class="AnimatedImagePlayer-button" aria-label="Play 懒惰_theta_star_ros.gif">
            <svg aria-hidden="true" focusable="false" class="octicon icon-play" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M4 13.5427V2.45734C4 1.82607 4.69692 1.4435 5.2295 1.78241L13.9394 7.32507C14.4334 7.63943 14.4334 8.36057 13.9394 8.67493L5.2295 14.2176C4.69692 14.5565 4 14.1739 4 13.5427Z">
            </path></svg>
            <svg aria-hidden="true" focusable="false" class="octicon icon-pause" width="16" height="16" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg">
              <rect x="4" y="2" width="3" height="12" rx="1"></rect>
              <rect x="9" y="2" width="3" height="12" rx="1"></rect>
            </svg>
          </button>
          <a data-target="animated-image.openButton" aria-label="Open 懒惰_theta_star_ros.gif in new window" class="AnimatedImagePlayer-button" href="https://github.com/ai-winter/ros_motion_planning/blob/master/assets/lazy_theta_star_ros.gif" target="_blank">
            <svg aria-hidden="true" class="octicon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
              <path fill-rule="evenodd" d="M10.604 1h4.146a.25.25 0 01.25.25v4.146a.25.25 0 01-.427.177L13.03 4.03 9.28 7.78a.75.75 0 01-1.06-1.06l3.75-3.75-1.543-1.543A.25.25 0 0110.604 1zM3.75 2A1.75 1.75 0 002 3.75v8.5c0 .966.784 1.75 1.75 1.75h8.5A1.75 1.75 0 0014 12.25v-3.5a.75.75 0 00-1.5 0v3.5a.25.25 0 01-.25.25h-8.5a.25.25 0 01-.25-.25v-8.5a.25.25 0 01.25-.25h3.5a.75.75 0 000-1.5h-3.5z"></path>
            </svg>
          </a>
        </span>
      </span></animated-image></td>
<td align="center"><a href="https://ojs.aaai.org/index.php/AAAI/article/view/7566" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Lazy Theta*：3D 中的任意角度路径规划和路径长度分析</font></font></a></td>
</tr>
<tr>
<td align="center"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">S-θ*</font></font></strong></td>
<td align="center"><a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/e312b1e6ef783ffbf72cf17901860d5a912e2c1e2e756a1d51236fe0c39c654f/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f646f6e652d76312e302d627269676874677265656e"><img src="https://camo.githubusercontent.com/e312b1e6ef783ffbf72cf17901860d5a912e2c1e2e756a1d51236fe0c39c654f/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f646f6e652d76312e302d627269676874677265656e" alt="地位" data-canonical-src="https://img.shields.io/badge/done-v1.0-brightgreen" style="max-width: 100%;"></a></td>
<td align="center"><animated-image data-catalyst=""><a target="_blank" rel="noopener noreferrer" href="/ai-winter/ros_motion_planning/blob/master/assets/s_theta_star_ros.gif" data-target="animated-image.originalLink" hidden=""><img src="/ai-winter/ros_motion_planning/raw/master/assets/s_theta_star_ros.gif" alt="s_theta_star_ros.gif" style="max-width: 100%;" data-target="animated-image.originalImage" hidden=""></a>
      <span class="AnimatedImagePlayer" data-target="animated-image.player">
        <a data-target="animated-image.replacedLink" class="AnimatedImagePlayer-images" href="https://github.com/ai-winter/ros_motion_planning/blob/master/assets/s_theta_star_ros.gif" target="_blank">
          <span data-target="animated-image.imageContainer">
            <img data-target="animated-image.replacedImage" alt="s_theta_star_ros.gif" class="AnimatedImagePlayer-animatedImage" src="https://github.com/ai-winter/ros_motion_planning/raw/master/assets/s_theta_star_ros.gif">
          </span>
        </a>
        <button data-target="animated-image.imageButton" class="AnimatedImagePlayer-images" tabindex="-1"></button>
        <span class="AnimatedImagePlayer-controls" data-target="animated-image.controls">
          <button data-target="animated-image.playButton" class="AnimatedImagePlayer-button">
            <svg aria-hidden="true" focusable="false" class="octicon icon-play" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M4 13.5427V2.45734C4 1.82607 4.69692 1.4435 5.2295 1.78241L13.9394 7.32507C14.4334 7.63943 14.4334 8.36057 13.9394 8.67493L5.2295 14.2176C4.69692 14.5565 4 14.1739 4 13.5427Z">
            </path></svg>
            <svg aria-hidden="true" focusable="false" class="octicon icon-pause" width="16" height="16" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg">
              <rect x="4" y="2" width="3" height="12" rx="1"></rect>
              <rect x="9" y="2" width="3" height="12" rx="1"></rect>
            </svg>
          </button>
          <a data-target="animated-image.openButton" aria-label="在新窗口中打开" class="AnimatedImagePlayer-button" href="https://github.com/ai-winter/ros_motion_planning/blob/master/assets/s_theta_star_ros.gif" target="_blank">
            <svg aria-hidden="true" class="octicon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
              <path fill-rule="evenodd" d="M10.604 1h4.146a.25.25 0 01.25.25v4.146a.25.25 0 01-.427.177L13.03 4.03 9.28 7.78a.75.75 0 01-1.06-1.06l3.75-3.75-1.543-1.543A.25.25 0 0110.604 1zM3.75 2A1.75 1.75 0 002 3.75v8.5c0 .966.784 1.75 1.75 1.75h8.5A1.75 1.75 0 0014 12.25v-3.5a.75.75 0 00-1.5 0v3.5a.25.25 0 01-.25.25h-8.5a.25.25 0 01-.25-.25v-8.5a.25.25 0 01.25-.25h3.5a.75.75 0 000-1.5h-3.5z"></path>
            </svg>
          </a>
        </span>
      </span></animated-image></td>
<td align="center"><a href="https://link.springer.com/chapter/10.1007/978-1-4471-4739-8_8" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">S-Theta*：低转向路径规划算法</font></font></a></td>
</tr>
<tr>
<td align="center"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">混合动力A*</font></font></strong></td>
<td align="center"><a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/e312b1e6ef783ffbf72cf17901860d5a912e2c1e2e756a1d51236fe0c39c654f/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f646f6e652d76312e302d627269676874677265656e"><img src="https://camo.githubusercontent.com/e312b1e6ef783ffbf72cf17901860d5a912e2c1e2e756a1d51236fe0c39c654f/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f646f6e652d76312e302d627269676874677265656e" alt="地位" data-canonical-src="https://img.shields.io/badge/done-v1.0-brightgreen" style="max-width: 100%;"></a></td>
<td align="center"><animated-image data-catalyst=""><a target="_blank" rel="noopener noreferrer" href="/ai-winter/ros_motion_planning/blob/master/assets/hybrid_astar_ros.gif" data-target="animated-image.originalLink"><img src="/ai-winter/ros_motion_planning/raw/master/assets/hybrid_astar_ros.gif" alt="Hybrid_astar_ros.gif" style="max-width: 100%; display: inline-block;" data-target="animated-image.originalImage"></a>
      <span class="AnimatedImagePlayer" data-target="animated-image.player" hidden="">
        <a data-target="animated-image.replacedLink" class="AnimatedImagePlayer-images" href="https://github.com/ai-winter/ros_motion_planning/blob/master/assets/hybrid_astar_ros.gif" target="_blank">
          
        <span data-target="animated-image.imageContainer">
            <img data-target="animated-image.replacedImage" alt="Hybrid_astar_ros.gif" class="AnimatedImagePlayer-animatedImage" src="https://github.com/ai-winter/ros_motion_planning/raw/master/assets/hybrid_astar_ros.gif" style="display: block; opacity: 1;">
          <canvas class="AnimatedImagePlayer-stillImage" aria-hidden="true" width="314" height="312"></canvas></span></a>
        <button data-target="animated-image.imageButton" class="AnimatedImagePlayer-images" tabindex="-1" aria-label="Play Hybrid_astar_ros.gif" hidden=""></button>
        <span class="AnimatedImagePlayer-controls" data-target="animated-image.controls" hidden="">
          <button data-target="animated-image.playButton" class="AnimatedImagePlayer-button" aria-label="Play Hybrid_astar_ros.gif">
            <svg aria-hidden="true" focusable="false" class="octicon icon-play" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M4 13.5427V2.45734C4 1.82607 4.69692 1.4435 5.2295 1.78241L13.9394 7.32507C14.4334 7.63943 14.4334 8.36057 13.9394 8.67493L5.2295 14.2176C4.69692 14.5565 4 14.1739 4 13.5427Z">
            </path></svg>
            <svg aria-hidden="true" focusable="false" class="octicon icon-pause" width="16" height="16" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg">
              <rect x="4" y="2" width="3" height="12" rx="1"></rect>
              <rect x="9" y="2" width="3" height="12" rx="1"></rect>
            </svg>
          </button>
          <a data-target="animated-image.openButton" aria-label="Open Hybrid_astar_ros.gif in new window" class="AnimatedImagePlayer-button" href="https://github.com/ai-winter/ros_motion_planning/blob/master/assets/hybrid_astar_ros.gif" target="_blank">
            <svg aria-hidden="true" class="octicon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
              <path fill-rule="evenodd" d="M10.604 1h4.146a.25.25 0 01.25.25v4.146a.25.25 0 01-.427.177L13.03 4.03 9.28 7.78a.75.75 0 01-1.06-1.06l3.75-3.75-1.543-1.543A.25.25 0 0110.604 1zM3.75 2A1.75 1.75 0 002 3.75v8.5c0 .966.784 1.75 1.75 1.75h8.5A1.75 1.75 0 0014 12.25v-3.5a.75.75 0 00-1.5 0v3.5a.25.25 0 01-.25.25h-8.5a.25.25 0 01-.25-.25v-8.5a.25.25 0 01.25-.25h3.5a.75.75 0 000-1.5h-3.5z"></path>
            </svg>
          </a>
        </span>
      </span></animated-image></td>
<td align="center"><a href="https://ai.stanford.edu/~ddolgov/papers/dolgov_gpp_stair08.pdf" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">自动驾驶路径规划中的实用搜索技术</font></font></a></td>
</tr>
<tr>
<td align="center"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">恢复时间</font></font></strong></td>
<td align="center"><a href="https://github.com/ai-winter/ros_motion_planning/blob/master/src/core/global_planner/sample_planner/src/rrt.cpp"><img src="https://camo.githubusercontent.com/76b0b0f688f0d73b64ff1fe06b05fe37112c5a7952efd07c914f1bd07aa28882/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f646f6e652d76312e312d627269676874677265656e" alt="地位" data-canonical-src="https://img.shields.io/badge/done-v1.1-brightgreen" style="max-width: 100%;"></a></td>
<td align="center"><animated-image data-catalyst=""><a target="_blank" rel="noopener noreferrer" href="/ai-winter/ros_motion_planning/blob/master/assets/rrt_ros.gif" data-target="animated-image.originalLink"><img src="/ai-winter/ros_motion_planning/raw/master/assets/rrt_ros.gif" alt="rrt_ros.gif" style="max-width: 100%; display: inline-block;" data-target="animated-image.originalImage"></a>
      <span class="AnimatedImagePlayer" data-target="animated-image.player" hidden="">
        <a data-target="animated-image.replacedLink" class="AnimatedImagePlayer-images" href="https://github.com/ai-winter/ros_motion_planning/blob/master/assets/rrt_ros.gif" target="_blank">
          
        <span data-target="animated-image.imageContainer">
            <img data-target="animated-image.replacedImage" alt="rrt_ros.gif" class="AnimatedImagePlayer-animatedImage" src="https://github.com/ai-winter/ros_motion_planning/raw/master/assets/rrt_ros.gif" style="display: block; opacity: 1;">
          <canvas class="AnimatedImagePlayer-stillImage" aria-hidden="true" width="340" height="255"></canvas></span></a>
        <button data-target="animated-image.imageButton" class="AnimatedImagePlayer-images" tabindex="-1" aria-label="Play rrt_ros.gif" hidden=""></button>
        <span class="AnimatedImagePlayer-controls" data-target="animated-image.controls" hidden="">
          <button data-target="animated-image.playButton" class="AnimatedImagePlayer-button" aria-label="Play rrt_ros.gif">
            <svg aria-hidden="true" focusable="false" class="octicon icon-play" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M4 13.5427V2.45734C4 1.82607 4.69692 1.4435 5.2295 1.78241L13.9394 7.32507C14.4334 7.63943 14.4334 8.36057 13.9394 8.67493L5.2295 14.2176C4.69692 14.5565 4 14.1739 4 13.5427Z">
            </path></svg>
            <svg aria-hidden="true" focusable="false" class="octicon icon-pause" width="16" height="16" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg">
              <rect x="4" y="2" width="3" height="12" rx="1"></rect>
              <rect x="9" y="2" width="3" height="12" rx="1"></rect>
            </svg>
          </button>
          <a data-target="animated-image.openButton" aria-label="Open rrt_ros.gif in new window" class="AnimatedImagePlayer-button" href="https://github.com/ai-winter/ros_motion_planning/blob/master/assets/rrt_ros.gif" target="_blank">
            <svg aria-hidden="true" class="octicon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
              <path fill-rule="evenodd" d="M10.604 1h4.146a.25.25 0 01.25.25v4.146a.25.25 0 01-.427.177L13.03 4.03 9.28 7.78a.75.75 0 01-1.06-1.06l3.75-3.75-1.543-1.543A.25.25 0 0110.604 1zM3.75 2A1.75 1.75 0 002 3.75v8.5c0 .966.784 1.75 1.75 1.75h8.5A1.75 1.75 0 0014 12.25v-3.5a.75.75 0 00-1.5 0v3.5a.25.25 0 01-.25.25h-8.5a.25.25 0 01-.25-.25v-8.5a.25.25 0 01.25-.25h3.5a.75.75 0 000-1.5h-3.5z"></path>
            </svg>
          </a>
        </span>
      </span></animated-image></td>
<td align="center"><a href="http://msl.cs.uiuc.edu/~lavalle/papers/Lav98c.pdf" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">快速探索随机树：路径规划的新工具</font></font></a></td>
</tr>
<tr>
<td align="center"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">恢复时间*</font></font></strong></td>
<td align="center"><a href="https://github.com/ai-winter/ros_motion_planning/blob/master/src/core/global_planner/sample_planner/src/rrt_star.cpp"><img src="https://camo.githubusercontent.com/e312b1e6ef783ffbf72cf17901860d5a912e2c1e2e756a1d51236fe0c39c654f/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f646f6e652d76312e302d627269676874677265656e" alt="地位" data-canonical-src="https://img.shields.io/badge/done-v1.0-brightgreen" style="max-width: 100%;"></a></td>
<td align="center"><animated-image data-catalyst=""><a target="_blank" rel="noopener noreferrer" href="/ai-winter/ros_motion_planning/blob/master/assets/rrt_star_ros.gif" data-target="animated-image.originalLink"><img src="/ai-winter/ros_motion_planning/raw/master/assets/rrt_star_ros.gif" alt="rrt_star_ros.gif" style="max-width: 100%; display: inline-block;" data-target="animated-image.originalImage"></a>
      <span class="AnimatedImagePlayer" data-target="animated-image.player" hidden="">
        <a data-target="animated-image.replacedLink" class="AnimatedImagePlayer-images" href="https://github.com/ai-winter/ros_motion_planning/blob/master/assets/rrt_star_ros.gif" target="_blank">
          
        <span data-target="animated-image.imageContainer">
            <img data-target="animated-image.replacedImage" alt="rrt_star_ros.gif" class="AnimatedImagePlayer-animatedImage" src="https://github.com/ai-winter/ros_motion_planning/raw/master/assets/rrt_star_ros.gif" style="display: block; opacity: 1;">
          <canvas class="AnimatedImagePlayer-stillImage" aria-hidden="true" width="340" height="255"></canvas></span></a>
        <button data-target="animated-image.imageButton" class="AnimatedImagePlayer-images" tabindex="-1" aria-label="Play rrt_star_ros.gif" hidden=""></button>
        <span class="AnimatedImagePlayer-controls" data-target="animated-image.controls" hidden="">
          <button data-target="animated-image.playButton" class="AnimatedImagePlayer-button" aria-label="Play rrt_star_ros.gif">
            <svg aria-hidden="true" focusable="false" class="octicon icon-play" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M4 13.5427V2.45734C4 1.82607 4.69692 1.4435 5.2295 1.78241L13.9394 7.32507C14.4334 7.63943 14.4334 8.36057 13.9394 8.67493L5.2295 14.2176C4.69692 14.5565 4 14.1739 4 13.5427Z">
            </path></svg>
            <svg aria-hidden="true" focusable="false" class="octicon icon-pause" width="16" height="16" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg">
              <rect x="4" y="2" width="3" height="12" rx="1"></rect>
              <rect x="9" y="2" width="3" height="12" rx="1"></rect>
            </svg>
          </button>
          <a data-target="animated-image.openButton" aria-label="Open rrt_star_ros.gif in new window" class="AnimatedImagePlayer-button" href="https://github.com/ai-winter/ros_motion_planning/blob/master/assets/rrt_star_ros.gif" target="_blank">
            <svg aria-hidden="true" class="octicon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
              <path fill-rule="evenodd" d="M10.604 1h4.146a.25.25 0 01.25.25v4.146a.25.25 0 01-.427.177L13.03 4.03 9.28 7.78a.75.75 0 01-1.06-1.06l3.75-3.75-1.543-1.543A.25.25 0 0110.604 1zM3.75 2A1.75 1.75 0 002 3.75v8.5c0 .966.784 1.75 1.75 1.75h8.5A1.75 1.75 0 0014 12.25v-3.5a.75.75 0 00-1.5 0v3.5a.25.25 0 01-.25.25h-8.5a.25.25 0 01-.25-.25v-8.5a.25.25 0 01.25-.25h3.5a.75.75 0 000-1.5h-3.5z"></path>
            </svg>
          </a>
        </span>
      </span></animated-image></td>
<td align="center"><a href="https://journals.sagepub.com/doi/abs/10.1177/0278364911406761" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基于采样的最佳运动规划算法</font></font></a></td>
</tr>
<tr>
<td align="center"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">知情的 RRT</font></font></strong></td>
<td align="center"><a href="https://github.com/ai-winter/ros_motion_planning/blob/master/src/core/global_planner/sample_planner/src/informed_rrt.cpp"><img src="https://camo.githubusercontent.com/e312b1e6ef783ffbf72cf17901860d5a912e2c1e2e756a1d51236fe0c39c654f/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f646f6e652d76312e302d627269676874677265656e" alt="地位" data-canonical-src="https://img.shields.io/badge/done-v1.0-brightgreen" style="max-width: 100%;"></a></td>
<td align="center"><animated-image data-catalyst=""><a target="_blank" rel="noopener noreferrer" href="/ai-winter/ros_motion_planning/blob/master/assets/informed_rrt_ros.gif" data-target="animated-image.originalLink"><img src="/ai-winter/ros_motion_planning/raw/master/assets/informed_rrt_ros.gif" alt="inform_rrt_ros.gif" style="max-width: 100%; display: inline-block;" data-target="animated-image.originalImage"></a>
      <span class="AnimatedImagePlayer" data-target="animated-image.player" hidden="">
        <a data-target="animated-image.replacedLink" class="AnimatedImagePlayer-images" href="https://github.com/ai-winter/ros_motion_planning/blob/master/assets/informed_rrt_ros.gif" target="_blank">
          
        <span data-target="animated-image.imageContainer">
            <img data-target="animated-image.replacedImage" alt="inform_rrt_ros.gif" class="AnimatedImagePlayer-animatedImage" src="https://github.com/ai-winter/ros_motion_planning/raw/master/assets/informed_rrt_ros.gif" style="display: block; opacity: 1;">
          <canvas class="AnimatedImagePlayer-stillImage" aria-hidden="true" width="340" height="255"></canvas></span></a>
        <button data-target="animated-image.imageButton" class="AnimatedImagePlayer-images" tabindex="-1" aria-label="Play inform_rrt_ros.gif" hidden=""></button>
        <span class="AnimatedImagePlayer-controls" data-target="animated-image.controls" hidden="">
          <button data-target="animated-image.playButton" class="AnimatedImagePlayer-button" aria-label="Play inform_rrt_ros.gif">
            <svg aria-hidden="true" focusable="false" class="octicon icon-play" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M4 13.5427V2.45734C4 1.82607 4.69692 1.4435 5.2295 1.78241L13.9394 7.32507C14.4334 7.63943 14.4334 8.36057 13.9394 8.67493L5.2295 14.2176C4.69692 14.5565 4 14.1739 4 13.5427Z">
            </path></svg>
            <svg aria-hidden="true" focusable="false" class="octicon icon-pause" width="16" height="16" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg">
              <rect x="4" y="2" width="3" height="12" rx="1"></rect>
              <rect x="9" y="2" width="3" height="12" rx="1"></rect>
            </svg>
          </button>
          <a data-target="animated-image.openButton" aria-label="Open inform_rrt_ros.gif in new window" class="AnimatedImagePlayer-button" href="https://github.com/ai-winter/ros_motion_planning/blob/master/assets/informed_rrt_ros.gif" target="_blank">
            <svg aria-hidden="true" class="octicon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
              <path fill-rule="evenodd" d="M10.604 1h4.146a.25.25 0 01.25.25v4.146a.25.25 0 01-.427.177L13.03 4.03 9.28 7.78a.75.75 0 01-1.06-1.06l3.75-3.75-1.543-1.543A.25.25 0 0110.604 1zM3.75 2A1.75 1.75 0 002 3.75v8.5c0 .966.784 1.75 1.75 1.75h8.5A1.75 1.75 0 0014 12.25v-3.5a.75.75 0 00-1.5 0v3.5a.25.25 0 01-.25.25h-8.5a.25.25 0 01-.25-.25v-8.5a.25.25 0 01.25-.25h3.5a.75.75 0 000-1.5h-3.5z"></path>
            </svg>
          </a>
        </span>
      </span></animated-image></td>
<td align="center"><a href="https://arxiv.org/abs/1404.2334" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通过对可接受的椭圆体启发式进行直接采样来集中优化基于采样的路径规划</font></font></a></td>
</tr>
<tr>
<td align="center"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">RRT-连接</font></font></strong></td>
<td align="center"><a href="https://github.com/ai-winter/ros_motion_planning/blob/master/src/core/global_planner/sample_planner/src/rrt_connect.cpp"><img src="https://camo.githubusercontent.com/e312b1e6ef783ffbf72cf17901860d5a912e2c1e2e756a1d51236fe0c39c654f/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f646f6e652d76312e302d627269676874677265656e" alt="地位" data-canonical-src="https://img.shields.io/badge/done-v1.0-brightgreen" style="max-width: 100%;"></a></td>
<td align="center"><animated-image data-catalyst=""><a target="_blank" rel="noopener noreferrer" href="/ai-winter/ros_motion_planning/blob/master/assets/rrt_connect_ros.gif" data-target="animated-image.originalLink"><img src="/ai-winter/ros_motion_planning/raw/master/assets/rrt_connect_ros.gif" alt="rrt_connect_ros.gif" style="max-width: 100%; display: inline-block;" data-target="animated-image.originalImage"></a>
      <span class="AnimatedImagePlayer" data-target="animated-image.player" hidden="">
        <a data-target="animated-image.replacedLink" class="AnimatedImagePlayer-images" href="https://github.com/ai-winter/ros_motion_planning/blob/master/assets/rrt_connect_ros.gif" target="_blank">
          
        <span data-target="animated-image.imageContainer">
            <img data-target="animated-image.replacedImage" alt="rrt_connect_ros.gif" class="AnimatedImagePlayer-animatedImage" src="https://github.com/ai-winter/ros_motion_planning/raw/master/assets/rrt_connect_ros.gif" style="display: block; opacity: 1;">
          <canvas class="AnimatedImagePlayer-stillImage" aria-hidden="true" width="314" height="236"></canvas></span></a>
        <button data-target="animated-image.imageButton" class="AnimatedImagePlayer-images" tabindex="-1" aria-label="Play rrt_connect_ros.gif" hidden=""></button>
        <span class="AnimatedImagePlayer-controls" data-target="animated-image.controls" hidden="">
          <button data-target="animated-image.playButton" class="AnimatedImagePlayer-button" aria-label="Play rrt_connect_ros.gif">
            <svg aria-hidden="true" focusable="false" class="octicon icon-play" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M4 13.5427V2.45734C4 1.82607 4.69692 1.4435 5.2295 1.78241L13.9394 7.32507C14.4334 7.63943 14.4334 8.36057 13.9394 8.67493L5.2295 14.2176C4.69692 14.5565 4 14.1739 4 13.5427Z">
            </path></svg>
            <svg aria-hidden="true" focusable="false" class="octicon icon-pause" width="16" height="16" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg">
              <rect x="4" y="2" width="3" height="12" rx="1"></rect>
              <rect x="9" y="2" width="3" height="12" rx="1"></rect>
            </svg>
          </button>
          <a data-target="animated-image.openButton" aria-label="Open rrt_connect_ros.gif in new window" class="AnimatedImagePlayer-button" href="https://github.com/ai-winter/ros_motion_planning/blob/master/assets/rrt_connect_ros.gif" target="_blank">
            <svg aria-hidden="true" class="octicon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
              <path fill-rule="evenodd" d="M10.604 1h4.146a.25.25 0 01.25.25v4.146a.25.25 0 01-.427.177L13.03 4.03 9.28 7.78a.75.75 0 01-1.06-1.06l3.75-3.75-1.543-1.543A.25.25 0 0110.604 1zM3.75 2A1.75 1.75 0 002 3.75v8.5c0 .966.784 1.75 1.75 1.75h8.5A1.75 1.75 0 0014 12.25v-3.5a.75.75 0 00-1.5 0v3.5a.25.25 0 01-.25.25h-8.5a.25.25 0 01-.25-.25v-8.5a.25.25 0 01.25-.25h3.5a.75.75 0 000-1.5h-3.5z"></path>
            </svg>
          </a>
        </span>
      </span></animated-image></td>
<td align="center"><a href="http://www-cgi.cs.cmu.edu/afs/cs/academic/class/15494-s12/readings/kuffner_icra2000.pdf" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">RRT-Connect：单查询路径规划的有效方法</font></font></a></td>
</tr>
<tr>
<td align="center"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">阿科</font></font></strong></td>
<td align="center"><a href="https://github.com/ai-winter/ros_motion_planning/blob/master/src/core/global_planner/evolutionary_planner/src/aco.cpp"><img src="https://camo.githubusercontent.com/e312b1e6ef783ffbf72cf17901860d5a912e2c1e2e756a1d51236fe0c39c654f/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f646f6e652d76312e302d627269676874677265656e" alt="地位" data-canonical-src="https://img.shields.io/badge/done-v1.0-brightgreen" style="max-width: 100%;"></a></td>
<td align="center"><animated-image data-catalyst=""><a target="_blank" rel="noopener noreferrer" href="/ai-winter/ros_motion_planning/blob/master/assets/aco_ros.gif" data-target="animated-image.originalLink"><img src="/ai-winter/ros_motion_planning/raw/master/assets/aco_ros.gif" alt="aco_ros.gif" style="max-width: 100%; display: inline-block;" data-target="animated-image.originalImage"></a>
      <span class="AnimatedImagePlayer" data-target="animated-image.player" hidden="">
        <a data-target="animated-image.replacedLink" class="AnimatedImagePlayer-images" href="https://github.com/ai-winter/ros_motion_planning/blob/master/assets/aco_ros.gif" target="_blank">
          
        <span data-target="animated-image.imageContainer">
            <img data-target="animated-image.replacedImage" alt="aco_ros.gif" class="AnimatedImagePlayer-animatedImage" src="https://github.com/ai-winter/ros_motion_planning/raw/master/assets/aco_ros.gif" style="display: block; opacity: 1;">
          <canvas class="AnimatedImagePlayer-stillImage" aria-hidden="true" width="340" height="340"></canvas></span></a>
        <button data-target="animated-image.imageButton" class="AnimatedImagePlayer-images" tabindex="-1" aria-label="Play aco_ros.gif" hidden=""></button>
        <span class="AnimatedImagePlayer-controls" data-target="animated-image.controls" hidden="">
          <button data-target="animated-image.playButton" class="AnimatedImagePlayer-button" aria-label="Play aco_ros.gif">
            <svg aria-hidden="true" focusable="false" class="octicon icon-play" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M4 13.5427V2.45734C4 1.82607 4.69692 1.4435 5.2295 1.78241L13.9394 7.32507C14.4334 7.63943 14.4334 8.36057 13.9394 8.67493L5.2295 14.2176C4.69692 14.5565 4 14.1739 4 13.5427Z">
            </path></svg>
            <svg aria-hidden="true" focusable="false" class="octicon icon-pause" width="16" height="16" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg">
              <rect x="4" y="2" width="3" height="12" rx="1"></rect>
              <rect x="9" y="2" width="3" height="12" rx="1"></rect>
            </svg>
          </button>
          <a data-target="animated-image.openButton" aria-label="Open aco_ros.gif in new window" class="AnimatedImagePlayer-button" href="https://github.com/ai-winter/ros_motion_planning/blob/master/assets/aco_ros.gif" target="_blank">
            <svg aria-hidden="true" class="octicon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
              <path fill-rule="evenodd" d="M10.604 1h4.146a.25.25 0 01.25.25v4.146a.25.25 0 01-.427.177L13.03 4.03 9.28 7.78a.75.75 0 01-1.06-1.06l3.75-3.75-1.543-1.543A.25.25 0 0110.604 1zM3.75 2A1.75 1.75 0 002 3.75v8.5c0 .966.784 1.75 1.75 1.75h8.5A1.75 1.75 0 0014 12.25v-3.5a.75.75 0 00-1.5 0v3.5a.25.25 0 01-.25.25h-8.5a.25.25 0 01-.25-.25v-8.5a.25.25 0 01.25-.25h3.5a.75.75 0 000-1.5h-3.5z"></path>
            </svg>
          </a>
        </span>
      </span></animated-image></td>
<td align="center"><a href="http://www.cs.yale.edu/homes/lans/readings/routing/dorigo-ants-1999.pdf" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">蚁群优化：一种新的元启发式算法</font></font></a></td>
</tr>
<tr>
<td align="center"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">遗传算法</font></font></strong></td>
<td align="center"><a href="https://github.com/ai-winter/ros_motion_planning/blob/master/src/core/global_planner/evolutionary_planner/src/ga.cpp"><img src="https://camo.githubusercontent.com/e312b1e6ef783ffbf72cf17901860d5a912e2c1e2e756a1d51236fe0c39c654f/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f646f6e652d76312e302d627269676874677265656e" alt="地位" data-canonical-src="https://img.shields.io/badge/done-v1.0-brightgreen" style="max-width: 100%;"></a></td>
<td align="center"><animated-image data-catalyst=""><a target="_blank" rel="noopener noreferrer" href="/ai-winter/ros_motion_planning/blob/master/assets/ga_ros.gif" data-target="animated-image.originalLink"><img src="/ai-winter/ros_motion_planning/raw/master/assets/ga_ros.gif" alt="ga_ros.gif" style="max-width: 100%; display: inline-block;" data-target="animated-image.originalImage"></a>
      <span class="AnimatedImagePlayer" data-target="animated-image.player" hidden="">
        <a data-target="animated-image.replacedLink" class="AnimatedImagePlayer-images" href="https://github.com/ai-winter/ros_motion_planning/blob/master/assets/ga_ros.gif" target="_blank">
          
        <span data-target="animated-image.imageContainer">
            <img data-target="animated-image.replacedImage" alt="ga_ros.gif" class="AnimatedImagePlayer-animatedImage" src="https://github.com/ai-winter/ros_motion_planning/raw/master/assets/ga_ros.gif" style="display: block; opacity: 1;">
          <canvas class="AnimatedImagePlayer-stillImage" aria-hidden="true" width="340" height="335"></canvas></span></a>
        <button data-target="animated-image.imageButton" class="AnimatedImagePlayer-images" tabindex="-1" aria-label="Play ga_ros.gif" hidden=""></button>
        <span class="AnimatedImagePlayer-controls" data-target="animated-image.controls" hidden="">
          <button data-target="animated-image.playButton" class="AnimatedImagePlayer-button" aria-label="Play ga_ros.gif">
            <svg aria-hidden="true" focusable="false" class="octicon icon-play" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M4 13.5427V2.45734C4 1.82607 4.69692 1.4435 5.2295 1.78241L13.9394 7.32507C14.4334 7.63943 14.4334 8.36057 13.9394 8.67493L5.2295 14.2176C4.69692 14.5565 4 14.1739 4 13.5427Z">
            </path></svg>
            <svg aria-hidden="true" focusable="false" class="octicon icon-pause" width="16" height="16" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg">
              <rect x="4" y="2" width="3" height="12" rx="1"></rect>
              <rect x="9" y="2" width="3" height="12" rx="1"></rect>
            </svg>
          </button>
          <a data-target="animated-image.openButton" aria-label="Open ga_ros.gif in new window" class="AnimatedImagePlayer-button" href="https://github.com/ai-winter/ros_motion_planning/blob/master/assets/ga_ros.gif" target="_blank">
            <svg aria-hidden="true" class="octicon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
              <path fill-rule="evenodd" d="M10.604 1h4.146a.25.25 0 01.25.25v4.146a.25.25 0 01-.427.177L13.03 4.03 9.28 7.78a.75.75 0 01-1.06-1.06l3.75-3.75-1.543-1.543A.25.25 0 0110.604 1zM3.75 2A1.75 1.75 0 002 3.75v8.5c0 .966.784 1.75 1.75 1.75h8.5A1.75 1.75 0 0014 12.25v-3.5a.75.75 0 00-1.5 0v3.5a.25.25 0 01-.25.25h-8.5a.25.25 0 01-.25-.25v-8.5a.25.25 0 01.25-.25h3.5a.75.75 0 000-1.5h-3.5z"></path>
            </svg>
          </a>
        </span>
      </span></animated-image></td>
<td align="center"><a href="https://ieeexplore.ieee.org/book/6267401" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">自然和人工系统的适应</font></font></a></td>
</tr>
<tr>
<td align="center"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">粒子群算法</font></font></strong></td>
<td align="center"><a href="https://github.com/ai-winter/ros_motion_planning/blob/master/src/core/global_planner/evolutionary_planner/src/pso.cpp"><img src="https://camo.githubusercontent.com/e312b1e6ef783ffbf72cf17901860d5a912e2c1e2e756a1d51236fe0c39c654f/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f646f6e652d76312e302d627269676874677265656e" alt="地位" data-canonical-src="https://img.shields.io/badge/done-v1.0-brightgreen" style="max-width: 100%;"></a></td>
<td align="center"><animated-image data-catalyst=""><a target="_blank" rel="noopener noreferrer" href="/ai-winter/ros_motion_planning/blob/master/assets/pso_ros.gif" data-target="animated-image.originalLink"><img src="/ai-winter/ros_motion_planning/raw/master/assets/pso_ros.gif" alt="pso_ros.gif" style="max-width: 100%; display: inline-block;" data-target="animated-image.originalImage"></a>
      <span class="AnimatedImagePlayer" data-target="animated-image.player" hidden="">
        <a data-target="animated-image.replacedLink" class="AnimatedImagePlayer-images" href="https://github.com/ai-winter/ros_motion_planning/blob/master/assets/pso_ros.gif" target="_blank">
          
        <span data-target="animated-image.imageContainer">
            <img data-target="animated-image.replacedImage" alt="pso_ros.gif" class="AnimatedImagePlayer-animatedImage" src="https://github.com/ai-winter/ros_motion_planning/raw/master/assets/pso_ros.gif" style="display: block; opacity: 1;">
          <canvas class="AnimatedImagePlayer-stillImage" aria-hidden="true" width="340" height="338"></canvas></span></a>
        <button data-target="animated-image.imageButton" class="AnimatedImagePlayer-images" tabindex="-1" aria-label="Play pso_ros.gif" hidden=""></button>
        <span class="AnimatedImagePlayer-controls" data-target="animated-image.controls" hidden="">
          <button data-target="animated-image.playButton" class="AnimatedImagePlayer-button" aria-label="Play pso_ros.gif">
            <svg aria-hidden="true" focusable="false" class="octicon icon-play" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M4 13.5427V2.45734C4 1.82607 4.69692 1.4435 5.2295 1.78241L13.9394 7.32507C14.4334 7.63943 14.4334 8.36057 13.9394 8.67493L5.2295 14.2176C4.69692 14.5565 4 14.1739 4 13.5427Z">
            </path></svg>
            <svg aria-hidden="true" focusable="false" class="octicon icon-pause" width="16" height="16" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg">
              <rect x="4" y="2" width="3" height="12" rx="1"></rect>
              <rect x="9" y="2" width="3" height="12" rx="1"></rect>
            </svg>
          </button>
          <a data-target="animated-image.openButton" aria-label="Open pso_ros.gif in new window" class="AnimatedImagePlayer-button" href="https://github.com/ai-winter/ros_motion_planning/blob/master/assets/pso_ros.gif" target="_blank">
            <svg aria-hidden="true" class="octicon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
              <path fill-rule="evenodd" d="M10.604 1h4.146a.25.25 0 01.25.25v4.146a.25.25 0 01-.427.177L13.03 4.03 9.28 7.78a.75.75 0 01-1.06-1.06l3.75-3.75-1.543-1.543A.25.25 0 0110.604 1zM3.75 2A1.75 1.75 0 002 3.75v8.5c0 .966.784 1.75 1.75 1.75h8.5A1.75 1.75 0 0014 12.25v-3.5a.75.75 0 00-1.5 0v3.5a.25.25 0 01-.25.25h-8.5a.25.25 0 01-.25-.25v-8.5a.25.25 0 01.25-.25h3.5a.75.75 0 000-1.5h-3.5z"></path>
            </svg>
          </a>
        </span>
      </span></animated-image></td>
<td align="center"><a href="https://ieeexplore.ieee.org/document/488968" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">粒子群优化</font></font></a></td>
</tr>
</tbody>
</table>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">当地规划师</font></font></h3><a id="user-content-local-planner" class="anchor" aria-label="永久链接：本地规划师" href="#local-planner"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<table>
<thead>
<tr>
<th align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">规划师</font></font></th>
<th align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">版本</font></font></th>
<th align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">动画片</font></font></th>
<th align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">纸</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td align="center"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">PID</font></font></strong></td>
<td align="center"><a href="https://github.com/ai-winter/ros_motion_planning/blob/master/src/core/local_planner/pid_planner/src/pid_planner.cpp"><img src="https://camo.githubusercontent.com/76b0b0f688f0d73b64ff1fe06b05fe37112c5a7952efd07c914f1bd07aa28882/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f646f6e652d76312e312d627269676874677265656e" alt="地位" data-canonical-src="https://img.shields.io/badge/done-v1.1-brightgreen" style="max-width: 100%;"></a></td>
<td align="center"><animated-image data-catalyst=""><a target="_blank" rel="noopener noreferrer" href="/ai-winter/ros_motion_planning/blob/master/assets/pid_ros.gif" data-target="animated-image.originalLink"><img src="/ai-winter/ros_motion_planning/raw/master/assets/pid_ros.gif" alt="pid_ros.gif" style="max-width: 100%; display: inline-block;" data-target="animated-image.originalImage"></a>
      <span class="AnimatedImagePlayer" data-target="animated-image.player" hidden="">
        <a data-target="animated-image.replacedLink" class="AnimatedImagePlayer-images" href="https://github.com/ai-winter/ros_motion_planning/blob/master/assets/pid_ros.gif" target="_blank">
          
        <span data-target="animated-image.imageContainer">
            <img data-target="animated-image.replacedImage" alt="pid_ros.gif" class="AnimatedImagePlayer-animatedImage" src="https://github.com/ai-winter/ros_motion_planning/raw/master/assets/pid_ros.gif" style="display: block; opacity: 1;">
          <canvas class="AnimatedImagePlayer-stillImage" aria-hidden="true" width="393" height="295"></canvas></span></a>
        <button data-target="animated-image.imageButton" class="AnimatedImagePlayer-images" tabindex="-1" aria-label="Play pid_ros.gif" hidden=""></button>
        <span class="AnimatedImagePlayer-controls" data-target="animated-image.controls" hidden="">
          <button data-target="animated-image.playButton" class="AnimatedImagePlayer-button" aria-label="Play pid_ros.gif">
            <svg aria-hidden="true" focusable="false" class="octicon icon-play" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M4 13.5427V2.45734C4 1.82607 4.69692 1.4435 5.2295 1.78241L13.9394 7.32507C14.4334 7.63943 14.4334 8.36057 13.9394 8.67493L5.2295 14.2176C4.69692 14.5565 4 14.1739 4 13.5427Z">
            </path></svg>
            <svg aria-hidden="true" focusable="false" class="octicon icon-pause" width="16" height="16" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg">
              <rect x="4" y="2" width="3" height="12" rx="1"></rect>
              <rect x="9" y="2" width="3" height="12" rx="1"></rect>
            </svg>
          </button>
          <a data-target="animated-image.openButton" aria-label="Open pid_ros.gif in new window" class="AnimatedImagePlayer-button" href="https://github.com/ai-winter/ros_motion_planning/blob/master/assets/pid_ros.gif" target="_blank">
            <svg aria-hidden="true" class="octicon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
              <path fill-rule="evenodd" d="M10.604 1h4.146a.25.25 0 01.25.25v4.146a.25.25 0 01-.427.177L13.03 4.03 9.28 7.78a.75.75 0 01-1.06-1.06l3.75-3.75-1.543-1.543A.25.25 0 0110.604 1zM3.75 2A1.75 1.75 0 002 3.75v8.5c0 .966.784 1.75 1.75 1.75h8.5A1.75 1.75 0 0014 12.25v-3.5a.75.75 0 00-1.5 0v3.5a.25.25 0 01-.25.25h-8.5a.25.25 0 01-.25-.25v-8.5a.25.25 0 01.25-.25h3.5a.75.75 0 000-1.5h-3.5z"></path>
            </svg>
          </a>
        </span>
      </span></animated-image></td>
<td align="center"><a href="https://liwanggt.github.io/files/Robotarium_CSM_Impact.pdf" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将单积分器动力学映射到独轮车控制</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">命令 </font><font style="vertical-align: inherit;">14</font></font></td>
</tr>
<tr>
<td align="center"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">线性QR</font></font></strong></td>
<td align="center"><a href="https://github.com/ai-winter/ros_motion_planning/blob/master/src/core/local_planner/lqr_planner/src/lqr_planner.cpp"><img src="https://camo.githubusercontent.com/76b0b0f688f0d73b64ff1fe06b05fe37112c5a7952efd07c914f1bd07aa28882/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f646f6e652d76312e312d627269676874677265656e" alt="地位" data-canonical-src="https://img.shields.io/badge/done-v1.1-brightgreen" style="max-width: 100%;"></a></td>
<td align="center"><animated-image data-catalyst=""><a target="_blank" rel="noopener noreferrer" href="/ai-winter/ros_motion_planning/blob/master/assets/lqr_ros.gif" data-target="animated-image.originalLink"><img src="/ai-winter/ros_motion_planning/raw/master/assets/lqr_ros.gif" alt="lqr_ros.gif" style="max-width: 100%; display: inline-block;" data-target="animated-image.originalImage"></a>
      <span class="AnimatedImagePlayer" data-target="animated-image.player" hidden="">
        <a data-target="animated-image.replacedLink" class="AnimatedImagePlayer-images" href="https://github.com/ai-winter/ros_motion_planning/blob/master/assets/lqr_ros.gif" target="_blank">
          
        <span data-target="animated-image.imageContainer">
            <img data-target="animated-image.replacedImage" alt="lqr_ros.gif" class="AnimatedImagePlayer-animatedImage" src="https://github.com/ai-winter/ros_motion_planning/raw/master/assets/lqr_ros.gif" style="display: block; opacity: 1;">
          <canvas class="AnimatedImagePlayer-stillImage" aria-hidden="true" width="395" height="384"></canvas></span></a>
        <button data-target="animated-image.imageButton" class="AnimatedImagePlayer-images" tabindex="-1" aria-label="Play lqr_ros.gif" hidden=""></button>
        <span class="AnimatedImagePlayer-controls" data-target="animated-image.controls" hidden="">
          <button data-target="animated-image.playButton" class="AnimatedImagePlayer-button" aria-label="Play lqr_ros.gif">
            <svg aria-hidden="true" focusable="false" class="octicon icon-play" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M4 13.5427V2.45734C4 1.82607 4.69692 1.4435 5.2295 1.78241L13.9394 7.32507C14.4334 7.63943 14.4334 8.36057 13.9394 8.67493L5.2295 14.2176C4.69692 14.5565 4 14.1739 4 13.5427Z">
            </path></svg>
            <svg aria-hidden="true" focusable="false" class="octicon icon-pause" width="16" height="16" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg">
              <rect x="4" y="2" width="3" height="12" rx="1"></rect>
              <rect x="9" y="2" width="3" height="12" rx="1"></rect>
            </svg>
          </button>
          <a data-target="animated-image.openButton" aria-label="Open lqr_ros.gif in new window" class="AnimatedImagePlayer-button" href="https://github.com/ai-winter/ros_motion_planning/blob/master/assets/lqr_ros.gif" target="_blank">
            <svg aria-hidden="true" class="octicon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
              <path fill-rule="evenodd" d="M10.604 1h4.146a.25.25 0 01.25.25v4.146a.25.25 0 01-.427.177L13.03 4.03 9.28 7.78a.75.75 0 01-1.06-1.06l3.75-3.75-1.543-1.543A.25.25 0 0110.604 1zM3.75 2A1.75 1.75 0 002 3.75v8.5c0 .966.784 1.75 1.75 1.75h8.5A1.75 1.75 0 0014 12.25v-3.5a.75.75 0 00-1.5 0v3.5a.25.25 0 01-.25.25h-8.5a.25.25 0 01-.25-.25v-8.5a.25.25 0 01.25-.25h3.5a.75.75 0 000-1.5h-3.5z"></path>
            </svg>
          </a>
        </span>
      </span></animated-image></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">-</font></font></td>
</tr>
<tr>
<td align="center"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">数字水务局</font></font></strong></td>
<td align="center"><a href="https://github.com/ai-winter/ros_motion_planning/blob/master/src/core/local_planner/dwa_planner/src/dwa.cpp"><img src="https://camo.githubusercontent.com/e312b1e6ef783ffbf72cf17901860d5a912e2c1e2e756a1d51236fe0c39c654f/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f646f6e652d76312e302d627269676874677265656e" alt="地位" data-canonical-src="https://img.shields.io/badge/done-v1.0-brightgreen" style="max-width: 100%;"></a></td>
<td align="center"><animated-image data-catalyst=""><a target="_blank" rel="noopener noreferrer" href="/ai-winter/ros_motion_planning/blob/master/assets/dwa_ros.gif" data-target="animated-image.originalLink"><img src="/ai-winter/ros_motion_planning/raw/master/assets/dwa_ros.gif" alt="dwa_ros.gif" style="max-width: 100%; display: inline-block;" data-target="animated-image.originalImage"></a>
      <span class="AnimatedImagePlayer" data-target="animated-image.player" hidden="">
        <a data-target="animated-image.replacedLink" class="AnimatedImagePlayer-images" href="https://github.com/ai-winter/ros_motion_planning/blob/master/assets/dwa_ros.gif" target="_blank">
          
        <span data-target="animated-image.imageContainer">
            <img data-target="animated-image.replacedImage" alt="dwa_ros.gif" class="AnimatedImagePlayer-animatedImage" src="https://github.com/ai-winter/ros_motion_planning/raw/master/assets/dwa_ros.gif" style="display: block; opacity: 1;">
          <canvas class="AnimatedImagePlayer-stillImage" aria-hidden="true" width="393" height="295"></canvas></span></a>
        <button data-target="animated-image.imageButton" class="AnimatedImagePlayer-images" tabindex="-1" aria-label="Play dwa_ros.gif" hidden=""></button>
        <span class="AnimatedImagePlayer-controls" data-target="animated-image.controls" hidden="">
          <button data-target="animated-image.playButton" class="AnimatedImagePlayer-button" aria-label="Play dwa_ros.gif">
            <svg aria-hidden="true" focusable="false" class="octicon icon-play" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M4 13.5427V2.45734C4 1.82607 4.69692 1.4435 5.2295 1.78241L13.9394 7.32507C14.4334 7.63943 14.4334 8.36057 13.9394 8.67493L5.2295 14.2176C4.69692 14.5565 4 14.1739 4 13.5427Z">
            </path></svg>
            <svg aria-hidden="true" focusable="false" class="octicon icon-pause" width="16" height="16" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg">
              <rect x="4" y="2" width="3" height="12" rx="1"></rect>
              <rect x="9" y="2" width="3" height="12" rx="1"></rect>
            </svg>
          </button>
          <a data-target="animated-image.openButton" aria-label="Open dwa_ros.gif in new window" class="AnimatedImagePlayer-button" href="https://github.com/ai-winter/ros_motion_planning/blob/master/assets/dwa_ros.gif" target="_blank">
            <svg aria-hidden="true" class="octicon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
              <path fill-rule="evenodd" d="M10.604 1h4.146a.25.25 0 01.25.25v4.146a.25.25 0 01-.427.177L13.03 4.03 9.28 7.78a.75.75 0 01-1.06-1.06l3.75-3.75-1.543-1.543A.25.25 0 0110.604 1zM3.75 2A1.75 1.75 0 002 3.75v8.5c0 .966.784 1.75 1.75 1.75h8.5A1.75 1.75 0 0014 12.25v-3.5a.75.75 0 00-1.5 0v3.5a.25.25 0 01-.25.25h-8.5a.25.25 0 01-.25-.25v-8.5a.25.25 0 01.25-.25h3.5a.75.75 0 000-1.5h-3.5z"></path>
            </svg>
          </a>
        </span>
      </span></animated-image></td>
<td align="center"><a href="https://www.ri.cmu.edu/pub_files/pub1/fox_dieter_1997_1/fox_dieter_1997_1.pdf" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">避免碰撞的动态窗口方法</font></font></a></td>
</tr>
<tr>
<td align="center"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有源滤波器</font></font></strong></td>
<td align="center"><a href="https://github.com/ai-winter/ros_motion_planning/blob/master/src/core/local_planner/apf_planner/src/apf_planner.cpp"><img src="https://camo.githubusercontent.com/e312b1e6ef783ffbf72cf17901860d5a912e2c1e2e756a1d51236fe0c39c654f/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f646f6e652d76312e302d627269676874677265656e" alt="地位" data-canonical-src="https://img.shields.io/badge/done-v1.0-brightgreen" style="max-width: 100%;"></a></td>
<td align="center"><animated-image data-catalyst=""><a target="_blank" rel="noopener noreferrer" href="/ai-winter/ros_motion_planning/blob/master/assets/apf_ros.gif" data-target="animated-image.originalLink"><img src="/ai-winter/ros_motion_planning/raw/master/assets/apf_ros.gif" alt="apf_ros.gif" style="max-width: 100%; display: inline-block;" data-target="animated-image.originalImage"></a>
      <span class="AnimatedImagePlayer" data-target="animated-image.player" hidden="">
        <a data-target="animated-image.replacedLink" class="AnimatedImagePlayer-images" href="https://github.com/ai-winter/ros_motion_planning/blob/master/assets/apf_ros.gif" target="_blank">
          
        <span data-target="animated-image.imageContainer">
            <img data-target="animated-image.replacedImage" alt="apf_ros.gif" class="AnimatedImagePlayer-animatedImage" src="https://github.com/ai-winter/ros_motion_planning/raw/master/assets/apf_ros.gif" style="display: block; opacity: 1;">
          <canvas class="AnimatedImagePlayer-stillImage" aria-hidden="true" width="402" height="396"></canvas></span></a>
        <button data-target="animated-image.imageButton" class="AnimatedImagePlayer-images" tabindex="-1" aria-label="Play apf_ros.gif" hidden=""></button>
        <span class="AnimatedImagePlayer-controls" data-target="animated-image.controls" hidden="">
          <button data-target="animated-image.playButton" class="AnimatedImagePlayer-button" aria-label="Play apf_ros.gif">
            <svg aria-hidden="true" focusable="false" class="octicon icon-play" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M4 13.5427V2.45734C4 1.82607 4.69692 1.4435 5.2295 1.78241L13.9394 7.32507C14.4334 7.63943 14.4334 8.36057 13.9394 8.67493L5.2295 14.2176C4.69692 14.5565 4 14.1739 4 13.5427Z">
            </path></svg>
            <svg aria-hidden="true" focusable="false" class="octicon icon-pause" width="16" height="16" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg">
              <rect x="4" y="2" width="3" height="12" rx="1"></rect>
              <rect x="9" y="2" width="3" height="12" rx="1"></rect>
            </svg>
          </button>
          <a data-target="animated-image.openButton" aria-label="Open apf_ros.gif in new window" class="AnimatedImagePlayer-button" href="https://github.com/ai-winter/ros_motion_planning/blob/master/assets/apf_ros.gif" target="_blank">
            <svg aria-hidden="true" class="octicon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
              <path fill-rule="evenodd" d="M10.604 1h4.146a.25.25 0 01.25.25v4.146a.25.25 0 01-.427.177L13.03 4.03 9.28 7.78a.75.75 0 01-1.06-1.06l3.75-3.75-1.543-1.543A.25.25 0 0110.604 1zM3.75 2A1.75 1.75 0 002 3.75v8.5c0 .966.784 1.75 1.75 1.75h8.5A1.75 1.75 0 0014 12.25v-3.5a.75.75 0 00-1.5 0v3.5a.25.25 0 01-.25.25h-8.5a.25.25 0 01-.25-.25v-8.5a.25.25 0 01.25-.25h3.5a.75.75 0 000-1.5h-3.5z"></path>
            </svg>
          </a>
        </span>
      </span></animated-image></td>
<td align="center"><a href="https://ieeexplore.ieee.org/document/1087247" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">机械手和移动机器人的实时避障</font></font></a></td>
</tr>
<tr>
<td align="center"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">RPP</font></font></strong></td>
<td align="center"><a href="https://github.com/ai-winter/ros_motion_planning/blob/master/src/core/local_planner/rpp_planner/src/rpp_planner.cpp"><img src="https://camo.githubusercontent.com/e312b1e6ef783ffbf72cf17901860d5a912e2c1e2e756a1d51236fe0c39c654f/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f646f6e652d76312e302d627269676874677265656e" alt="地位" data-canonical-src="https://img.shields.io/badge/done-v1.0-brightgreen" style="max-width: 100%;"></a></td>
<td align="center"><animated-image data-catalyst=""><a target="_blank" rel="noopener noreferrer" href="/ai-winter/ros_motion_planning/blob/master/assets/rpp_ros.gif" data-target="animated-image.originalLink"><img src="/ai-winter/ros_motion_planning/raw/master/assets/rpp_ros.gif" alt="rpp_ros.gif" style="max-width: 100%; display: inline-block;" data-target="animated-image.originalImage"></a>
      <span class="AnimatedImagePlayer" data-target="animated-image.player" hidden="">
        <a data-target="animated-image.replacedLink" class="AnimatedImagePlayer-images" href="https://github.com/ai-winter/ros_motion_planning/blob/master/assets/rpp_ros.gif" target="_blank">
          
        <span data-target="animated-image.imageContainer">
            <img data-target="animated-image.replacedImage" alt="rpp_ros.gif" class="AnimatedImagePlayer-animatedImage" src="https://github.com/ai-winter/ros_motion_planning/raw/master/assets/rpp_ros.gif" style="display: block; opacity: 1;">
          <canvas class="AnimatedImagePlayer-stillImage" aria-hidden="true" width="402" height="399"></canvas></span></a>
        <button data-target="animated-image.imageButton" class="AnimatedImagePlayer-images" tabindex="-1" aria-label="Play rpp_ros.gif" hidden=""></button>
        <span class="AnimatedImagePlayer-controls" data-target="animated-image.controls" hidden="">
          <button data-target="animated-image.playButton" class="AnimatedImagePlayer-button" aria-label="Play rpp_ros.gif">
            <svg aria-hidden="true" focusable="false" class="octicon icon-play" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M4 13.5427V2.45734C4 1.82607 4.69692 1.4435 5.2295 1.78241L13.9394 7.32507C14.4334 7.63943 14.4334 8.36057 13.9394 8.67493L5.2295 14.2176C4.69692 14.5565 4 14.1739 4 13.5427Z">
            </path></svg>
            <svg aria-hidden="true" focusable="false" class="octicon icon-pause" width="16" height="16" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg">
              <rect x="4" y="2" width="3" height="12" rx="1"></rect>
              <rect x="9" y="2" width="3" height="12" rx="1"></rect>
            </svg>
          </button>
          <a data-target="animated-image.openButton" aria-label="Open rpp_ros.gif in new window" class="AnimatedImagePlayer-button" href="https://github.com/ai-winter/ros_motion_planning/blob/master/assets/rpp_ros.gif" target="_blank">
            <svg aria-hidden="true" class="octicon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
              <path fill-rule="evenodd" d="M10.604 1h4.146a.25.25 0 01.25.25v4.146a.25.25 0 01-.427.177L13.03 4.03 9.28 7.78a.75.75 0 01-1.06-1.06l3.75-3.75-1.543-1.543A.25.25 0 0110.604 1zM3.75 2A1.75 1.75 0 002 3.75v8.5c0 .966.784 1.75 1.75 1.75h8.5A1.75 1.75 0 0014 12.25v-3.5a.75.75 0 00-1.5 0v3.5a.25.25 0 01-.25.25h-8.5a.25.25 0 01-.25-.25v-8.5a.25.25 0 01.25-.25h3.5a.75.75 0 000-1.5h-3.5z"></path>
            </svg>
          </a>
        </span>
      </span></animated-image></td>
<td align="center"><a href="https://arxiv.org/pdf/2305.20026.pdf" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">机器人路径跟踪的受监管纯粹追踪</font></font></a></td>
</tr>
<tr>
<td align="center"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TEB</font></font></strong></td>
<td align="center"><a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/20940c44dc0b6fc06cb3ff0bbcfdd38ea12f9d155ef1dc026fa7bedea03d813a/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f646576656c6f702d76312e302d726564"><img src="https://camo.githubusercontent.com/20940c44dc0b6fc06cb3ff0bbcfdd38ea12f9d155ef1dc026fa7bedea03d813a/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f646576656c6f702d76312e302d726564" alt="地位" data-canonical-src="https://img.shields.io/badge/develop-v1.0-red" style="max-width: 100%;"></a></td>
<td align="center"><a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/8cfd3922400b98f3a3ed11fab448c168f81d0973c569ed0301b02788eb8e1a77/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f6769662d6e6f6e652d79656c6c6f77"><img src="https://camo.githubusercontent.com/8cfd3922400b98f3a3ed11fab448c168f81d0973c569ed0301b02788eb8e1a77/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f6769662d6e6f6e652d79656c6c6f77" alt="地位" data-canonical-src="https://img.shields.io/badge/gif-none-yellow" style="max-width: 100%;"></a></td>
<td align="center"></td>
</tr>
<tr>
<td align="center"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">多点控制</font></font></strong></td>
<td align="center"><a href="https://github.com/ai-winter/ros_motion_planning/blob/master/src/core/local_planner/mpc_planner/src/mpc_planner.cpp"><img src="https://camo.githubusercontent.com/e312b1e6ef783ffbf72cf17901860d5a912e2c1e2e756a1d51236fe0c39c654f/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f646f6e652d76312e302d627269676874677265656e" alt="地位" data-canonical-src="https://img.shields.io/badge/done-v1.0-brightgreen" style="max-width: 100%;"></a></td>
<td align="center"><animated-image data-catalyst=""><a target="_blank" rel="noopener noreferrer" href="/ai-winter/ros_motion_planning/blob/master/assets/mpc_ros.gif" data-target="animated-image.originalLink"><img src="/ai-winter/ros_motion_planning/raw/master/assets/mpc_ros.gif" alt="mpc_ros.gif" style="max-width: 100%; display: inline-block;" data-target="animated-image.originalImage"></a>
      <span class="AnimatedImagePlayer" data-target="animated-image.player" hidden="">
        <a data-target="animated-image.replacedLink" class="AnimatedImagePlayer-images" href="https://github.com/ai-winter/ros_motion_planning/blob/master/assets/mpc_ros.gif" target="_blank">
          
        <span data-target="animated-image.imageContainer">
            <img data-target="animated-image.replacedImage" alt="mpc_ros.gif" class="AnimatedImagePlayer-animatedImage" src="https://github.com/ai-winter/ros_motion_planning/raw/master/assets/mpc_ros.gif" style="display: block; opacity: 1;">
          <canvas class="AnimatedImagePlayer-stillImage" aria-hidden="true" width="518" height="503"></canvas></span></a>
        <button data-target="animated-image.imageButton" class="AnimatedImagePlayer-images" tabindex="-1" aria-label="Play mpc_ros.gif" hidden=""></button>
        <span class="AnimatedImagePlayer-controls" data-target="animated-image.controls" hidden="">
          <button data-target="animated-image.playButton" class="AnimatedImagePlayer-button" aria-label="Play mpc_ros.gif">
            <svg aria-hidden="true" focusable="false" class="octicon icon-play" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M4 13.5427V2.45734C4 1.82607 4.69692 1.4435 5.2295 1.78241L13.9394 7.32507C14.4334 7.63943 14.4334 8.36057 13.9394 8.67493L5.2295 14.2176C4.69692 14.5565 4 14.1739 4 13.5427Z">
            </path></svg>
            <svg aria-hidden="true" focusable="false" class="octicon icon-pause" width="16" height="16" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg">
              <rect x="4" y="2" width="3" height="12" rx="1"></rect>
              <rect x="9" y="2" width="3" height="12" rx="1"></rect>
            </svg>
          </button>
          <a data-target="animated-image.openButton" aria-label="Open mpc_ros.gif in new window" class="AnimatedImagePlayer-button" href="https://github.com/ai-winter/ros_motion_planning/blob/master/assets/mpc_ros.gif" target="_blank">
            <svg aria-hidden="true" class="octicon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
              <path fill-rule="evenodd" d="M10.604 1h4.146a.25.25 0 01.25.25v4.146a.25.25 0 01-.427.177L13.03 4.03 9.28 7.78a.75.75 0 01-1.06-1.06l3.75-3.75-1.543-1.543A.25.25 0 0110.604 1zM3.75 2A1.75 1.75 0 002 3.75v8.5c0 .966.784 1.75 1.75 1.75h8.5A1.75 1.75 0 0014 12.25v-3.5a.75.75 0 00-1.5 0v3.5a.25.25 0 01-.25.25h-8.5a.25.25 0 01-.25-.25v-8.5a.25.25 0 01.25-.25h3.5a.75.75 0 000-1.5h-3.5z"></path>
            </svg>
          </a>
        </span>
      </span></animated-image></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">-</font></font></td>
</tr>
<tr>
<td align="center"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">格子</font></font></strong></td>
<td align="center"><a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/20940c44dc0b6fc06cb3ff0bbcfdd38ea12f9d155ef1dc026fa7bedea03d813a/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f646576656c6f702d76312e302d726564"><img src="https://camo.githubusercontent.com/20940c44dc0b6fc06cb3ff0bbcfdd38ea12f9d155ef1dc026fa7bedea03d813a/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f646576656c6f702d76312e302d726564" alt="地位" data-canonical-src="https://img.shields.io/badge/develop-v1.0-red" style="max-width: 100%;"></a></td>
<td align="center"><a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/8cfd3922400b98f3a3ed11fab448c168f81d0973c569ed0301b02788eb8e1a77/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f6769662d6e6f6e652d79656c6c6f77"><img src="https://camo.githubusercontent.com/8cfd3922400b98f3a3ed11fab448c168f81d0973c569ed0301b02788eb8e1a77/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f6769662d6e6f6e652d79656c6c6f77" alt="地位" data-canonical-src="https://img.shields.io/badge/gif-none-yellow" style="max-width: 100%;"></a></td>
<td align="center"></td>
</tr>
</tbody>
</table>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">曲线生成</font></font></h3><a id="user-content-curve-generation" class="anchor" aria-label="永久链接：曲线生成" href="#curve-generation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<table>
<thead>
<tr>
<th align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">规划师</font></font></th>
<th align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">版本</font></font></th>
<th align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">动画片</font></font></th>
<th align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">纸</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td align="center"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">多项式</font></font></strong></td>
<td align="center"><a href="https://github.com/ai-winter/ros_motion_planning/blob/master/src/core/curve_generation/src/polynomial_curve.cpp"><img src="https://camo.githubusercontent.com/e312b1e6ef783ffbf72cf17901860d5a912e2c1e2e756a1d51236fe0c39c654f/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f646f6e652d76312e302d627269676874677265656e" alt="地位" data-canonical-src="https://img.shields.io/badge/done-v1.0-brightgreen" style="max-width: 100%;"></a></td>
<td align="center"><animated-image data-catalyst=""><a target="_blank" rel="noopener noreferrer" href="/ai-winter/ros_motion_planning/blob/master/assets/polynomial_curve_python.gif" data-target="animated-image.originalLink"><img src="/ai-winter/ros_motion_planning/raw/master/assets/polynomial_curve_python.gif" alt="多项式_curve_python.gif" style="max-width: 100%; display: inline-block;" data-target="animated-image.originalImage"></a>
      <span class="AnimatedImagePlayer" data-target="animated-image.player" hidden="">
        <a data-target="animated-image.replacedLink" class="AnimatedImagePlayer-images" href="https://github.com/ai-winter/ros_motion_planning/blob/master/assets/polynomial_curve_python.gif" target="_blank">
          
        <span data-target="animated-image.imageContainer">
            <img data-target="animated-image.replacedImage" alt="多项式_curve_python.gif" class="AnimatedImagePlayer-animatedImage" src="https://github.com/ai-winter/ros_motion_planning/raw/master/assets/polynomial_curve_python.gif" style="display: block; opacity: 1;">
          <canvas class="AnimatedImagePlayer-stillImage" aria-hidden="true" width="359" height="267"></canvas></span></a>
        <button data-target="animated-image.imageButton" class="AnimatedImagePlayer-images" tabindex="-1" aria-label="Play 多项式_curve_python.gif" hidden=""></button>
        <span class="AnimatedImagePlayer-controls" data-target="animated-image.controls" hidden="">
          <button data-target="animated-image.playButton" class="AnimatedImagePlayer-button" aria-label="Play 多项式_curve_python.gif">
            <svg aria-hidden="true" focusable="false" class="octicon icon-play" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M4 13.5427V2.45734C4 1.82607 4.69692 1.4435 5.2295 1.78241L13.9394 7.32507C14.4334 7.63943 14.4334 8.36057 13.9394 8.67493L5.2295 14.2176C4.69692 14.5565 4 14.1739 4 13.5427Z">
            </path></svg>
            <svg aria-hidden="true" focusable="false" class="octicon icon-pause" width="16" height="16" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg">
              <rect x="4" y="2" width="3" height="12" rx="1"></rect>
              <rect x="9" y="2" width="3" height="12" rx="1"></rect>
            </svg>
          </button>
          <a data-target="animated-image.openButton" aria-label="Open 多项式_curve_python.gif in new window" class="AnimatedImagePlayer-button" href="https://github.com/ai-winter/ros_motion_planning/blob/master/assets/polynomial_curve_python.gif" target="_blank">
            <svg aria-hidden="true" class="octicon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
              <path fill-rule="evenodd" d="M10.604 1h4.146a.25.25 0 01.25.25v4.146a.25.25 0 01-.427.177L13.03 4.03 9.28 7.78a.75.75 0 01-1.06-1.06l3.75-3.75-1.543-1.543A.25.25 0 0110.604 1zM3.75 2A1.75 1.75 0 002 3.75v8.5c0 .966.784 1.75 1.75 1.75h8.5A1.75 1.75 0 0014 12.25v-3.5a.75.75 0 00-1.5 0v3.5a.25.25 0 01-.25.25h-8.5a.25.25 0 01-.25-.25v-8.5a.25.25 0 01.25-.25h3.5a.75.75 0 000-1.5h-3.5z"></path>
            </svg>
          </a>
        </span>
      </span></animated-image></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">-</font></font></td>
</tr>
<tr>
<td align="center"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">贝塞尔</font></font></strong></td>
<td align="center"><a href="https://github.com/ai-winter/ros_motion_planning/blob/master/src/core/curve_generation/src/bezier_curve.cpp"><img src="https://camo.githubusercontent.com/e312b1e6ef783ffbf72cf17901860d5a912e2c1e2e756a1d51236fe0c39c654f/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f646f6e652d76312e302d627269676874677265656e" alt="地位" data-canonical-src="https://img.shields.io/badge/done-v1.0-brightgreen" style="max-width: 100%;"></a></td>
<td align="center"><a target="_blank" rel="noopener noreferrer" href="/ai-winter/ros_motion_planning/blob/master/assets/bezier_curve_python.png"><img src="/ai-winter/ros_motion_planning/raw/master/assets/bezier_curve_python.png" alt="bezier_curve_python.png" style="max-width: 100%;"></a></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">-</font></font></td>
</tr>
<tr>
<td align="center"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">三次样条</font></font></strong></td>
<td align="center"><a href="https://github.com/ai-winter/ros_motion_planning/blob/master/src/core/curve_generation/src/cubic_spline.cpp"><img src="https://camo.githubusercontent.com/e312b1e6ef783ffbf72cf17901860d5a912e2c1e2e756a1d51236fe0c39c654f/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f646f6e652d76312e302d627269676874677265656e" alt="地位" data-canonical-src="https://img.shields.io/badge/done-v1.0-brightgreen" style="max-width: 100%;"></a></td>
<td align="center"><a target="_blank" rel="noopener noreferrer" href="/ai-winter/ros_motion_planning/blob/master/assets/cubic_spline_python.png"><img src="/ai-winter/ros_motion_planning/raw/master/assets/cubic_spline_python.png" alt="cubic_spline_python.png" style="max-width: 100%;"></a></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">-</font></font></td>
</tr>
<tr>
<td align="center"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">样条曲线</font></font></strong></td>
<td align="center"><a href="https://github.com/ai-winter/ros_motion_planning/blob/master/src/core/curve_generation/src/bspline_curve.cpp"><img src="https://camo.githubusercontent.com/e312b1e6ef783ffbf72cf17901860d5a912e2c1e2e756a1d51236fe0c39c654f/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f646f6e652d76312e302d627269676874677265656e" alt="地位" data-canonical-src="https://img.shields.io/badge/done-v1.0-brightgreen" style="max-width: 100%;"></a></td>
<td align="center"><a target="_blank" rel="noopener noreferrer" href="/ai-winter/ros_motion_planning/blob/master/assets/bspline_curve_python.png"><img src="/ai-winter/ros_motion_planning/raw/master/assets/bspline_curve_python.png" alt="bspline_curve_python.png" style="max-width: 100%;"></a></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">-</font></font></td>
</tr>
<tr>
<td align="center"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">杜宾斯</font></font></strong></td>
<td align="center"><a href="https://github.com/ai-winter/ros_motion_planning/blob/master/src/core/curve_generation/src/dubins_curve.cpp"><img src="https://camo.githubusercontent.com/e312b1e6ef783ffbf72cf17901860d5a912e2c1e2e756a1d51236fe0c39c654f/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f646f6e652d76312e302d627269676874677265656e" alt="地位" data-canonical-src="https://img.shields.io/badge/done-v1.0-brightgreen" style="max-width: 100%;"></a></td>
<td align="center"><a target="_blank" rel="noopener noreferrer" href="/ai-winter/ros_motion_planning/blob/master/assets/dubins_curve_python.png"><img src="/ai-winter/ros_motion_planning/raw/master/assets/dubins_curve_python.png" alt="dubins_curve_python.png" style="max-width: 100%;"></a></td>
<td align="center"><a href="/ai-winter/ros_motion_planning/blob/master"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在具有平均曲率约束且具有指定初始位置和终止位置以及切线的最小长度曲线上</font></font></a></td>
</tr>
<tr>
<td align="center"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">里兹-谢普</font></font></strong></td>
<td align="center"><a href="https://github.com/ai-winter/ros_motion_planning/blob/master/src/core/curve_generation/src/reeds_shepp.cpp"><img src="https://camo.githubusercontent.com/e312b1e6ef783ffbf72cf17901860d5a912e2c1e2e756a1d51236fe0c39c654f/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f646f6e652d76312e302d627269676874677265656e" alt="地位" data-canonical-src="https://img.shields.io/badge/done-v1.0-brightgreen" style="max-width: 100%;"></a></td>
<td align="center"><animated-image data-catalyst=""><a target="_blank" rel="noopener noreferrer" href="/ai-winter/ros_motion_planning/blob/master/assets/reeds_shepp_python.gif" data-target="animated-image.originalLink"><img src="/ai-winter/ros_motion_planning/raw/master/assets/reeds_shepp_python.gif" alt="reeds_shepp_python.png" style="max-width: 100%; display: inline-block;" data-target="animated-image.originalImage"></a>
      <span class="AnimatedImagePlayer" data-target="animated-image.player" hidden="">
        <a data-target="animated-image.replacedLink" class="AnimatedImagePlayer-images" href="https://github.com/ai-winter/ros_motion_planning/blob/master/assets/reeds_shepp_python.gif" target="_blank">
          
        <span data-target="animated-image.imageContainer">
            <img data-target="animated-image.replacedImage" alt="reeds_shepp_python.png" class="AnimatedImagePlayer-animatedImage" src="https://github.com/ai-winter/ros_motion_planning/raw/master/assets/reeds_shepp_python.gif" style="display: block; opacity: 1;">
          <canvas class="AnimatedImagePlayer-stillImage" aria-hidden="true" width="359" height="269"></canvas></span></a>
        <button data-target="animated-image.imageButton" class="AnimatedImagePlayer-images" tabindex="-1" aria-label="Play reeds_shepp_python.png" hidden=""></button>
        <span class="AnimatedImagePlayer-controls" data-target="animated-image.controls" hidden="">
          <button data-target="animated-image.playButton" class="AnimatedImagePlayer-button" aria-label="Play reeds_shepp_python.png">
            <svg aria-hidden="true" focusable="false" class="octicon icon-play" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M4 13.5427V2.45734C4 1.82607 4.69692 1.4435 5.2295 1.78241L13.9394 7.32507C14.4334 7.63943 14.4334 8.36057 13.9394 8.67493L5.2295 14.2176C4.69692 14.5565 4 14.1739 4 13.5427Z">
            </path></svg>
            <svg aria-hidden="true" focusable="false" class="octicon icon-pause" width="16" height="16" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg">
              <rect x="4" y="2" width="3" height="12" rx="1"></rect>
              <rect x="9" y="2" width="3" height="12" rx="1"></rect>
            </svg>
          </button>
          <a data-target="animated-image.openButton" aria-label="Open reeds_shepp_python.png in new window" class="AnimatedImagePlayer-button" href="https://github.com/ai-winter/ros_motion_planning/blob/master/assets/reeds_shepp_python.gif" target="_blank">
            <svg aria-hidden="true" class="octicon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
              <path fill-rule="evenodd" d="M10.604 1h4.146a.25.25 0 01.25.25v4.146a.25.25 0 01-.427.177L13.03 4.03 9.28 7.78a.75.75 0 01-1.06-1.06l3.75-3.75-1.543-1.543A.25.25 0 0110.604 1zM3.75 2A1.75 1.75 0 002 3.75v8.5c0 .966.784 1.75 1.75 1.75h8.5A1.75 1.75 0 0014 12.25v-3.5a.75.75 0 00-1.5 0v3.5a.25.25 0 01-.25.25h-8.5a.25.25 0 01-.25-.25v-8.5a.25.25 0 01.25-.25h3.5a.75.75 0 000-1.5h-3.5z"></path>
            </svg>
          </a>
        </span>
      </span></animated-image></td>
<td align="center"><a href="https://projecteuclid.org/journals/pacific-journal-of-mathematics/volume-145/issue-2/Optimal-paths-for-a-car-that-goes-both-forwards-and/pjm/1102645450.full" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">汽车前进和后退的最佳路径</font></font></a></td>
</tr>
</tbody>
</table>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><span id="user-content-4"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">04.致谢</font></font></span></h2><a id="user-content-04-acknowledgments" class="anchor" aria-label="永久链接：04.致谢" href="#04-acknowledgments"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们的机器人和世界模型来自</font></font><a href="https://github.com/mlherd/Dataset-of-Gazebo-Worlds-Models-and-Maps"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
Dataset-of-Gazebo-Worlds-Models-and-Maps</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><a href="https://github.com/aws-robotics/aws-robomaker-small-warehouse-world"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
aws-robomaker-small-warehouse-world</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font><font style="vertical-align: inherit;">衷心感谢这些开源模型。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这种环境下的行人使用的是社会力模型（sfm），该模型来自</font></font><a href="https://github.com/robotics-upo/lightsfm"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://github.com/robotics-upo/lightsfm</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Boris Lau 提出的用于</font></font><a href="http://www2.informatik.uni-freiburg.de/~lau/dynamicvoronoi/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">dynamicvoronoi</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">的ROS costmap 插件。</font></font></p>
</li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><span id="user-content-5"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">05. 许可证</font></font></span></h2><a id="user-content-05-license" class="anchor" aria-label="永久链接：05. 许可证" href="#05-license"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="https://www.gnu.org/licenses/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">源代码根据GPLv3</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">许可证发布</font><font style="vertical-align: inherit;">。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><span id="user-content-6"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">06. 维护保养</font></font></span></h2><a id="user-content-06-maintenance" class="anchor" aria-label="永久链接：06.维护" href="#06-maintenance"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您有任何疑问，请随时与我们联系。</font></font></p>
</article></div>
