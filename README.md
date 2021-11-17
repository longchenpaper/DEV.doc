# 版控開發流程

|  | 步驟 | 指令 |
| --- | --- | --- |
| 1 | 將 master 更新到最新版本 | git pull |
| 2 | 從 master 切功能分支，進行開發 | git checkout -b <分支名稱> |
| 3 | 將所有變更加入索引 | git add . |
| 4 | 提交變更 commit | git commit -m "敘述本次變更的內容" |
| 5 | 擷取最新版本 | git fetch origin |
| 6 | 將最新版本合併至功能分支 | git rebase origin/master |
| 7 | 將功能分支推送至遠端倉庫 origin | git push -u origin <分支名稱> |
| 8 | 到 Github 遠端倉庫提交 PR | 無指令，在介面進行 PR 提交 ([PR 範例](https://github.com/longchenpaper/UOF_DEV/pull/5)) |

<br>

### 步驟 6 如遇到衝突，請解完衝突後再推送 PR
