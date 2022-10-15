# Quran_Full_Database_Word_By_Word
Quran Full Database Word By Word Translation. Multilingual translations and so on...

SQL Example For Simple DB:

SELECT * FROM `arabic_text` INNER JOIN  `TNamoone` ON 
`arabic_text`.`sura`=`TNamoone`.`ParentID` AND `arabic_text`.`aya`=`TNamoone`.`CategoryID`
INNER JOIN  `TNoor` ON 
`arabic_text`.`sura`=`TNoor`.`Nsure` AND `arabic_text`.`aya`=`TNoor`.`NAye`
