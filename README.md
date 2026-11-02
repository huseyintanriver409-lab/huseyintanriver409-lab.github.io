# huseyintanriver409-lab.github.io

Kök alan adı için GitHub Pages sitesi. İki işi var:

- `.well-known/assetlinks.json`: Spor Defteri Android uygulamasının (TWA, paket `io.github.huseyintanriver409lab.spordefteri`) bu siteye ait olduğunu kanıtlar; böylece uygulama adres çubuğu olmadan tam ekran açılır. Parmak izi, uygulamayı imzalayan anahtarın SHA-256 değeridir. Anahtar değişirse burası da güncellenmeli.
- `index.html`: kök adrese geleni Spor Defteri'ne yönlendirir.

`.nojekyll`, GitHub Pages'in nokta ile başlayan `.well-known` klasörünü yayınlaması için gerekli.
