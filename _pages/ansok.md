---
layout: page
title: Ansök
permalink: /ansok/
---

<!-- ### Om du studerar eller arbetar på Linköpings universitet kan du ansöka om medlemskap. Gör det redan idag! -->

<div id="countdown">
    <p style="font-size: 20px;">
        Vi antar snart nya medlemmar! Ansökningstiden går ut om:
        <span id="countdown-timer" style="font-weight: bold;">Timer placeholder</span>
    </p>
    <p>
        Du kan såklart söka medlemskap i LiTHe Blås när som helst under året, men efter ansökningstiden är det stor risk att det är fullt på just ditt instrument. Så passa på att ansöka nu!
    </p>
</div>

<script>
  document.addEventListener('DOMContentLoaded', function () {
    // Set the date we're counting down to
    var countDownDate = new Date('2024-09-11T23:59:59').getTime();

    // Define the countdown function
    function updateCountdown() {
      // Get today's date and time
      var now = new Date().getTime();

      // Find the distance between now and the count down date
      var distance = countDownDate - now;

      // Time calculations for days, hours, minutes and seconds
      var days = Math.floor(distance / (1000 * 60 * 60 * 24));
      var hours = Math.floor(
        (distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60),
      );
      var minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
      var seconds = Math.floor((distance % (1000 * 60)) / 1000);

      // Display the result in the element with id="countdown-timer"
      document.getElementById('countdown-timer').innerHTML =
        days + 'd ' + hours + 'h ' + minutes + 'm ' + seconds + 's ';

      // If the count down is finished, write some text
      if (distance < 0) {
        clearInterval(x);
        document.getElementById('countdown-timer').innerHTML = 'EXPIRED';
      }
    }

    // Run the countdown function once first
    updateCountdown();

    // Then set it to run every 1 second
    var x = setInterval(updateCountdown, 1000);
  });
</script>

## Vilka är LiTHe Blås egentligen?

Vi är en studentorkester med fart och fläng som uppträder på många evenemang både inom samt utanför studentlivet och varje söndagskväll träffas vi för att repa tillsammans på campus Valla. Dessutom arrangerar vi Luciafesten på Kårallen där vi har årets största uppträdande och ställer till med en fest som har vår alldeles unika spinn!

## Så gör du

Skriv ner din ansökan på ett lämpligt medium (ett papper är enkelt och bra, men kreativa varianter av ansökningar uppskattas också!) som du sedan rusar iväg och lämnar i brevlådan utanför Blåsrummet i Kårallen. Du kan såklart även skicka din ansökan med posten, men e-post är fel sätt. Vill du posta din ansökan hittar du vår adress längst ner på sidan.

I din ansökan skriver du ner allt som kan vara av intresse att veta om dig. Det kan till exempel vara lämpligt att skriva vad du heter, var du bor och vilket/vilka instrument du skulle kunna tänka dig att hantera i orkestern eller om du tänkt dig en karriär i baletten. Men även annat kan vara intressant. Tänk på att styrelsen brukar ha gräsligt tråkiga styrelsemöten, där en roande och välformulerad ansökan kan lysa upp som ett värmeljus en gråkall novemberdag.

Blåsrummet hittar du i källarvåningen i Kårallen, i korridoren som börjar strax bortom Baljanfiket. Vi delar rummet med Linköpings Studentspex, så det kan hända att dörren är tapetserad med annat än våra affischer. Under raster sitter det ofta någon blåsare där inne, och då är det bara att sticka in huvudet om man har något att fråga.

Har du några andra funderingar så tveka inte att kontakta oss (men ansökningar bör komma pappersledes).

Adress för att posta ansökan:<br>
LiTHe Blås<br>
Kårallen, Linköpings universitet<br>
581 83 Linköping<br>
Sverige
