# SQL
SQL Portfolio

CREATE TABLE Beach_Coverup_Shop (id INTEGER PRIMARY KEY, name TEXT, color TEXT, quantity INTEGER, price_$ INTEGER, COO TEXT); 

INSERT INTO Beach_Coverup_Shop VALUES (1, "StarFish", "LightBlues", 20, 85.00, "Turkey");
INSERT INTO Beach_Coverup_Shop VALUES (2, "Stars", "Gold", 20, 85.00, "Italy");
INSERT INTO Beach_Coverup_Shop VALUES (3, "Waves", "BlueSilver", 10, 90.00, "China");
INSERT INTO Beach_Coverup_Shop VALUES (4, "Dolphins", "LightBlues", 10, 85.00, "Turkey");
INSERT INTO Beach_Coverup_Shop VALUES (5, "Flowers", "Pinks", 20, 85.00, "Italy");
INSERT INTO Beach_Coverup_Shop VALUES (6, "Tulips", "Multi", 10, 85.00, "China");
INSERT INTO Beach_Coverup_Shop VALUES (7, "Kisses", "Reds", 20, 90.00, "Turkey");
INSERT INTO Beach_Coverup_Shop VALUES (8, "LadyBugs", "MultiReds", 10, 85.00, "China");
INSERT INTO Beach_Coverup_Shop VALUES (9, "Birds", "MultiBlues", 30, 95.00, "China");
INSERT INTO Beach_Coverup_Shop VALUES (10, "Lines", "Multi", 10, 85.00, "Italy");
INSERT INTO Beach_Coverup_Shop VALUES (11, "Rainbows", "Multi", 20, 95.00, "Turkey");
INSERT INTO Beach_Coverup_Shop VALUES (12, "Smiles", "MultiYellows", 15, 85.00, "China");
INSERT INTO Beach_Coverup_Shop VALUES (13, "Friuts", "Multi", 20, 95.00, "China");
INSERT INTO Beach_Coverup_Shop VALUES (14, "Flags", "Multi", 20, 85.00, "Brazil");
INSERT INTO Beach_Coverup_Shop VALUES (15, "Bikes", "Multi", 10, 75.00, "China");
INSERT INTO Beach_Coverup_Shop VALUES (16, "Cats", "Multi", 10, 85.00, "China");

SELECT COO FROM Beach_Coverup_Shop;
SELECT * FROM Beach_Coverup_Shop;
SELECT SUM (quantity) FROM Beach_Coverup_Shop;
SELECT MAX (quantity) FROM Beach_Coverup_Shop;
SELECT * FROM Beach_Coverup_Shop ORDER BY price_$;
SELECT * FROM Beach_Coverup_Shop WHERE price_$ >= 90.00;
SELECT * FROM Beach_Coverup_Shop WHERE price_$ <= 75.00;
SELECT * FROM Beach_Coverup_Shop WHERE price_$ = 85.00;

