# Naudojimasis terminalu:

E:\Marko\Mokslai\Vilnius Coding School kursai\testine-repozitorija - Absoliutus kelias; 
. - Terminalo direktorijų struktūroje reiškia esamą direktoriją;
.. - Nurodo vieną direktoriją aukščiau nuo esamos;
cd - (Change Directory) - Komanda, kuri nurodo esamos direktorijos pakeitimą;



echo "# testine-repozitorija" >> README.md - Sukuria failą pavadinimu README.md ir jame patalpina tekstą "# testine-repozitorija";

# Naujos repozitorijos sukūrimo naudojamos komandos:

git init - Inicijuoja repozitoriją;
git add . - Nurodo, kokius failus pridedame į repozitoriją;
git commit -m "first commit" - Commit žinutės priskyrimas;
git branch -M main - Atšakos (branch) nurodymas;
git remote add origin https://github.com/MGViolent/testine-repozitorija.git (repozitorijos//adresas) - Github repozitorijos susiejimas;
git push -u origin main - "Commit'o įkėlimo inicijavimas".

# Repozitorijos atnaujinimas:

git add .;
git commit -m "update message";
git push.