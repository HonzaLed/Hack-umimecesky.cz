# Hack-umimecesky.cz
Crack na rozhodovačky na webu umímečesky.cz

# ----------Update log----------
----------Verze 2.3----------

Kód 1:javascript:var a = setInterval(function(){$(".option"+questions[questionOffset].options[1].correct).trigger("click")}, 2000)
Kód 2:javascript:clearInterval(a);

Popis:
Když spustíte(respektive když kliknete na) kód 1, script udělá to, že každé 2 sekundy klikne na správnou odpověď
Když spustíte(respekive když kliknete na) kód 2, klikání se zastaví


----------Verze 2.1----------

Kód:javascript: $(".option"+questions[questionOffset].options[1].correct).trigger("click")


Popis:
Když spustíte(respektive kliknete na) kód, script klikne jednou na správnou odpověď(Stejná funkce jako verze 2.0 ale kód je kratší a nenačítá scripty v webovek třetích stran)


----------Verze 2.0----------

Kód:javascript:var s = document.createElement('script');s.type='text/javascript';document.body.appendChild(s);s.src='https://honzaled.github.io/hackumimecesky.js ';void(0);

Popis:
Když spustíte(respektive kliknete na) kód, script klikne jednou na správnou odpověď


----------Verze 1.0----------

Kód:javascript:alert("Správná možnost je možnost číslo "+questions[questionOffset].options[1].correct)

Popis:
Když spustíte(respektive kliknete na) kód, zobrazí se zpráva jaká možnost je dobře
