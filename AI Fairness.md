# AI Fairness
 I learned and heard about AI Fairness from my favorite professor. (not allow to share so I am sharing another example from the web)


- Example by Dongah Science 

- 1. Demographic Parity
- 위 사례에서는 대출 신청의 성별에서 여성을 차별을 예로 들고 있다. 공정하게 대출을 해주기 위해서 한가지 방법으로 제시한 것은 성별에 대한 정보를 아예 없애는 것이 있었지만 기계학습을 한 인공지능은 성별정보가 없어도 충분히 이를 유추할 수 있다는 이유로 성비를 신청자의 성비와 똑같이 하자는 제안을 한다. 신청자 중 여성이 40%였으니 대출승인에서도 여성을 40%로 하자는 것이다.
- Advantage & Disadvantage 
- One of the advantages of demographic parity is the point that we can try this metric usefully for each group with the same fraction of people. For example, we can make the same promotional offer for each group in equal proportion. It’s kind of a promotional event for both groups of low income and high income using this metric and we deem it a good or fair(?) offer, which has the same rate. However, sometimes it’s not good enough depending on who uses this metric in terms of cost-effective promotion.


- 2. Equalized of odds
- 돈을 갚을 사람이 얼마나 되는지 분명히 알아야 한다고 한다. 한쪽 성별에 돈을 안 갚는 사람이 몰려 있을 수도 있으니까. 일단 신청자에 따라 성비를 맞추더라도, 남성과 여성 중 돈을 분명히 갚을 사람의 비율을 먼저 살펴보고 그 비율에 맞게 돈을 빌려줘야한다.
- 남성 중 돈을 값는 사람이 33%이면 여성 중 돈을 값을 사람이 50%라면 최종적으로 대출 받는 사람도 남성 중 33%는 돈을 갚는 사람으로 여성도 50%는 돈을 갚을 사람으로 구성
- 문제 : 돈을 갚을 사람의 비율이 너무 적다.

- Advantage & Disadvantage 
- Advantage of Equalized odds is the metric avoiding discrimination against protected group. For example, if we have certain criteria to expect that the person is more likely to commit the crime, no matter who they are, they will be sentenced to jail. The same applies to being innocent. There’s no big difference to the true positive and false positive. Disadvantages of it is the misuse of the matric causes another bias. For example, we can apply it to the process of hiring or school admission. Top students from the most competitive school and top students from the least competitive school are different. However, if the school has selected every top student from each school, it might sound unfair. Therefore, schools decide to allocate a different proportion of the enrollment quota to select only real top students so the number of qualified people might be different from each group. Surprisingly, the methods of assessment for fairness might make an impact on a cause of huge gaps between groups later. After all, it can turn out to be biased in the real world.
As a result, bias repeats and if it sounds unfair, then people get angry. Poor algorithm and candidates.
