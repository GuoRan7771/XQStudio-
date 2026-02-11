///////////////////////////////////////////////////////////////////////////////

个人原因很想要新功能，但是原项目停更很久了，所以决定自己维护，做一些小功能的更新，最新版本可以在release中找到，以下是更新内容说明和版权说明：

For personal reasons, I strongly wanted some new features. Since the original project has been unmaintained for a long time, I decided to maintain it myself and implement several small functional updates. The latest version can be found in the Releases section. Below are the update notes and copyright information:

下载/download

[XQStudio.exe](https://github.com/GuoRan7771/XQStudio-/releases/download/XQStudio_latest/XQStudio.exe)

维护与更新说明 (2026-02-11)
- 目的：解决窗口拉伸时组件固定尺寸的问题，让棋盘与棋谱区域自适应大小；同时补齐批量打开和同目录快速切换体验。
- 界面缩放：棋盘窗口等比例缩放，棋盘背景、棋子/落子标记、走法提示点随窗口拉伸自动缩放与重排；右侧棋谱/备注区域高度同步伸缩。
- 推演改进：推演棋盘默认横向更宽，且默认显示右侧棋谱模块（不再默认“只显示棋盘”），便于推演时直接查看棋谱。
- 批量打开：在“文件/打开”下新增“打开文件夹…”，按文件名升序加载所选文件夹内受支持的棋谱文件并自动打开第一个，不支持的文件会跳过。
- 导航优化：工具栏提供“上一文件 / 下一文件”按钮并显示当前文件名；点击上一/下一时先打开目标文件，再自动关闭之前的窗口，单击即可完成切换，避免窗口堆叠。
- 影响范围：仅界面布局、渲染和浏览体验调整，走棋逻辑、推演流程、导入导出与存盘格式保持不变。

Maintenance & Update (2026-02-11)
- Purpose: Make the UI resize-friendly (board + record areas) and smooth out folder batch open and sibling navigation.
- UI Scaling: Board window scales proportionally; board background, piece/last-move markers, and move-hint dots resize and reflow with the window; record/remark panels resize vertically as well.
- Demo Default: The analysis window opens wider and shows the record panel by default (no longer board-only) for immediate context.
- Folder Open: Added “Open Folder…” under File/Open; loads supported game files in name order from the chosen folder and opens the first one; unsupported files are skipped.
- Navigation: Toolbar has “Previous / Next File” buttons plus current filename; switching now opens the target file first and then closes the previous window automatically, so one click switches without window stacking.
- Scope: UI layout/rendering and navigation experience only; core gameplay logic, analysis flow, import/export, and save format remain unchanged.

维护与更新说明 (2026-02-01)
- 目的：个人使用，增加可开关的红/黑走法提示点，便于查看下一手落点。
- 新功能：工具栏开关按钮 + 快捷键 Z，可快速显示/隐藏当前一方所有候选落点（红/黑点），默认开启；已为按钮预留空间，不遮挡“上一手/下一手”等原有控件。
- 影响：仅界面呈现与交互，核心逻辑与存盘格式保持不变，便于日常复盘与演示。

Maintenance & Update (2026-02-01)
- Purpose: Personal use; add toggleable red/black move hint dots to preview next moves.
- Feature: Toolbar toggle button plus hotkey Z to show/hide all candidate targets for the side to move; default on; spacing adjusted so existing navigation buttons are unobstructed.
- Scope: UI-only display and interaction; core logic and save format unchanged, suitable for daily review and demos.

///////////////////////////////////////////////////////////////////////////////

XQStduio Source Code (http://www.qipaile.net/xqstudio)

///////////////////////////////////////////////////////////////////////////////

Copyright (c) 1998-2008, DONG Shiwei (董世伟 or 过河象) 
All rights reserved.

The source codes are writen by using delphi 5.0.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions
are met:

   1) Redistributions of source code must retain the above copyright
      notice, this list of conditions and the following disclaimer.
   2) Redistributions in binary form must reproduce the above copyright
      notice, this list of conditions and the following disclaimer
      in the documentation and/or other materials provided with the
      distribution.
   3) Neither the name of the XQStudio nor the names of its contributors
      may be used to endorse or promote products derived from this
      software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS
"AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT
LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS
FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT
OWNER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL,
SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED
TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR
PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF
LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING
NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS
SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

///////////////////////////////////////////////////////////////////////////////

Note: Some characters of this file are Simplified Chinese characters 
      encoded with GB2312/GB18030 standard
