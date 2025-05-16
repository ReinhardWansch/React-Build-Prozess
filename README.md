# React-Build-Prozess
Created with CodeSandbox

## Notizen
Mit dem Setup von der Seite beginnen obwohl CRA (Create React App) depricated ist, weil es für den Artikel unwichtig. In dem Artikel geht es um das Verständnis der Schritte des Build Prozesses im einzelnen.

Was macht build als Ganzes gesehen?
Aus den Dateien in `public/` und `scr/` werden html-, css- und javascript-Dateien in `build/`.
Außerdem wird eine Datei namens `asset-manifest.json` erzeugt.

`browserslist` wird beim build in *package.json* eingefügt (wenn man mit ja bestätigt)

## Chronic
- `npm audit fix --force`