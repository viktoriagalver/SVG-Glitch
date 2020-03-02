# SVG-Glitch

## Aufgabe
Wir bekamen die Aufgabe SVGs zu glitchen, indem wir gezielt den Code verändern, um so den Aufbau der SVGs besser zu verstehen.

## Mein SVG Glitch
Ich habe mir zunächst die Openmojis der HfG in Farbe heruntergeladen (https://openmoji.org) und sie mir durchgeschaut, um ein geeignetes SVG zum Glitchen zu finden. Ich habe mich dann für die Fledermaus entschieden. Zunächst habe ich ein bisschen ausprobiert und zufällig Zahlen verändert, um herauszufinden wie das Ganze aufgebaut ist. Nachdem ich mich einigermaßen zurechtgefunden habe habe ich nocheinmal von vorne begonnen. Ich habe mir überlegt die Fledermaus 3D mäßig wirken zu lassen, also in Rot iund Blau und Bewegung einzufügen. 

Zunächst habe ich die Pfäde einiger Flächen der Fledermaus kopiert und nocheinmal eingefügt, jedoch die Zahlen so verändert, dass sie leicht versetzt zu den ursprünglichen Pfäden sind. 
Die Flächen habe ich dann in Rot und Blau eingefärbt um so den 3D-Effekt zu erzielen. Eine Fläche habe ich schwarz gelassen, um soetwas wie einen Schatten zu erschaffen.
Dann habe ich mir überlegt Schrift einzufügen. Also verwendete ich den h1-Tag und setzte so den "SVG Glitch" Schriftzug unter meine Fledermaus. Als Schriftart wählte ich "courier new", da ich sie passend zu dem Thema Glitch fand. Ich habe mir überlegt wie auch bei der Fledermaus die Schrift mit einem 3D-Effekt darzustellen, also fügte ich den Schriftzug erneut ein und färbte einen rot und den anderen blau. Nach langem rumprobieren gelang es mir jedoch nicht die Schriften übereinander zu setzen, also ließ ich es so stehe, da mir das auch so ziemlich gut gefallen hat.
Zum Schluss wollte ich noch Bewegung einfügen. Ich recherchierte also im Interner und habe den animate-Tag gefunden. Ich habe ihn dann zunächst so eingesetzt:
  
*animateTransform attributeName="transform" <br>
type="translate" <br>
from="-520 20" <br>
to="520 20" <br>
begin="0s" <br>
dur="5s" <br>
repeatCount="indefinite"*

So bewegte sich meine Fledermaus einfach von links nach rechts. So wollte ich meinen Glitch lassen und abgeben, jedoch habe ich dann ein bisschen an dem Tag rumprobiert und die "duration" von 5s auf 0,01s verändert, sodass die Fledermaus anfing zu "glitchen".
