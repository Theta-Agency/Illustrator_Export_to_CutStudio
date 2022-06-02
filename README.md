# Illustrator_Export_to_CutStudio
This little script is for replacing the Extension provided by Roland since it is not more compatible with newer versions of Illustrator CC


## Examples for correct Path formatting

### export_to_cutstudio.jsx :
var batchfile = new File("D:/Theta-Agency/Entwicklung/CutStudio/start.bat");
exportFileToAi("D:/Theta-Agency/Entwicklung/CutStudio/temp.ai");

### start.bat:
cd "C:\Program Files (x86)\CutStudio"
start "" CutStudio.exe -import "D:\Theta-Agency\Entwicklung\CutStudio\temp.ai"




