# EncJsonReader-heureka-code

Nutzt das Modul 
[```AESEncryptor-heureka-code```](https://github.com/heureka-code/AESEncryptor-heureka-code) 
um Json-Datein verschlüsselt zu speichern.

## Methoden der Klasse ```EncJsonReader```

___

### ```__init__```: 

Konstruktor für die Klasse.

file: str – der Pfad zu der Datei, in der die Informationen gespeichert werden sollen.<br>
passwort: str – das Passwort, mit dem die Informationen gesichert werden sollen.<br>
signatur: str – optional. Der Signatur Text.

___

### ```__del__```

Destruktor der Klasse der die änderungen speichert.

___

### ```read```

Liest die Datei ein, falls sie existiert. Wird automatisch im Konstruktor aufgerufen.

___

### ```write```

Schreibt die Änderungen verschlüsselt in die Datei.

___

### ```set_from_path```

Steuert die Json-Datei über einen Pfad an und setzt den passenden Wert.

path: str – der Pfad, der gesetzt werden soll.<br>
value – der Wert, der gesetzt werden soll

___

### ```get_from_path```

Liefert den Wert am gegebenen Pfad.

path: str – der Pfad, dessen Wert geliefert werden soll.

___

### ```delete_path```

Löscht den Wert eines Pfades.

path: str – der Pfad, dessen Wert gelöscht werden soll.

___

### ```path_exists```

Gibt zurück, ob ein Pfad existiert.

path: str – der Pfad, der geprüft werden soll.

___

### Property-Attribute

| Name      | Typ   | Beschreibung       |
| :-------- | :---: | :----------------- |
| file      | str   | Der Dateipfad      |
| passwort  | str   | Das Passwort       |
| signatur  | str   | Der Signatur Text  |
