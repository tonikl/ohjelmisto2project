SQL
--------------------------------------------------

DELETE FROM goal_reached;
DELETE FROM game;
DELETE FROM airport WHERE type="heliport";
DELETE FROM airport WHERE type="closed";
DELETE FROM airport WHERE type="small_airport";
DELETE FROM airport WHERE type="balloonport";
DELETE FROM airport WHERE type="seaplane_base";
DELETE FROM airport WHERE type="medium_airport";
