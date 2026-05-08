# Astro Tailwind Starter til at lave fede og flotte websites

Clone github repo'et i VSCode eller lav et nyt repo på basis af templaten, og klon derfra

Åbn terminalen og kør:

```sh
npm install
```

Så er du klar til at bruge løs af:
[Astro](https://astro.build/)
[Tailwind](https://tailwindcss.com/)
[Alpine.js](https://alpinejs.dev/)
[Motion One](https://motion.dev/)

Og følgende Tailwind plugins og godbidder:
[Tailwind Typography](https://github.com/tailwindlabs/tailwindcss-typography)
[Tailwind Forms](https://github.com/tailwindlabs/tailwindcss-forms)
[Tailwind Animated](https://www.tailwindcss-animated.com/)
[Tailwind Intersect](https://github.com/heidkaemper/tailwindcss-intersect)
[Hero icons](https://heroicons.com/)
[Hero patterns](https://heropatterns.com/)

Og du kan altid installere flere stumper, hvis du får brug for det:-)

## 🚀 Hav det sjovt

Vi aftaler at kode med disse regler:

Branches navngives således: feature*start (hero_start) når man starter med at kode noget og feature*ændringer (hero_ændringer) når man retter i det. Når man committer, skriver man så feature_done (hero_done).

Når man bruger heading komponenter er default værdierne: h3, medium, dark600 & heading - så når disse værdier skal bruges defineres de ikke.

Når man bruger text komponenter er default værdierne: brødtekst, paragraph & dark900 - så når disse værdier skal bruges defineres de ikke.

I text og heading komponenterne bruges stylingclasses="" som udgangspunkt ikke - kun hvis der lige er brug for det enkelte steder.

Kodestumper der ikke bruges skal slettes.

Vi laver kun komponenter af ting der genbruges.

Tilføj start og slut kommentarer på sektioner - så koden er let at overskue.

Der skal laves indrykninger, så man kan se parent-child-sibling forholdet, så koden er overskuelig.

Layout:

Vi arbejder som udgangspunkt med et grid der defineres i <main>:
Mobil: 6 kolonner, gap/gutter 10 px = tailwind size-2.5. 
Desktop: 12 kolonner, gap/gutter 20 px = tailwind size-5.

Margin defineres også i <main>: 
Mobil: 20px = tailwind size-5. Desktop: 40px = tailwind size-10

Afstande/spacings er defineret i en variabel: "my-section-desktop" & "my-section-mobil": 80px & 40px (Svarer til 20 & 10 tailwind size). Vores spacing variabel er defineret i tailwind.css.

Vi bruger ikke arbitrære værdier (Værdier i firkantede parenteser)

Ingen inline styles

Vi koder med tailwind og Daisy UI

JS placeres nederst på siden (udenfor MainLayout) eller i komponenten (medmindre det er alpinejs).

Når vi er færdige med at kode tested der med: Wave test & lighthousetest.
