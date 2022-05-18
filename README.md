# HTMl
![image](https://user-images.githubusercontent.com/62333447/168454573-e04a8866-37e2-4ab3-90d7-52214bebc148.png)

b는 의미없는 텍스트를 강조해주는 것이고 strong은 강조뿐만 아니라 실제로 페이지에서 중요한 부분을 브라우저에게 알려주는 역할을 한다.
브라우저가 strong 태그를 해석할 때 페이지 내에서 중요한 부분으로 이해하면, 이는 브라우저에서 지원되는 웹 접근성에 큰 기여를 한다.
holder
즉, 차이점은 화면 낭독기이다. <strong> 태그를 사용하면 화면 낭독기는 해당 부분이 강조되었다고 알려주나, <b>태그는 알려주지 않는다. 
  <hr>
  
# value 와 placeholder
  
  ##### value는 input의 기본값을 지정할 수 있다. 기본값이 아닌 다른 문구를 지정하고 싶다면 placeholder를 사용하여 작성할 수 있다.
  ##### 둘 다 문구를 나타내지만 value로 지정한 기본값은 그 상태로 버튼을 누르면 기본값 자체로 전송되지만 placeholder는 버튼을 눌러도 전송되지 않는다
  
  <hr>
  # CSS
  
  ####inline style은 쉽고 간단하지만 꾸미는 데에 한계가 있고 재사용이 불가하다.
  
  ####internal style은 <style>과</style>사이에 CSS를 넣는 것이다. 예를 들면
  
  <style>
    h1{
      color : blue;
    }
  </style>
  
  로 표현한다. 이 방법은 한번에 꾸밀 수 있으나 다른 html문서에서 사용할 수 없다는 단점이 존재한다.
  
  ####linking style은 CSS를 만들고 html파일과 연결하는 형태이다. 
