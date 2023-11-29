# Verziókezelés

## Helyi repo létrehozása

- inicializálás:
    >git init
- git felhasználó ellenőrzése:
    >git config user.name

    >git config user.email
- ellenőrzés(van-e különbség a munkakönyvtár és a helyi repo közt?):
    >git status
- előkészítjük a commit-ra (minden változást eltárolunk):
    >git add .
- ellenőrzés:
    >git status
- commit:
    >git commit -m "first commit"

## Összekapcsolás a távoli repoval (GitHub)

- új GitHub repo létrehozása:
    >git remote add origin git remote add origin https://token@github.com/TheRedOwl/Tours.git
    >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
- első push-nál meg kell mondani a branch nevét:
    >git push -u origin master