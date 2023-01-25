## 起動方法
1. docker run -itd -v $PWD:/home -w /home -p 127.0.0.1:3000:3000 --name script-last ruby /bin/bash
2. docker exec -it script-last /bin/bash
3. apt update
4. apt install sqlite3
5. gem install rails
6. bundle install
7. rails server -b 0.0.0.0

access to(probably)↓
http://localhost:3000/ 

基本は授業スライド通りなのであとはよしなに。
