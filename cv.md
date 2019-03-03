# Yuliya Pakidzka


  :telephone_receiver: *+375292311231*

  :email:   <julanick@gmail.com>
  
 

***

## Objective  
My main expectations and goals:
 * Improving of knowledge and get new skills of using development tools;
 * Get basic understanding of the best practices of modern applications design;
 * I want to gain teamwork experience with professionals.


 ## Summary
  I have 5 year experience of working as L2 Support engineer. Technologies I'm working with are SQL, Delphy, 1C, FastReport.
 My main responsibilities :
- Supporting of different system;
- Making of small changes and sometimes bug fixing in programs;
- Implementation of new features in legacy enterprise applications.

The main reason I'm on this courses is that a technologies at my current job is outdated. And I wish to develop myself as professional  to achieve success: career, skills, recognition, financial.

 ***

 ## Skills

Foreign language | English (B1), German (basic)
:--- | :----:
DB | Informix, FoxPro, Cache, MSSQL
Programming languages | Delphi, Pascal, 1C, JavaScript, HTML, CSS, Git Bash
 


***
As an example, I can give the text of the stored procedure Update from the Informix database: :relaxed:
```
CREATE PROCEDURE "informix".p_upd(vold_list integer, vnew_list integer)

returning varchar(250);
define vorder_id integer;
define vsvc_id integer;
define vnewsvc_id integer;
define vname varchar(250);

foreach cur1 for

  select x.order_id ,y.svc_id, z.name
  into vorder_id, vsvc_id, vname 
  from (prl_order x 
  join prl_ord_svc y
  on x.order_id=y.order_id)
  join prl_svc z
  on y.svc_id=z.svc_id
  where x.id_arm=98 and x.order_date >'31.12.2015' and z.pricelist_id=vold_list
  
  select svc_id 
  into vnewsvc_id
  from prl_svc
  where pricelist_id=vnew_list and name=vname;
  
  update prl_ord_mat
  set svc_id=vnewsvc_id
  where order_id=vorder_id and svc_id=vsvc_id;

  update prl_ord_svc
  set svc_id=vnewsvc_id
  where order_id=vorder_id and svc_id=vsvc_id;

end foreach;
 return '' with resume;

end procedure;
}
```
***
 **My tests tasks:** 

 * *HTML CSS Basics*: https://www.codecademy.com/users/juliyaPakidzka4293641960/achievements

* *HTML Academy*: https://htmlacademy.ru/profile/id956891/achievements


***

## Education

**Higher education**

**2016 - till now**   
**International School of English "IH"**    

**2009 - 2014**   
**Belarussian National Technical University**   
  Faculty : Information Technologies and Robotics
