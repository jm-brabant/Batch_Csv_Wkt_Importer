# Batch_Csv_Wkt_Importer
Allow one to import as many csv files with wkt line geometry, with a single click, provided the files are of the same known type.
In this first version, the CRS is by default the CRS of the project, the first field is WKT geometry (and named "WKT"), and all the other fields are of integer type by default.
If there are characters in the features, the corresponding field is of string type.
The column separator by default is ";". You can change it by "," in lines 60 and 64 of batch_csv_wkt_importer.py
Developped as part of Q-Traf, a macroscopic traffic program working with QGis.
Feel free to modify the file "batch_csv_wkt_importer.py" to your convenance.
