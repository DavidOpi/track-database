# track-database
track and field database for comp Sci

# Schema SQL

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

-----------------------------------------------------------------------------------

# Query SQL

