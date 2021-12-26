# **Paso 1**
[Paso1-1](/Paso1/1-1.jpg "" )

**codigo:**

insert into genres (id, name, ranking, active)
values(default, "investigación", 13, 1)

[Paso1-2](/Paso1/1-2.jpg "" ) 

**codigo:**

update genres 
set name = "investigación cientifica"
where id = 13;

[Paso1-3](/Paso1/1-3.jpg "" )

**codigo:**
 delete from genres 
    where id = 13 

[Paso1-4](/Paso1/1-4.jpg "" )

**codigo:** 

 select * from movies

[Paso1-5a](/Paso1/1-5(a).jpg "" )

**codigo:**

 select first_name, last_name, rating 
    from actors

[Paso1-5b](/Paso1/1-5(b).jpg "" ) 

[Paso1-6](/Paso1/1-6.jpg "" )

**codigo:**
 select title from series

  # **Paso 2**
  [Paso2-1](/Paso2/2-1.jpg "" )
  
  **codigo:**

  select first_name, last_name, rating 
    from actors 
    where rating > 7.5

  [Paso2-2](/Paso2/2-2.jpg "" )
  
  **codigo:**

  select title, rating, awards, rating 
    from movies 
    where rating > 7.5


  [Paso2-3](/Paso2/2-3.jpg "" )
  
  **codigo:**

   select title , rating  from movies 
    order by title 

  # **Paso 3**

   [Paso3-1](/Paso3/3-1.jpg "" )
  
  **codigo:**

  select title 
    from movies 
    limit 3

  

   [Paso3-2](/Paso3/3-2.jpg "" )
  
  **codigo:**

   select * 
    from movies 
    order by rating desc 
    limit 5

   [Paso3-3](/Paso3/3-3.jpg "" )
  
  **codigo:**

   select * from movies
    order by rating desc
    limi 10
    offset 5 

   [Paso3-4](/Paso3/3-4.jpg "" )
  
  **codigo:**

  select * 
    from actors 
    limit 10

   [Paso3-4a](/Paso3/3-4a.jpg "" )
  
  **codigo:**

  select *
    from actors
    limit 10
    offset 3

  # **Paso 4**

   [Paso4-1](/Paso4/4-1.jpg "" )
  
  **codigo:**

  select title , rating
    from movies 
    where title 
    like '%Harry Potter%'

   [Paso4-2](/Paso4/4-2.jpg "" )
  
  **codigo:**

   select *
    from actors
    where first_name 
    like '%Sam'

   [Paso4-3](/Paso4/4-3.jpg "" )
  
  **codigo:**

  select *
    from movies
    where release_date 
    between "2004-1-1" and "2008-1-1"
