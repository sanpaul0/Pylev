для создания ключа
ssh-keygen
ssh-keygen -t ed25519 -C "имя.фамилия@phystech.edu"
cat ~/.ssh/id_ed25519.pub
eval "$(ssh-agent -s)"
cat ~/.ssh/id_ed25519.pub скопировать полученный ключ
создать репозиторий, копировать ссх и вставить в команду вместо урл
git clone <url>
