# MCAS Git練習
Owner：Lee X-X 一號

## 添加訊息
你怎麼能直接 commit 到我的 main 分支啊？ ！ GitHub 上不是這樣！ 你應該先 fork 我的倉庫，然後從 develop 分支 checkout 一個新的 feature 分支，例如叫 feature/confession。 然後你把你的心意寫成程式碼，並為它寫好單元測試和整合測試，確保程式碼覆蓋率達到95%以上。 接著你要跑一下 Linter，通過所有的程式碼風格檢查。 然後你再 commit，commit message 要遵循 Conventional Commits 規範。 之後你把這個分支 push 到你自己的遠端倉庫，然後給我一個 Pull Request。 在 PR 描述裡，你要詳細說明你的功能改變和實現思路，並且 @ 我和至少兩個其他的評審。 我們會 review 你的程式碼，可能會留下一些評論，你需要解決所有的 thread。 等 CI/CD 管線全部通過，並且拿到至少兩個 LGTM 之後，我才會考慮把你的分支 squash and merge 到 develop 裡，等待下一個版本發布！ GitHub 上根本不是這樣！ 我拒絕合併！