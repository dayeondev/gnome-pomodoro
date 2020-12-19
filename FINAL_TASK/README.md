### gnome-pomodoro

--------------



#### 어떤 프로그램인가?

gnome-pomodoro(https://github.com/codito/gnome-pomodoro)는 **포모도로 기법**(https://en.wikipedia.org/wiki/Pomodoro_Technique)을 활용한 그놈 전용 프로그램으로, 짧은 휴식을 주기적으로 주어 **생산성을 향상** 시키는 것이 목적이다. (기여자는 20/12/19 기준 64명이다.)

<img src="https://user-images.githubusercontent.com/46081429/102678348-1e83b480-41eb-11eb-8042-8df7d6c7e9d5.png" alt="Screenshot from 2020-12-19 11-12-15" style="zoom: 50%;" /><img src="https://user-images.githubusercontent.com/46081429/101980671-64e88900-3caa-11eb-909c-c4c12a8fe38e.png" style="zoom: 38%;" />

왼쪽은 첫 번째 화면이다. 중앙의 시작 버튼을 누르면 타이머가 동작하고, 남은 시간을 시각적으로(오른쪽 이미지) 나타낸다. 시간이 다 되면 종 소리와 함께 화면이 어두워지고 휴식 시간이 나타난다(물론 마우스를 움직이면 화면이 다시 밝아지고 휴식 시간 동안 컴퓨터를 사용할 수 있다.).

다음은 설정 창이다.

<img src="https://user-images.githubusercontent.com/46081429/102678535-91d9f600-41ec-11eb-9ea8-007c91ae6676.png" alt="Screenshot from 2020-12-19 11-16-25" style="zoom: 67%;" />

일 할 시간과 휴식 시간, 그리고 긴 휴식 시간을 직접 정할 수 있고 원하는 타이머 소리(실제 포모도로 타이머의 째깍째깍 소리)를 지정하는 것도 가능하다. 알림음도 마찬가지이며 기타 옵션들도 존재한다.



#### 왜 이 프로젝트를 선정했는가?

선택지로 두었던 프로젝트는 gnome-pomodoro, InstaPy, python-telegram-bot이 있었다. 그러나 gnome-pomodoro를 선정한 이유는 몇 가지가 있는데 가장 큰 이유는 내가 유용하게 사용하는 프로그램이기 때문이다. 프로그램을 사용하며 감사한 마음을 갖고 있었지만 어떻게 돌려줄 지에 대한 고민은 하지 못했던 것 같다. 그렇기에 이번 기회에 감사를 표현하고 내가 사용하는 프로그램에 기여했다는 뿌듯한 마음을 느껴보고 싶어 이 프로젝트를 선택하였다.

다른 이유로는 친절함 때문이다. 프로젝트를 소개하는 웹 페이지(https://gnomepomodoro.org/)가 존재하고, 그 곳에 기여를 환영한다는 메시지가 있었다. 어떻게 번역 기여를 할 수 있는지도 상세하게 쓰여있었기에(https://github.com/codito/gnome-pomodoro/wiki/Translating) 헤매지 않을 수 있겠다는 마음이 들었다.



#### 어떻게 기여하였는가?

> gnome-pomodoro의 번역 기여 가이드(https://github.com/codito/gnome-pomodoro/wiki/Translating)

번역 기여 가이드에 따라 기여를 시작했다. 

1. 포크 뜨기

   - Github의 fork기능으로 프로젝트를 복제하였다.
   - <img src="https://user-images.githubusercontent.com/46081429/102685447-f3698700-4223-11eb-9efe-8c8f43cc91d0.png" alt="Screenshot from 2020-12-19 17-58-44" style="zoom:67%;" />

2. 설명에 따라 ko.po파일 생성하기

   - ```
     $ cd po
     $ make gnome-pomodoro.pot-update
     ```

   - ```
     $ msginit --locale=ko --input=gnome-pomodoro.pot
     ```

3. Poedit(https://poedit.net/) 프로그램을 통해 번역 파일 작성하기

   - <img src="https://user-images.githubusercontent.com/46081429/102679963-7f18ee80-41f7-11eb-863c-adf76791b4b1.png" alt="Screenshot from 2020-12-19 12-41-12" style="zoom: 50%;" />

4. 내 Repository에 Commit 및 Push 하기

   - 커밋 로그(https://github.com/dayeondev/gnome-pomodoro/commit/2f7df1844a97b489dfd6b1cc194f800268846289)

5. Pull Request 하기

   - https://github.com/codito/gnome-pomodoro/pull/530
   - 번역을 추가한 후 풀 리퀘스트를 보냈으나 반응이 없었다. 그래서 메일을 전송했다.

6. 커뮤니케이션

   - 커뮤니케이션 기록
   - <img src="/home/dayeon/.config/Typora/typora-user-images/image-20201219125207206.png" alt="image-20201219125207206" style="zoom: 67%;" />
   - 마침내 Pull Request가 수락되었고, 담당자가 배정되었다.
   - 리뷰 내용(https://github.com/codito/gnome-pomodoro/pull/530)
   - <img src="https://user-images.githubusercontent.com/46081429/102680180-69a4c400-41f9-11eb-897f-d7ac647e3c47.png" alt="Screenshot from 2020-12-19 12-54-16" style="zoom:50%;" />

7. ~~Merge~~

   - 안타깝게도 그 이후에 Merge가 이루어지지 않았다. 배정된 담당자(https://github.com/kamilprusko)와 소통하기 위해 연락처를 찾아보았으나 이메일, 번호, SNS 등 연락처를 확인할 수 없었고 깃허브의 활동도 적었다. 그래서 추가적인 커뮤니케이션은 불가능했고, Merge되지 못했다.

