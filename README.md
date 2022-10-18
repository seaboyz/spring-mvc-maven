# spring-mvc-maven

## Build a Basic webapp using maven
#### Create a maven webapp 
![](create%20new%20project.png)
![](/images/starters/Screen%20Shot%202022-10-18%20at%2010.54.30%20AM.png)
![](/images/starters/Screen%20Shot%202022-10-18%20at%2010.54.42%20AM.png)
![](/images/starters/Screen%20Shot%202022-10-18%20at%2010.54.53%20AM.png)
![](/images/starters/Screen%20Shot%202022-10-18%20at%2010.55.03%20AM.png)
#### Build war file
```
mvn clean package
```
#### Deploy war to tomcat
![](/images/starters/Screen%20Shot%202022-10-18%20at%2011.07.06%20AM.png)
![](/images/starters/Screen%20Shot%202022-10-18%20at%2011.07.25%20AM.png)
![](/images/starters/Screen%20Shot%202022-10-18%20at%2011.07.38%20AM.png)
![](/images/starters/Screen%20Shot%202022-10-18%20at%2011.09.41%20AM.png)
![](/images/starters/Screen%20Shot%202022-10-18%20at%2011.09.41%20AM.png)
![](/images/starters/Screen%20Shot%202022-10-18%20at%2011.09.50%20AM.png)
![](/images/starters/Screen%20Shot%202022-10-18%20at%2011.10.02%20AM.png)


#### Add spring maven dependencies in pom.xml 
![](/images/add%20maven%20dependency/Screen%20Shot%202022-10-18%20at%2011.35.37%20AM.png)
![](/images/add%20maven%20dependency/Screen%20Shot%202022-10-18%20at%2011.35.59%20AM.png)
![](/images/add%20maven%20dependency/Screen%20Shot%202022-10-18%20at%2011.36.37%20AM.png)

## Add DispacherServlet
#### Add main-menu.jsp in view folder
![](/images/add%20dispacher%20servlet/Screen%20Shot%202022-10-18%20at%2011.50.35%20AM.png)
#### Add HomePageController to direct "/" to main-menu.jsp
![](/images/add%20dispacher%20servlet/Screen%20Shot%202022-10-18%20at%2011.41.52%20AM.png)
#### Edit web.xml file def base-package and MVC view resolver
![](/images/add%20dispacher%20servlet/Screen%20Shot%202022-10-18%20at%2011.48.21%20AM.png)
#### Add DisPacherServlet config file
![](/images/add%20dispacher%20servlet/Screen%20Shot%202022-10-18%20at%2011.47.32%20AM.png)
#### Remove the default index.jsp
```
mvn clean package
```
#### Redeploy war file
![](/images/add%20dispacher%20servlet/Screen%20Shot%202022-10-18%20at%2012.03.17%20PM.png)
![](/images/add%20dispacher%20servlet/Screen%20Shot%202022-10-18%20at%2012.03.39%20PM.png)

![]()
![]()
