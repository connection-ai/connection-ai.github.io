---
title: "AUROC vs AUPR"
date: 2020-04-17 08:26:28 -0400
categories: etc
---

알고리즘끼리 정확도를 비교할 때, Accuracy 하나만 가지고 비교하는 것은 위험할 수 있음은 잘 알려진 사실이다.
이를 위해 TPR, FPR, Accaracy, Recall 등 다양한 지표를 사용하는데, 보통은 threshold에 따라 이 지표의 값이 계속 변화하기 때문에, threshold에 의존하지 않으면서도(즉, 모든 threshold에 대해서) 알고리즘 성능을 평가하는 measure가 필요하다.

Out-of-Domain Detection에서는 2개의 평가 지표 AUROC, AUPR가 사용되는데, 이 두 개의 차이점은 무엇일까?
[TheRelationshipBetween Precision-Recalland ROC Curves] 논문을 참고하면, 얻을 수 있는 정보가 많다.

[TheRelationshipBetween Precision-Recalland ROC Curves]: https://dl.acm.org/doi/10.1145/1143844.1143874
<!--
You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.

To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

​```python
def print_hi(name):
  print("hello", name)
print_hi('Tom')
​```

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
-->
