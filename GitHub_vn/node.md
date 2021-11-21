# Terms

Reponsitory (Repo)
Branch (Nhánh)
Conflict (Xung đột khi merge 2 branch cùng chỉnh sửa 1 đoạn. khi đó phải chọn giữ đoạn code nào. Khi chọn xong gõ "git add ." -> "git commit" để lưu)

Local
Remote

# Commands

- git init (khởi tạo git cho folder)
- git status (xem trạng thái git folder)
- git add + name_file (thêm dữ liệu đã thay đổi)
- git reset (hoàn tác)
- git commit -m + 'bình luận' (xác nhận dữ liệu đã thay đổi )
- git log (xem lịch sử cụ thể log)
- git log --oneline (xem lịch sử rút gọn log)
- git checkout + ID_LOG (trở lại dự án đã lưu ở ID đó) 
- git checkout + Branch_Name(di chuyển đến branch)
- git branch (xem tất các branch và vị trị hiện tại đang thuộc branch nào. Ưu tiên vị trí branch mới tạo)
- git checkout -b + Branch_Name (tạo 1 branch mới)
- git merge + Branch_Name_New (tổng hợp branch mới vào branch master)
- git branch -d + Branch_Name (Xoá 1 branch. Lưu ý kiểm tra branch và lưu file trc khi xoá)


- git push + URL_Reponsitory_Github + Branch_Name (push folder code theo branch lên server github, hay reponsitory)
- git remote add origin URL_Reponsitory_Github(đổi tên url github thành 'origin')
- git push + origin + Branch_Name (push folder code theo branch lên server github, hay reponsitory)

- git clone + URL_Reponsitory_Github (clone lại folder github nếu ko may xoá nhầm)
- git push (push toàn bộ lên server github, chỉ dùng dc khi clone folder code từ server github về máy)
- vào vscode nhanh: mở terminal -> cd vào folder code -> gõ "code ."

- git push -u origin + Branch_Name (push branch tạo từ pc lên sv github, sau bước này chỉ cần dùng git push để push folder code theo branch)

- git fetch origin (check branch chỉ đang tồn tại trên sv Github)
- git checkout -b + Branch_Name_ServerGithub + origin/Branch_Name_ServerGithub (kéo branch tạo từ sv Github về pc)

-git pull (kéo merge từ sv github về pc)

