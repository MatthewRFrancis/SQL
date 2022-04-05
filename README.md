# Matthew Francis's SQL Portfolio
# Welcome to my SQL Portfolio. This depository contains examples of SQL that I have written. It is by no means comprehensive.






# Inventory Database

CREATE TABLE Spare_Parts (id INTEGER PRIMARY KEY, Part_Code TEXT, Description TEXT, Quantity INTEGER, Bin_Location TEXT, Price INTEGER);

INSERT INTO Spare_Parts VALUES (1, "1001-D-21", "Umbrella Ring", 26, "A04-45A", 2);
INSERT INTO Spare_Parts VALUES (2, "2457-E-21", "Fabric Cover", 53, "A36-45A", 15);
INSERT INTO Spare_Parts VALUES (3, "100437865-R-22", "Right Arm",
2, "A45-63B", 8);
INSERT INTO Spare_Parts VALUES (4, "1849948589-G-20", "GROMIT", 7, "A22-08F", 2);
INSERT INTO Spare_Parts VALUES (5, "74884844889-T", "Chaise Lounge Ground Bumper", 400, "A09-22K", 1);
INSERT INTO Spare_Parts VALUES (6, "484448440-Y-22", "Rope Netting", 42, "A44-02B", 7);
INSERT INTO Spare_Parts VALUES (7, "4938059-3-21", "White Adjustable Leveler", 143, "B-42C", 1);
INSERT INTO Spare_Parts VALUES (8, "123587-6", "Leg Connector", 13, "AWALL15", 67);
INSERT INTO Spare_Parts VALUES (9, "4748389-12-22", "Firepit", 13, "A04-07D", 488);
