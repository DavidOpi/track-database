-- Drop the table if it exists
DROP TABLE IF EXISTS "myTable";

-- Create the table
CREATE TABLE "myTable" (
  "place" SERIAL PRIMARY KEY,

  "name" VARCHAR(255) DEFAULT NULL,
  "country" VARCHAR(100) DEFAULT NULL,
  "wind" VARCHAR(255) DEFAULT NULL,
  "prelims" DECIMAL DEFAULT NULL
);

-- Insert data into the table
INSERT INTO "myTable" ("place", "name", "country", "wind", "prelims")
VALUES
('1', 'Talon Peterson', 'Chile', 'NWI', 10.55),
  ('2', 'Denton Gentry', 'Sweden', 'NWI', 10.58),
  ('3', 'Hayes Porter', 'Singapore', 'NWI', 10.63),
  ('4', 'Keelie Sparks', 'Belgium', 'NWI', 10.72),
  ('5', 'Ferdinand Shaffer', NULL, 'NWI', 10.85),
 ('6', 'Davido King', 'Russia', 'NWI', 10.92);
 
 CREATE TABLE "iTable" (
  "place" SERIAL PRIMARY KEY,

  "name" VARCHAR(255) DEFAULT NULL,
  "country" VARCHAR(100) DEFAULT NULL,
  "wind" VARCHAR(255) DEFAULT NULL,
  "prelims" DECIMAL DEFAULT NULL
);
-- Insert data into the table
INSERT INTO "iTable" ("place", "name", "country", "wind", "prelims")
VALUES

('1', 'Cristian Alvarado', 'Canada', 'NWI', 10.43),
  ('2', 'Daryl Hall', 'USA', 'NWI', 10.55),
  ('3', 'Jack Jool', 'USA', 'NWI', 10.58),
  ('4', 'Devonte Allen', 'Ghana', 'NWI', 10.67),
  ('5', 'Paul Lop', 'Japan', 'NWI', 10.72),
 ('6', 'Keri Hilson', 'Canada', 'NWI', 10.88);
 
 
 CREATE TABLE "lolTable" (
  "place" SERIAL PRIMARY KEY,

  "name" VARCHAR(255) DEFAULT NULL,
  "country" VARCHAR(100) DEFAULT NULL,
  "wind" VARCHAR(255) DEFAULT NULL,
  "prelims" DECIMAL DEFAULT NULL,
   "heat" VARCHAR (225) DEFAULT NULL
);
-- Insert data into the table
INSERT INTO "lolTable" ("place", "name", "country", "wind", "prelims", "heat")
VALUES


('1', 'Cristian Alvarado', 'Canada', 'NWI', 10.43, '2'),
  ('2', 'Daryl Hall', 'USA', 'NWI', 10.55, '2'),
  ('3', 'Jack Jool', 'USA', 'NWI', 10.58, '2'),
  ('4', 'Devonte Allen', 'Ghana', 'NWI', 10.67, '2'),
  ('5', 'Paul Lop', 'Japan', 'NWI', 10.72, '2'),
 ('6', 'Keri Hilson', 'Canada', 'NWI', 10.88, '2'),
 ('7', 'Talon Peterson', 'Chile', 'NWI', 10.55, '1'),
  ('8', 'Denton Gentry', 'Sweden', 'NWI', 10.58,'1'),
  ('9', 'Hayes Porter', 'Singapore', 'NWI', 10.63, '1'),
  ('10', 'Keelie Sparks', 'Belgium', 'NWI', 10.72, '1'),
  ('11', 'Ferdinand Shaffer', NULL, 'NWI', 10.85, '1'),
 ('12', 'Davido King', 'Russia', 'NWI', 10.92, '1');
 
 
 -- Create the table
CREATE TABLE "pTable" (
  "place" SERIAL PRIMARY KEY,

  "name" VARCHAR(255) DEFAULT NULL,
  "country" VARCHAR(100) DEFAULT NULL,
  "wind" VARCHAR(255) DEFAULT NULL,
  "finals" DECIMAL DEFAULT NULL
);
 
 -- Insert data into the table
INSERT INTO "pTable" ("place", "name", "country", "wind", "finals")
VALUES


('1', 'Cristian Alvarado', 'Canada', 'NWI', 10.38),
('2', 'Jack Jool', 'USA', 'NWI', 10.51),
  ('3', 'Daryl Hall', 'USA', 'NWI', 10.63),
  ('4', 'Devonte Allen', 'Ghana', 'NWI', 10.64);
  
  CREATE TABLE "lalaTable" (
  "place" SERIAL PRIMARY KEY,

  "name" VARCHAR(255) DEFAULT NULL,
  "country" VARCHAR(100) DEFAULT NULL,
  "wind" VARCHAR(255) DEFAULT NULL,
  "prelims" DECIMAL DEFAULT NULL
);

