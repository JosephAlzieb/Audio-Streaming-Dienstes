*ich habe keine Primäer-Schlüssel hinzugefügt, da ich das nirgindwo richtig nötig fand. 
 aber in dem Relationen-Modell wird um Schlüssel gekümert. (Id's) 

*benutzername sollte meiner meinung nach Primärschlüssel sein, da es eindeutig sein soll 

*Ein Prämium-Nutzer ist auch ein Nutzer

*Ein Nutzer kann beliebig viele Titel kommentieren, und ein Titel kann von beliebig vielen kommentiert werden
 ('einmalig' könnte man in einer späteren Phase berücksichtigen)

*Ein Titel gehört zu einem bestimmten Genre => [1,1]

*Jedes Genre kann ein anderes Genre empfehlen => [0,1] (also ein Genre kann NUR EIN anderes Genre empfehlen)

*Dass man nur öffentliche Playlists bewerten kann, könnte man in einer späteren Phase machen.

*Jeder Titel hat genau zwei Speicherorte (Jeder Titel liegt in 2 Qualitäten vor) LQ & HQ ,
 und unter einem Speicherort können beliebig viele Titels gespeichert werden (in einem Ordner beliebig viele Dateien)

*jeder Nutzer hat genau eine Adresse, und unter einer Adresse können mehrere Nutzer wohnen (zb. zwei Brüder , ein Paar,..)

*jede Band kann eine Geschicht haben, und die Geschicht sollte einen Text haben
 Geschichte als Entität, um die 1. NF nicht zu verletzen.

