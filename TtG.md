---
layout : page
title : TtG
---

### 개발자 관찰 관련해서 생각을 해보자.

{% highlight html %}
Requirement
  * 이후 연구에 도움이 되는 방향이면 좋다.
  * 내가 생각하기에 재미있어야 한다.
  * Don`t be too clever, focus on simple key idea.
{% endhighlight %}

### Autometic Tuning for CSA application(우렁각시)

{% highlight html %}
지금 개발자들이 CSA 튜닝을 어떻게 하는가?
  * 특히 튜닝 과정은 앱의 동작 정확도(e.g Context감지 정확도를) 고려하며 
    진행할것으로 보이는데 지금 앱의 정확도는 어떤 방식으로 관찰하고 있는가?
    (파워의 경우 어찌되었던 배터리 레벨로 관찰 가능할것 같은데 앱이 얼마나 
    정확하게 동작하는지를 파악하는 방식은 현업에서 어떻게 하는지 잘 모르겠다.)    
  * 튜닝 과정이 Automation 되는게 필요한가?
    (튜닝 과정이 burden이 크고, iteration이 많이 필요하다고 가정을 했었는데 
    이걸 보여주는 부분이 지금으로썬, 약해보임.)
{% endhighlight %}

### Benchmark set for CSA Development

{% highlight html %}
지금 개발자들은 어떤 시나리오를 가정하고, Target해서 개발하고 있는가?
  * 개발중인 CSA가 어떤 시나리오에 대해서 에너지 테스팅이 필요한지 
    (e,g 에너지 문제 없이 잘 동작해야 되는지) 어떻게 정하는가?
  * 주어진 시나리오에서 '에너지 문제없이 동작'한다는 건 어떻게 판단하는가?
  * 시나리오 별로 에너지를 얼만큼 정도 소모해야하는지는 어떻게 정하는가?
  * 지금 어떤 수준의 Coverage를 염두에 두고, 앱을 개발하고 있는지?
{% endhighlight %}

### Multiple Sensor Devices Aware Devleopment

{% highlight html %}
단순 모바일을 넘어선 개발을 고려할때는 무엇이 새로 필요한가?
  * 앞으로는 휴대폰 하나만 생각하며 만들기 보다는 수많은 센서들이 서로 
    상호작용하는 환경을 고려하며 개발을 해야할 텐데, 그런 개발 과정에서는 
    어떤 툴이 필요할까? 
  * 다양한 기기간의 상호작용을 고려하는 지금의 사례는?
{% endhighlight %}


### Power Aware Development Process (PAPA)

{% highlight html %}
지금 우리가 생각하고 있는 개발 프로세스는 XXX인데 이걸 수행할 수 있을만 한가?
  * 지금 Idea_Sketch에 있는 개발단계는 현업에서 실제로 Practical하게 진행하기에는
    너무 긴 면이 있다. (Power_Goal설정, Workload Design, Logic Design, 
    Implementation, testing/debuging, Power tuning, QA power testing,
    Power-aware maintenance.)
  * 만약 우리가 제시하려한 방안대로 개발을 진행한다고 했을때, 어떤 단계 때문에 현업에 
    적용하기가 어려운것 같은가? (만약 여기서 특정 과정이 많이 언급된다면, 언급되는 과정을 
    Support하는 툴이 필요하다는 걸 알아낼 수 도 있을것 같다).
{% endhighlight %}
