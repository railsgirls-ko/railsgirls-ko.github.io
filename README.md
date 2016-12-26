# Rails Girls 한글 가이드

우리의 목표는 여성이 기술을 이해할 수 있는 도구를 제공하는 것입니다. Rails Girls 이벤트는 인터넷 구축에 대한 훌륭한 첫 경험을 제공해주는 것을 수행합니다.

Rails Girls는 2010년 말 헬싱키에서 설립되었습니다. 원래는 한번의 행사로 의도되어졌고, 우리는 전세계의 많은 지부를 볼 수 있다는 것을 생각해본 적이 없습니다.

자료와 지침을 사용하여 도시, 직장 또는 주방에서 워크샵을 시작할 수 있습니다! http://railsgirls.com에서 Rails Girls에 관해 좀더 살펴보세요!

## 빠르게 시작하기

http://guides.railsgirls.com에서 가이드를 보거나 or 해당 repo를 clone하고 설치하고 동작시키세요.[jekyll](https://github.com/mojombo/jekyll)

### jekyll 설치하기

```
$ cd railsgirls.github.com
```

```
$ bundle install
```

### Pygments and 코드 강조

가이드는 [pygments](http://pygments.org/) 라이브러리를 사용하여 구문 강조를 수행합니다. 설치하지 않으면 다음과 같은 하이라이트 섹션을 볼 수 없습니다. 

```
{% highlight %}
{% endhighlight %}
```

코드 블록을 편집하지 않으면 이 코드를 무시해도 됩니다. Pygments을 원할 경우, "Pygments" 섹션의 [설치 지침](http://jekyllrb.com/docs/installation/)을 참조하세요.

### jekyll 실행

```
$ bundle exec jekyll server --watch
```

### 스타일링

[kbd](https://www.w3.org/wiki/HTML/Elements/kbd) HTML 태그로 키보드 단축키를 줄 바꾸기.

스타일을 일관되게 유지하려면 `CTRL-c`/`ctrl+c`를 통해 `Ctrl+C`를 사용하십시오.

```
서버를 종료하려면 <kbd>Ctrl</kbd>+<kbd>C</kbd>
```

### 문제가 있나요?

예상대로 작동하지 않는 경우 Jekyll에서 유용한 힌트를 찾을 수 있습니다: [Issue 503](https://github.com/mojombo/jekyll/issues/503)

## 기여  가이드

가이드에 기여하려면, http://guides.railsgirls.com/contributing에서 지침서를 보세요.

## 트위터

업데이트 및 추가 정보[@railsgirls](https://twitter.com/railsgirls)

## 웹 사이트 & 블로그

Rails Girls 운동을 위한 공식 웹 사이트 http://railsgirls.com에서와 블로그에서 찾을 수 있습니다.

## 이메일 리스트

http://groups.google.com/group/rails-girls-team Rails Girls 이벤트들을 위한 국제 메일 목록

## Credits

* Karri Saarinen / [@karrisaarinen](https://twitter.com/karrisaarinen) / [github](http://github.com/ksaa)
* Linda Liukas / [@lindaliukas](https://twitter.com/lindaliukas) / [github](http://github.com/lindaliukas)
* Vesa Vänskä / [@vesan](https://twitter.com/vesan) / [github](http://github.com/vesan)
* Terence Lee / [@hone02](https://twitter.com/hone02) / [github](http://github.com/hone)

.. 그리고 다른 모든 코치들과 Rails Girls를 만드는 사람들은 굉장합니다. 자신을 추가하십시오.
