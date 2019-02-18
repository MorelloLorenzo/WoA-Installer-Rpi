# WoA Installer per Raspberry Pi 3

L'applicazione per installare Windows 10 Full nel tuo Raspberry Pi!

![image](https://user-images.githubusercontent.com/3109851/43066047-e7134552-8e63-11e8-8ac7-895e601b60e3.png)

# **Super semplice da usare. No-problemi.**

Per piacere leggi attentamente. Tutto quello di cui hai bisogno è scritto qui.

# Requisiti per WOA
- Raspberry Pi 3 Model B (or B+)
- MicroSD card. Raccomandata con rateo A1.
- A Windows 10 ARM64 Image (.wim). Per piacere, vai qui [this link](https://github.com/WOA-Project/guides/blob/master/GettingWOA.md) per scaricarlo.

## Requisiti per eseguire l'applicazione
- Una versione recente di Windows 10 (per piacere, assicurati di utilizzare l'ultima versione, altrimenti non aprire problemi).
.NET Framework 4.6.1 (dovrebbe essere incluso nella recente versione di Windows 10)

# Informazioni Core Packages
Per piacere, si fa notare che l'installer WoA è solo un tool che ti aiuta nello sviluppo. WoA Installer ha bisogno di alcuni file binaries, AKA i **Core Package**, per fare il suo lavoro. **questi binaries non sono miei** sono in bundle e offerti solo per convenienza per renderti la vita più semplice, infatti questo tool è orientato alla semplicità. 

Li trovate qui sotto.

# Downloads

## 1. WoA Installer

Scarica l'ultima versione **[ultima versione](https://github.com/SuperJMN/WoA-Installer/releases/download/v1.2/WoA.Installer.for.Raspberry.Pi.zip)** 

## 2. Core Package

Scaricalo da **[qui](https://1drv.ms/f/s!AtXoQFW327DIyMxxCDU_uUM6o6dn2A)**.

## 3. Installare i Core Package
Avvia l'installer di WoA e vai sulla sezione **Advanced**. Clicca su `[Import Core Package]` e seleziona direttamente il pacchetto. Non decomprimeteli (Non eseguire l'unzip). Dopo quest'importante operazione, sarai in grado di distribuire Windows.

# Le donazioni sono ben accette!

Se lo trovi utile, sentiti utile di [offrirmi un caffè ☕](http://paypal.me/superjmn). Grazie in anticipo!!

## Donate ai contributori del progetto
Per piacere, non dimenticatevi the il progetto WOA per Raspberry Pi è supportato da utenti privati e aziende (guarda la [sezione dei crediti e riconoscimenti](#credits-and-acknowledgements
)).
 - Dona a [MCCI](https://mcci.com/). Perchè? [Leggi questo 🗒](Docs/mcci_donate.md) 

# Bisogno di aiuto?
Allora visita il sito riguardo i nostri progetti a https://pi64.win, per una soluzione one-stop per tutte le tue domande 😊

Ti raccomandiamo anche di rellegere le [FAQ 📘](https://pi64.win/)

# Crediti e Riconoscimenti

WoA Installer è possibile grazie alla bella community dietro ad esso. Vorrei ringraziare le brillanti menti dietro questa meraviglia tecnica. Se pensi di essere aggiunto alla lista, per piacere, contattami usando l'indirizzo email he trovi nel mio profilo.

- [Andrei Warkentin](https://github.com/andreiw) per il **64-bit Pi UEFI**, UEFI Pi (HDMI, USB, SD/MMC) drivers, miglioramento ATF e  supporto Windows boot/runtime.
- [MCCI](https://mcci.com/) per il loro ottimo contributo per il RaspberryPI WoA Project:
  - per aver portato il loro **TrueTask USB stack** in Windows 10 ARM64, e concesso un uso non commerciale a questo progetto. ([guarda la licenza](Docs/mcci_license.md))
  - per aver finanziato il sito del progetto http://pi64.win e anche il sito del discorso http://discourse.pi64.win
  - Un ringraziamento speciale a Terry Moore per tutto l'ottimo supporto e consilenza, e per aver configurato la presenza online del progetto e la sua infrastruttura.
- Ard Bisheuvel per l' ATF iniziale e le porte UEFI
- [Googulator](https://github.com/Googulator) per il suo metodo per installare WoA nel RaspberryPI
- Mario Bălănică per il suo [fantastico tool](https://www.worproject.ml), e per i consigli e supporto :)
	- daveb77
    - thchi12
    - falkor2k15
    - driver1998
    - XperfectTR
    - woachk
    - novaspirit
    - zlockard 
     
    ...un grazie per aver testato tutti gli ACPI/driver e per le procedure di installazione.
- Microsoft per il 32-bit IoT firmware.

In oltre un grazie anche a:

- [Eric Zimmerman](https://github.com/EricZimmerman) per aver [Registrato il progetto](https://github.com/EricZimmerman/Registry)
- [Jan Karger](https://github.com/punker76) [MahApps.Metro](https://mahapps.com)
- [ReactiveUI](https://reactiveui.net)
- [Adam Hathcock](https://github.com/adamhathcock) for [SharpCompress](https://github.com/adamhathcock/sharpcompress)

E il nostro bellissimo gruppo su Telegram per i loro test e il supporto!
- [RaspberryPiWOA](https://t.me/raspberrypiwoa)

## Progetti Relativi
Questi sono altri progetti relativi al Raspberry. I Core Packages vengono da loro. Un Grande grazie!

- [RaspberryPiPkg](https://github.com/andreiw/RaspberryPiPkg)
- [Microsoft IoT-BSP](https://github.com/ms-iot/bsp)
- [Raspberry Pi ATF](https://github.com/andreiw/raspberry-pi3-atf)
- [WOR Project](https://www.worproject.ml) da [Mario Bălănică](https://github.com/mariobalanica)
