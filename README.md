# Git Lab Repository
git bisect good $(git log --reverse --oneline | head -n 1 | awk '{print $1}')
chỉ định commit đầu tiên chưa có bug
