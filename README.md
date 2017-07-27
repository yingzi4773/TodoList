# TodoList
主要功能：用户的登录注册；待办事宜的增删改；用户自定义头像的上传<br>
涉及到的技术：nodejs,express框架，mongodb非关系型数据库，mongoose框架，ejs模板，expressSession记录登录状态<br>
<h2>用户的登录注册<h2>
<h4>登录功能<h4>
<ul>
  <li>得到请求的数据,get请求是 req.query.userName   post请求的数据是在body中，因此req.body.userName</li>
  <li>验证用户输入是否正确，这是需要从数据库中取出userName对应的密码，比较
    <ul>
      <li>数据库需要根据user的id找到用户信息，找到的话就说明用户登录正确，就渲染到listItem页面</li>
       <li>否则输出不正确</li>
      </ul>
  </li>
  
</ul>




<h2>待办事宜的增删改<h2>




<h2>用户自定义头像的上传<h2>
