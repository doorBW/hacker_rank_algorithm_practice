# 차량 정비소

막상 이번에 시험보게 될 SW 역량 테스트를 위해 그동안 java를 이용해서 했는데… python이 추가되었다는 소식을 듣고 오랜만에 좋아하는 python으로 컴백하여 푼 문제!!!



많이 어렵거나, 크게 복잡하지 않아서 딱 좋았던 것 같다.

단순히 단방향으로 작업 처리를 하는게 아니라, 실제로는 해당시간에 한번에 접수, 정비 등의 작업이 처리된다는 것을 고려해야 한다.

하지만 우리가 멀티스레드로 두고 동시에 5개가 하게 되도..뭐.. 제대로 되지는 않을 것

그러면, 실질적으로 먼저 처리해야 되는 부분을 생각해야 한다.

그리고 각각의 접수 및 정비 작업 앞에 wait 라는 대기소를 만들어 줘야한다.

이러한 점들을 고려하면 크게 어렵지 않게 풀 수 있는 문제라고 생각!