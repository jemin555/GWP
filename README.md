# GWP
======

G$WP is  focussed for GDollar and  DOTNET  Professionals for Mobile web/remoteweb/biometric web/remoteweb application . it is invented by wilmix jemin j . 



SYNTAX:
=======



<? language=gdollar /> //  indicate the  language  gdollar focused  for   gdollar  and  dotnet  professionals.
<IMPORT> packages; // import  util packages



 

<%




public class <classname> {


 public void main()
{


HTML.displayhtml("???");// display  the  contents  of  html  to    browser


 
}

}



%>


?>


index.Gdollar
==============
<? language=gdollar />
<IMPORT> java.util.*;



 

<%




public class index {


 public void main()
{


HTML.displayhtml("Register.html");


 
}

}



%>


?>


Register.html
==============

<html>
  <head>
    <title>STUDENT  REGISTRATION</title>
    
  </head>

  <body class="fancy">
<form action="http://localhost:8090/Jquerytest.j$" method="post" >

<div id="pageContainer">
     
      <div id="pageContent">

        <div id="chaptersAccordion">

            <h2><a href="#chapter1">Enter your   Details</a></h2>
            <div>
              

<p>Enter  Your Name: <input type="text" name="name" size="25" /></p>
<p>Enter your Username : <input type="text" name="uname" size="15"/></p>
<p>Enter  the password : <input type="password" name="password" size="25" /></p>
<p>Choose your  state  : <input type="text" name="state" size="15"/></p>
<p>Choose  your  Country  : <input type="text" name="country" size="15"/></p>

<p>Enter  the   password : <input type="password" name="spwd" size="25" /></p>
<p>Enter your secret  password text : <input type="text" name="stext" sixe="15"/></p>

<p>Enter  your family details : <input type="text" name="familydet" size="25" /></p>

<p> Enter  Percentage of  marks  scored <input type="text" name="Indent" sixe="5"/></p>

<p>Enter Your Favourite subject <input type="text" name="CIndent" size="15"/></p>


            </div>


<h2><a href="#chapter2">REGISTER</a></h2>
            <div>
              <input type="submit" name="Click">
<input type="reset" name="Clear">
            </div>


</form>

</body>
</html>


Jquerytest.j$
==============


<JDollar> =>  starting  point of  J$  program

<USE> <WEB>.util; // load  util  packages  for  jdollar from  .dll  set  from properties  file


<PACK> Program5
{
  
    <CLASS> Prog
   {

  
      public void Main()
      {

ArrayList arm1= new ArrayList();

arm1.add("name");
arm1.add("uname");arm1.add("password");
arm1.add("state");
arm1.add("coun<TRY>");
arm1.add("spwd");
arm1.add("stext");
arm1.add("familydet");
arm1.add("Indent");
arm1.add("CIndent");
//  10 fields names  should  be  added  to  arraylist
arm1.add("NOT");

<PRINTLN>("<HTML>");

<PRINTLN>("<BODY bgcolor=pink>");

<PRINTLN>("<form>");
 
  

ArrayList  armg= Request.Query(arm1,"index.cl.dsn",10,1);

// increment  the  field  value  one by  1 ;  retrieve  the  value  stored  at .dsn file

 <PRINTLN>("<table style='width:100%' bgcolor=gold>"); // simillar  to Console.WriteLine

<PRINTLN>("<tr>");

<PRINTLN>("  <th>Name</th>");
  
<PRINTLN>("  <th>Username</th>"); 
  
<PRINTLN>("  <th>Password</th>");
  
<PRINTLN>("  <th>State</th>");
  
<PRINTLN>("  <th>Country</th>");
  
<PRINTLN>("  <th>Confirm Password</th>");

<PRINTLN>("  <th>Secret Password</th>");

<PRINTLN>("  <th> FamilyDetails </th>");
<PRINTLN>("  <th>Percentage of Marks Scored</th>");
<PRINTLN>("  <th>Subject</th>");
   
<PRINTLN>(" </tr>");
   
<PRINTLN>(" <tr>");



for (int i=armg.size()-10;i<armg.size();i++)
{


   <PRINTLN>("<td>"+armg.get(i)+"</td>");
  
  // print  from  arraylist
   
 }

  
<PRINTLN>(" </tr>");
 
  
<PRINTLN>("</table>");


<PRINTLN>("</form>");

<PRINTLN>("</html>");
      
 

		
}


}

}
