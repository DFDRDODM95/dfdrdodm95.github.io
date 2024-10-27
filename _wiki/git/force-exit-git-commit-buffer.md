---
layout  : wiki
title   : git merge시에 gitcommit 버퍼에서 강제 종료시키기 (:cq)
summary : 
date    : 2024-10-27 11:46:08 +0900
updated : 2024-10-27 11:53:34 +0900
tag     : 
resource: 1e/033de6-e50a-4f24-848b-09463e4c54b7
toc     : true
public  : true
parent  : [[/git]]
latex   : false
---
* TOC
{:toc}

## how-to

git merge시에 gitcommit 버퍼에서 강제로 종료시키는 방법입니다.

>git merge 혹은 git rebase시에 vim buffer에 commit message 입력하는 단계에서 abort 하고 싶은 경우가 있습니다.
>
>이때 gitcommit buffer에서는 :q! 를 하더라도 커밋이 완려 되버립니다. (! 을 쓰면 write 하지않고 종료인데 그게 안되는 상황이죠)
>
>이럴때는 :cq 를 사용하면 에러를 발생시키면서 종료시키기 때문에 커밋이 되지 않습니다.
>
>즉 :cq 를 하고나서 git rebase --abort 를 하시면 됩니다.

## 출처

vim.kr 디스코드의 `tip-and-trick` 채널, devstefancho님의 포스트

# 
