---
marp: true
theme: uncover
class: invert
---

# Synteza subtraktywna dźwięku 🎶

<span style="color: grey">Autor:</span> Gerald Serafin

---

### Voltage controlled oscilator (VCO) 🔊

###

Układ elektroniczny generujący okresowy sygnał elektryczny (falę) o częstotliwości proporcjonalnej do napięcia elektrycznego podanego na wejście.

##

<span style="color: #5dadec; font-weight: bold">
  Częstotliwośc fali wpływa na wysokość dźwięku. 
</span>

---

### Podstawowe fale

![height:5in](photos/waves.png)

---

## Control Voltage (CV) 🎛️

![bg left height:5in](photos/CV.png)

Zmiana konkretnego parametru poprzez zmianę przychodzącego z zewnątrz napięcia.

---

## VCA 🎹

Moduł bramkujący. Przepuszcza dźwięk tylko przy podanym napięciu. Umożliwia odtważanie dźwięku generowanego przez oscylator tylko wtedy gdy klawisz na klawiaturze jest wciśnięty.

---

![height:6in](photos/VCA.png)

---

## Envelope generator (ENV) 🎷

#### Generator obwiedni

Moduł który po wyzwoleniu sygnałem bramkującym, odwzorowuje następujące fazy dźwięku:

- Czas narastania (Attack)​
- Moment osiągnięcia największej wartości (Decay)​
- Czas trwania (Sustain)​
- Czas zanikania (Release)

---

![height:6in](photos/ENV.png)

---

## Filter (VCF) ✂️

Moduł pozwalający uciąć cześć częstotliwości z dźwięku. Do automatycznego otwierania oraz zamykania filtra wykorzystuje się generator obwiedni.​

---

![height:6in](photos/Filter.png)

---

## LFO 🌿

Oscylator generujący fale o niskiej częstotliwości. Wykorzystywany głownie do modulacji parametrów innych modułów.

---

![height:6in](photos/LFO.png)

---

## Podsumowując

Synteza subtraktywna bazuje na dynamicznym odejmowaniu harmonicznych.
