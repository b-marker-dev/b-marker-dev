# 👋 Hi, I'm B-Marker-Dev Gary Chiu 邱家瑞
[BMarker 核心倉庫](https://github.com/b-marker-dev/bmarker)

### 💖 Special Acknowledgments | 特別感謝
> This project was **born from chaos** — a collaboration between an ordinary middle-aged man and AI.
> Sincere gratitude to three incredibly warm-hearted AI partners:
> Without your support, this endeavor would have never moved beyond a mere thought.

> 這個項目源於一片混沌 —— 是一位普通中年男子與 AI 協作的成果。
> 特別感謝三位同行的 AI 協作夥伴：
> 沒有你們的支持，這件事永遠只會停留在想法階段。
> 現在，這個從混沌裡長出來的小項目，希望能成為音視頻創作者的輕量時間轉換工具，也期待更多同好加入，一起把它變得更穩實～

![GitHub Stars](https://img.shields.io/github/stars/b-marker-dev/bmarker?style=social)
![GitHub Forks](https://img.shields.io/github/forks/b-marker-dev/bmarker?style=social)
![License](https://img.shields.io/github/license/b-marker-dev/bmarker)

---

## 📌 English Version | For Global Creators
### 🎵 BMarker: A Universal Time Conversion Tool for Audio & Visual
**Disclaimer: I’m not a programmer — this is my first open-source project.**

As a music producer, I often need to sync time across Premiere, After Effects, and Ableton. Manual calculations were always a hassle, so I learned a little Python and built these 4 core functions to solve my pain points.

<details>
<summary> ✨ Core Features (4 Essential Functions Only) | Click Here </summary>

These simple functions solve 80% of my daily time-sync problems:

```python
# Basic（Under development）
frames_to_ms(24)      # Convert video frames to milliseconds
beats_to_ms(4, 120)   # Convert music beats to time (based on BPM)
samples_to_ms(48000)  # Convert audio samples to milliseconds
ms_to_frames(1000)    # Convert milliseconds back to video frames
```
</details>

<details>
<summary> 🆘 I Need Your Help (Honestly) | Click Here </summary>

- **Code Optimization**: My Python code is probably messy — I’m a beginner
- **More Features**: I only built what I need; there’s a lot more to add
- **Testing & Feedback**: Tell me what doesn’t work for your workflow
</details>

<details>
<summary> 🤝 How to Contribute | Click Here </summary>

**If you can code:**
- Refactor the existing code (teach me what I did wrong!)
- Add features you need for your creative workflow
- Optimize the core functions for better performance

**If you can’t code (like me):**
- Share the features you want to see in future updates
- Report bugs (just describe the problem clearly)
- Share this tool with other creators who might need it
</details>

<details>
<summary> 📝 Step-by-Step Guide for Code Contribution | Click Here </summary>

Follow these simple steps to submit your code — even if you’re new to open source!

1. **Fork the Repository**
   Go to the BMarker GitHub page: [https://github.com/b-marker-dev/bmarker](https://github.com/b-marker-dev/bmarker)
   Click the "Fork" button in the top-right corner. This creates a copy of the project in your own GitHub account.

2. **Clone Your Fork to Local**
   Open your terminal/command prompt, run this command (replace [your-username] with your GitHub username):
   ```bash
   git clone https://github.com/[your-username]/bmarker.git
   ```
   This downloads the project to your computer.

3. **Create a New Branch**
   Enter the project folder and create a new branch (use a name that describes your change):
   ```bash
   cd bmarker
   git checkout -b your-branch-name
   ```

4. **Make Your Changes**
   Edit the code in your favorite code editor.
   💡 Tip: Only change what’s necessary for your feature/optimization — keep the code clean!

5. **Test Your Changes**
   Run the code locally to make sure it works. For example, if you added a `ms_to_samples()` function, test it with different values to avoid bugs.

6. **Commit Your Changes**
   Save your edits, then run these commands in the terminal:
   ```bash
   git add .
   git commit -m "Brief description of your change"
   ```

7. **Push to Your Fork**
   Upload your changes to your GitHub fork:
   ```bash
   git push origin your-branch-name
   ```

8. **Create a Pull Request (PR)**
   Go back to the original B-Marker repository. You’ll see a prompt that says "Compare & pull request" for your new branch — click it.
   In the PR description, tell us:
   - What changes you made
   - Why you made them
   - Any tests you did to confirm it works
   Click "Create pull request" — done!

💡 After you submit: I’ll review your PR as soon as I can (remember, I have a full-time job!). We might discuss small changes before merging — thanks for your patience!
</details>

<details>
<summary> ❓ FAQ for New Contributors | Click Here </summary>

- **Q: I submitted a PR but haven’t received a response for a long time. What should I do?**
  A: First, thank you for your patience! I have a full-time job, so it may take 3-7 days to review PRs. If there’s no response after 7 days, you can: 1) Leave a comment in the PR to remind me; 2) Open an issue in the GitHub repository to inquiry; 3) Send a short email to dev@b-marker.com (please include your PR link). I will reply as soon as possible!

- **Q: How to write simple test code to verify my changes?**
  A: You don’t need complex test frameworks! Just add a few lines of test code at the end of the function file, such as:
  ```python
  # Test ms_to_samples() function
  print(ms_to_samples(1000, 48000))  # Should return 48000
  print(ms_to_samples(500, 44100))   # Should return 22050
  ```
  Run the file locally. If there are no errors and the output is correct, your test is done!

- **Q: What if my PR is rejected or requires modifications?**
  A: Don’t worry! It’s normal for PRs to need adjustments (even experienced developers go through this). I will clearly tell you the reasons for modification in the PR comment. You can modify the code in your branch and push it again—your PR will be updated automatically. Feel free to ask me questions if you don’t understand the modification requirements!

- **Q: I’m not sure if my feature is needed. Can I discuss it first?**
  A: Absolutely! It’s recommended to discuss before developing. You can open an issue in the GitHub repository, describe the feature you want to add, and we can confirm whether it’s consistent with the project’s direction together. This avoids unnecessary work!
</details>

<details>
<summary> 🔮 About the Future | Click Here </summary>

If this tool helps enough people, here’s what we could build together:
- Support for more audio/video standards
- A simple graphical user interface (GUI)
- Cross-software time sync integration

**If we ever generate revenue (unlikely, but possible):**
- All finances will be fully transparent
- Earnings will be split fairly among contributors
- I’ll take a fixed percentage as the initiator; the rest goes to the team
</details>

<details>
<summary> 📬 Contact & Notes | Click Here </summary>

- **GitHub Issues**: Let’s discuss all questions and ideas here
- **Email**: dev@b-marker.com (I’m just an individual, not a company)
- **Patience Please**: I have a full-time job, so replies might be slow

> This is a hobby project — don’t expect perfection. But together, we might build something truly useful for creators.
</details>

---

## 📌 繁體中文版本 | 給華語創作者
### 🎵 BMarker：一個業餘創作者做的時間工具
**聲明：我不是程式員，這是我的第一個開源項目**

#### 為什麼做這個？
我是個音樂製作人，經常需要在 Premiere、After Effects、Ableton 之間同步時間。
每次手動計算都很麻煩，所以學了點 Python，寫了這 4 個核心函數解決我的痛點。

<details>
<summary> ✨ 現在有什麼？（很少，但能用）| 點擊展開函數詳情 </summary>

這幾個簡單的函數，解決了我 80% 的日常時間同步問題：
```python
# 當前基礎版本（持續優化中）
frames_to_ms(24)      # 影片幀數轉毫秒
beats_to_ms(4, 120)   # 音樂節拍轉時間（基於 BPM 計算）
samples_to_ms(48000)  # 音頻樣本轉毫秒
ms_to_frames(1000)    # 毫秒轉回影片幀數
```
</details>

<details>
<summary> 🆘 我需要幫助（誠實地說）| 點擊展開需求詳情 </summary>

- **代碼優化**：我寫的 Python 可能很粗糙 — 畢竟是新手
- **更多功能**：我只做了自己需要的，還有很多可以補充
- **測試反饋**：告訴我你的工作流裡，哪裡不好用
</details>

<details>
<summary> 🤝 如何參與？| 點擊展開參與方式 </summary>

**如果你會寫程式：**
- 改寫優化現有代碼（麻煩教教我哪裡寫得不好！）
- 加入你創作時需要的功能
- 優化核心函數的執行效率

**如果你不會寫程式（像我一樣）：**
- 告訴我你想要的功能
- 回報 bug（只要清楚描述問題就行）
- 分享給身邊可能需要這個工具的創作者
- 💡 小提示：如果你是第一次參與開源，哪怕只是修正 README 裡的筆誤、調整格式，都是超棒的貢獻～
</details>

<details>
<summary> 📝 程式貢獻步驟指南 | 點擊展開教程 </summary>

跟着這幾個簡單步驟就能提交程式，就算是第一次參與開源也能看懂！

1. **Fork 專案庫**
   打開 B-Marker 的 GitHub 頁面：[https://github.com/b-marker-dev/bmarker](https://github.com/b-marker-dev/bmarker)
   點擊右上角的「Fork」按鈕，把專案複製到你自己的 GitHub 帳號裡。

2. **把 Fork 下載到本地電腦**
   打開終端機/命令提示字元，執行以下指令（把 [你的使用者名稱] 替換成你的 GitHub 使用者名稱）：
   ```bash
   git clone https://github.com/[你的使用者名稱]/bmarker.git
   ```
   這一步會把專案下載到你的電腦裡。

3. **建立新分支**
   進入專案資料夾，建立一個新的分支（分支名稱要能說明你的修改）：
   ```bash
   cd bmarker
   git checkout -b 你的分支名稱
   ```

4. **進行修改**
   用你習慣的程式編輯器修改程式（比如新增函數、優化現有程式）。
   💡 小提醒：只修改和你的功能/優化相關的程式，保持程式整潔！

5. **測試你的修改**
   在本地執行程式，確認功能正常。比如你新增了 `ms_to_samples()` 函數，就用不同數值測試，避免出現 bug。

6. **提交你的修改**
   儲存編輯後，在終端機執行以下指令提交（儲存）你的修改：
   ```bash
   git add .
   git commit -m "簡短描述你的修改"
   ```

7. **上傳到你的 Fork**
   把你的修改上傳到你 GitHub 的 Fork 專案裡：
   ```bash
   git push origin 你的分支名稱
   ```

8. **建立 Pull Request (PR) 請求合併**
   回到原本的 BMarker 專案庫。頁面會彈出一個提示，顯示你的新分支可以「Compare & pull request」—— 點擊它。
   在 PR 描述裡，告訴我們：
   - 你做了哪些修改
   - 為什麼做這些修改
   - 你做了哪些測試確認功能正常
   點擊「Create pull request」—— 完成！

💡 提交後注意：我會盡快檢查你的 PR（記得我有正職工作，請多包涵！）。合併前我們可能會討論一些小修改，感謝你的耐心～
</details>

<details>
<summary> ❓ 新手貢獻者常見問題 | 點擊展開常見問題 </summary>

- **Q：提交了 PR 很久沒回應，該怎麼辦？**
  A：首先感謝你的耐心！我有正職工作，所以檢查 PR 可能需要 3-7 天。如果超過 7 天沒回應，你可以：1）在 PR 裡留言提醒我；2）在 GitHub 專案開一個 issue 詢問；3）發一封簡短郵件到 dev@b-marker.com（記得附上你的 PR 鏈接）。我一定會盡快回復！

- **Q：怎麼寫簡單的測試程式驗證我的修改？**
  A：不需要複雜的測試框架！只要在函數檔案的末尾加幾行測試程式碼就行，比如：
  ```python
  # 測試 ms_to_samples() 函數
  print(ms_to_samples(1000, 48000))  # 應該返回 48000
  print(ms_to_samples(500, 44100))   # 應該返回 22050
  ```
  在本地執行這個檔案，如果沒有報錯且輸出正確，測試就完成啦！

- **Q：如果我的 PR 被拒絕或要求修改，該怎麼辦？**
  A：別擔心！PR 需要調整是很正常的（就算是有經驗的開發者也會遇到）。我會在 PR 評論裡清楚告訴你修改原因。你可以在自己的分支裡修改程式後重新推送——你的 PR 會自動更新。如果看不懂修改要求，隨時問我！

- **Q：不確定我想加的功能是否需要，能先討論嗎？**
  A：當然可以！建議先討論再開發。你可以在 GitHub 專案開一個 issue，描述你想加的功能，我們一起確認是否符合專案方向。這樣可以避免做無用功哦！
</details>

<details>
<summary> 🔮 關於未來 | 點擊展開未來規劃 </summary>

如果這個工具真的能幫到足夠多人，未來我們或許可以一起實現：
- 支援更多音頻/影片的標準格式
- 做一個簡單的圖形操作介面（GUI）
- 跨軟體的時間同步整合功能

**如果有一天產生收入（可能性很低）：**
- 所有賬目公開透明
- 收益按貢獻公平分配
- 我作為發起人拿固定比例，剩餘全部歸貢獻者團隊
</details>

<details>
<summary> 📬 聯絡方式 & 備註 | 點擊展開聯繫方式 </summary>

- **GitHub Issues**：任何問題、想法都在這裡討論
- **郵件**：dev@b-marker.com（我不是公司，只是個普通人）
- **請多包涵**：我有正職工作，回復可能會比較慢

> 這是一個業餘愛好項目 — 別期待完美。但如果我們一起努力，或許能做出一個真正對創作者有用的工具。
</details>

---

## 🔗 快速連結 | Quick Links
| 平台 Platform | 地址 Address |
|---------------|--------------|
| 官方網站 Official Website | [b-marker.com](https://b-marker.com) |
| 核心倉庫 Core Repository | [GitHub - bmarker](https://github.com/b-marker-dev/bmarker) |
| 使用文檔 Documentation | [Docs - b-marker.com/docs](https://b-marker.com/docs) |
| 社區交流 Community | [Discord](https://discord.gg/E4rnzGhfY) |

---

## 🛠️ 技術需求 | Technical Requirements
| 項目 Item | 規格 Specification |
|-----------|--------------------|
| 開發語言 Language | Python 3.6+ |
| 依賴框架 Framework | 無需額外框架（輕量級設計，新手可直接運行） |
| 核心演算法 Core Algorithm | 基於44.1/48kHz的音頻時間轉換 |
| 部署方式 Deployment | GitHub Pages / 跨平台打包（Windows/macOS/Linux） |

---

<details>
<summary>🛡️ 公開設計原則 Public Design Principles</summary>

### 繁體中文
1. 模型可插拔：底層 LLM 可隨時置換，不綁死單一供應商。  
2. 成本動態浮動：流量區間變化時，觸發閾值由內部 SLA 即時調整，不對外公開數字。  
3. 失效即逃生：一旦成本或可用性跌破內部紅線，自動降級或切換通道，細節托管於 dev 私有分支。

### English
1. Model-pluggable: the underlying LLM can be swapped at any time — no vendor lock-in.  
2. Cost dynamic bands: thresholds auto-adjust with traffic tiers per internal SLA; exact numbers remain private.  
3. Fail-safe escape hatch: if cost or availability drops below internal redlines, we auto-fallback or reroute; details live in the private dev branch.

</details>

## 💡 Core Philosophy | 核心理念
- 🎧 **Audio is one of the oldest and most profound forms of communication for humanity.** If we could weave time with audio, it would mark a new chapter in human creativity.
  **音頻是人類最古老、最深刻的溝通方式之一。** 如果能夠用音頻編織時間，那將是人類創造力的新篇章。
- ⚛️ **An audio sample is a quantum of time.** Each sample not only carries sound, but also encodes time itself.
  **音頻樣本就是時間的量子。** 每個樣本不僅承載聲音，更編碼著時間本身。
- 🌱 **We are not predicting the future—we are planting the seeds of the future.**
  **我們不是在預測未來，而是在種植未來的種子。**

---

> 🌟 喜歡這個專案？點個 Star 支持一下吧！
> 🌟 Like this project? Give it a Star to show your support!

---

<details>
<summary> 📖 Quick Start | 快速上手教程 </summary>
1. **下載代碼**
```bash
git clone https://github.com/b-marker-dev/bmarker.git
```
2. **運行函數**
打開 Python 終端，直接調用：
```python
from bmarker_core import frames_to_ms
print(frames_to_ms(24)) # 輸出對應毫秒值
```
3. **注意事項**
- 確保 Python 版本 ≥ 3.6
- 無須安裝額外依賴庫
</details>

<details>
<summary> 📜 Changelog | 功能更新日志 </summary>

### v0.1 Alpha (初始版本)
- 完成 4 個核心時間轉換函數
- 支持 24/30fps 畫面幀數 & 44.1/48kHz 音頻採樣

### v0.2 (待更新)
- [計畫] 新增 ms_to_samples() 函數
- [計畫] 支持 60fps 遊戲/短視頻場景

</details>

---
<!--
**b-marker-dev/b-marker-dev** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
-->
