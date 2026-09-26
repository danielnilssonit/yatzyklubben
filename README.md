# Yatzyklubben

Klassisk skandinavisk yatzy med riktiga 3D-tärningar, för surfplatta, mobil och dator. Tärningarna skakas i en
läderbägare och rullar ut på en filtbricka. Sparade tärningar hoppar ner på hyllan närmast dig, och poängen skrivs i
ett protokoll av papper.

**Spela:** https://danielnilssonit.github.io/yatzyklubben/

- **Själv**, **mot datorn** (lätt, medel eller svår) eller **flera vid samma skärm**.
- **Online:** tryck på *Spela online*, skapa ett bord och dela länken eller QR-koden. Två till sex spelare, var och en i sin egen mobil eller platta.
- Skandinaviska regler (ett par, två par, liten stege 1–5, stor stege 2–6, bonus 50 vid 63). Husregler: tvångsyatzy och yatzy som kåk.
- Tips-knapp, lugnt tempo, större siffror och uppläsning för den som vill.
- På iPhone och iPad: *Dela → Lägg till på hemskärmen*, så startar spelet som en app.

Spelarna hittar varandra via öppna MQTT-servrar (inga konton, ingen egen server). Den som skapar bordet slår
tärningarna och räknar poängen. Namnen man väljer syns för andra i lobbyn.

3D-modellerna är gjorda i Blender och spelet använder Three.js. Den här mappen byggs automatiskt (tools/build-pages.mjs i projektet).
