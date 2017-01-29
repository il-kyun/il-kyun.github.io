---
layout: post
title:  "start jekyll!"
date:   2017-01-29 19:41:00 +0900
categories: main
---

2013-05-01 시작이었다.

tistory를 해볼까? blogger를 해볼까? 하다가 `github pages`를 알고 jekyll을 사용하기로 정했다.

이미 많은 분들이 사용하고 계시기 때문에 쉽게 찾을 수 있고 git으로 관리 할 수 있다는 점이 마음에 들었다.

[github-pages-basics][github-pages-basics]를 보면 자세한 설명을 볼 수 있다.

간단히 말하면 github repository를 기반으로 간단한 정적 페이지를 호스팅 해준다는 거다.

예를 들어 github 이름이 il-kyun라면 il-kyun.github.io라고 repository name을 만들면 il-kyun.github.io로 연결을 해준다.

단 repository가 1GB를 넘지 않는 것을 추천하며 bandwidth가 100GB/month로 제한이 된다.

1. userName.github.io로 repository를 생성
2. Settigns -> GitHub Pages에서 theme을 선택

이렇게 1&2 만으로도 페이지 생성이 완료 되고 접속하여 확인 해 볼 수 있다.

[pages-github][pages-github]에 매우 잘 정리 되어있다.

단 관리를 위해서 로컬에 jekyll 환경을 구축하고 사용 하는 것을 추천한다.

로컬에 구축하기 위해서는 ruby를 설치 해야 한다.

[jekyll-windows][jekyll-windows]를 단계 별로 따라하면 어렵지 않게 할 수 있고 `3.syntax` 부터는 필수는 아니다.

설치 후 패키지를 설치하고

{% highlight command %}

  //instal packages
  gem install github-pages
  gem install bundler

{% endhighlight %}

원하는 theme 프로젝트를 다운 받아서 `RubyDevKit` 하위 폴더에 폴더를 만들고 해당 폴더에 git을 add해서 사용하면 된다.


ref :
https://help.github.com/categories/github-pages-basics/ -
http://yongho1037.tistory.com/599#recentTrackback
http://jekyll-windows.juthilo.com/
https://pages.github.com/


[github-pages-basics]: https://help.github.com/categories/github-pages-basics/
[pages-github]:   https://pages.github.com/
[jekyll-windows]: http://jekyll-windows.juthilo.com/