-- Insert data into the table
INSERT INTO "lalaTable" ("place", "name", "country", "wind", "prelims")
VALUES
('1', 'Taylor Talons', 'Japan', 'NWI', 11.07),
  ('2', 'Denice Dimes', 'Canada', 'NWI', 11.15),
  ('3', 'Fiona Finnn', 'Canada', 'NWI', 11.27),
  ('4', 'Jasmine Sparks', 'USA', 'NWI', 11.32),
  ('5', 'Haylie Hails', 'Jamaica', 'NWI', 11.36),
 ('6', 'Maya Lol', 'Japan', 'NWI', 11.48);
 
 
   CREATE TABLE "lopTable" (
  "place" SERIAL PRIMARY KEY,

  "name" VARCHAR(255) DEFAULT NULL,
  "country" VARCHAR(100) DEFAULT NULL,
  "wind" VARCHAR(255) DEFAULT NULL,
  "prelims" DECIMAL DEFAULT NULL
);

-- Insert data into the table
INSERT INTO "lopTable" ("place", "name", "country", "wind", "prelims")
VALUES
('1', 'Jolly Jolls', 'Jamaica', 'NWI', 11.03),
  ('2', 'Karla Kas', 'USA', 'NWI', 11.18),
  ('3', 'Olivia Blos', 'USA', 'NWI', 11.22),
  ('4', 'Cristina sall', 'Canada', 'NWI', 11.28),
  ('5', 'Sally Opsala', 'Canada', 'NWI', 11.36),
 ('6', 'Mya Miss', 'Japan', 'NWI', 11.46);


CREATE TABLE "finTable" (
  "place" SERIAL PRIMARY KEY,

  "name" VARCHAR(255) DEFAULT NULL,
  "country" VARCHAR(100) DEFAULT NULL,
  "wind" VARCHAR(255) DEFAULT NULL,
  "prelims" DECIMAL DEFAULT NULL,
   "heat" VARCHAR (225) DEFAULT NULL
);
-- Insert data into the table
INSERT INTO "finTable" ("place", "name", "country", "wind", "prelims", "heat")
VALUES


('2', 'Taylor Talons', 'Japan', 'NWI', 11.07, '1'),
  ('3', 'Denice Dimes', 'Canada', 'NWI', 11.15, '1'),
  ('6', 'Fiona Finnn', 'Canada', 'NWI', 11.27, '1'),
  ('8', 'Jasmine Sparks', 'USA', 'NWI', 11.32, '1'),
  ('9', 'Haylie Hails', 'Jamaica', 'NWI', 11.36, '1'),
 ('12', 'Maya Lol', 'Japan', 'NWI', 11.48, '1'),
 ('1', 'Jolly Jolls', 'Jamaica', 'NWI', 11.03, '2'),
  ('4', 'Karla Kas', 'USA', 'NWI', 11.18, '2'),
  ('5', 'Olivia Blos', 'USA', 'NWI', 11.22, '2'),
  ('7', 'Cristina sall', 'Canada', 'NWI', 11.28, '2'),
  ('10', 'Sally Opsala', 'Canada', 'NWI', 11.36, '2'),
 ('11', 'Mya Miss', 'Japan', 'NWI', 11.46, '2');
 
 
 CREATE TABLE "cTable" (
  "place" SERIAL PRIMARY KEY,

  "name" VARCHAR(255) DEFAULT NULL,
  "country" VARCHAR(100) DEFAULT NULL,
  "wind" VARCHAR(255) DEFAULT NULL,
  "finals" DECIMAL DEFAULT NULL
 
);
-- Insert data into the table
INSERT INTO "cTable" ("place", "name", "country", "wind", "finals")
VALUES


('1', 'Taylor Talons', 'Japan', 'NWI', 11.12),
  ('2', 'Denice Dimes', 'Canada', 'NWI', 11.17),
 ('3', 'Jolly Jolls', 'Jamaica', 'NWI', 11.21),
  ('4', 'Karla Kas', 'USA', 'NWI', 11.25);
 
## QUERY SQL


SELECT * FROM "myTable";
SELECT * FROM "iTable";


SELECT * FROM "lolTable"
ORDER BY prelims ASC;

SELECT * FROM "pTable";

SELECT * FROM "lalaTable";
SELECT * FROM "lopTable";

SELECT * FROM "finTable"
ORDER BY prelims ASC;

SELECT * FROM "cTable";
