##### \# la rockete 1 : **Afficher tous les articles (title, publish_date);**





 SELECT title, publish_date 

 FROM Posts;



+---------------------------+--------------+

| title                     | publish\_date |

+---------------------------+--------------+

| Apprendre SQL             | 2025-05-10   |

| Bases de Données          | 2025-05-20   |

| Le futur du Web           | 2025-12-15   |

| Sécurité Informatique     | 2025-03-12   |

| Post de test 222          | 2025-04-10   |

| Autre post 222            | 2025-04-15   |

| Santé Mentale             | 2025-01-10   |

| Recette Pizza             | 2025-02-05   |

| Voyage à Bali             | 2025-02-20   |

| Python pour débutants     | 2025-06-15   |

| Entrainement Cardio       | 2025-07-22   |

| Intelligence Artificielle | 2025-12-25   |

| Actualité du Jour         | 2026-01-08   |

| Météo du 8 Janvier        | 2026-01-08   |

+---------------------------+--------------+

14 rows in set (0.00 sec)



##### \# la rockete 2 : **Afficher les users dont le nom commence par 'EL';**



 SELECT * 

 FROM users 

 WHERE user_name LIKE 'EL%';



**+---------+-------------+-------------------+------------+**

**| id\_user | user\_name   | email             | date\_birth |**

**+---------+-------------+-------------------+------------+**

**|       3 | EL Mansouri | mansouri@mail.com | 1988-02-20 |**

**|       4 | EL Idrissi  | idrissi@mail.com  | 1992-12-12 |**

**|       6 | EL Amrani   | amrani@mail.com   | 1985-08-30 |**

**+---------+-------------+-------------------+------------+**

**3 rows in set (0.00 sec)**