# jsp-servlet-jdbc-tutorial

在新環境中佈署時，要注意需要修改的地方可能有：

1.UserDAO.java
  1) jdbcURL = "jdbc:mysql://localhost:3306/demo?serverTimezone=CST";
  2) jdbcUsername = "<Your database username or root name>";
  3) jdbcPassword = "<Your database username password or root password>";
  
2.中文編碼的問題：
  >1) Servlet (於處理Get POST的doGet或doPost都可以加上以下程式碼) <br>
     response.setContentType("text/html; charset=utf-8");<br>
     request.setCharacterEncoding("utf-8");
  >2) 或使用jsp檔案，並於標頭設定中注意編碼為UTF-8 <br>
     <%@ page language="java" contentType="text/html; charset=UTF-8" pageEncoding="UTF-8"%>



### Java web course mini project - Media blog
1. Pages：
  >1) index: blog list page
  >2) single: blog single page
  >3) about: blog about page(list some author info)
  >4) login: blog owner login page
  >5) admin-index: blog admin list page(after login)
  >6) admin-single: blog admin single post new/edit page
  
2. Databases(models)：
  >1) blog user account
  >2) blog posts
  
3. 


### Java web course final project - Inventory System
1.Pages：
  >1) 
