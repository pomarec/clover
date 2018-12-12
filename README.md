Pas le meme dossier clover pour 10.12 et 10.13.4
AirportBrmcNIC KP => disable wifi card dans le bios
Cannot initialize graphics / gIOScreenLockState 3  => 0x12345678
0x12345678 permet de pas se prendre la tete avec la config de la cg pour l'instant
0x19260004 pour wam (pas oublier de reload le cache kext) en fait c 02 a la fin
cimer ggctseng qui m'a permis de sortir du KP AppleACPIPlatform grace a son dossier clover
les themes c juste des dossiers, yen a qui fonctionnent mieux que d'autre, moi j'aime minimal
SSDT et DDST ca semble compliqué j'y ai pas touché encore
tu t'en sors avec les kext et/ou les kext patch dans config.plist
je recommande de vider le dossier ACPI et de pas se prendre la tete avec pour l'instant, ca sert apres
FixHeaders_20000000 j'ai rien capté mais ca m'a pas aidé
syscl m'a bcp aidé pour 10.12 mais m'a fait galérer pour 10.13
acpi=off DropSSDT=Yes DSDT=Null m'ont un peu aidé
l'option -v est essentielle
j'ai pas vu d'incidence de MacBookPro13,1 ou MacBookAir6,3 c'est juste que la ca marche



Mon matos c'est
    XPS 9350  - 512Go SSD
    CPU : i7-6560U Skylake
    Graphics : Intel Iris 540HD / QHD+ screen (3200x1800)
    Wifi : DW1820A (BCM4350) 14e4:43a3
    Sound : Realtek ALC 3246

