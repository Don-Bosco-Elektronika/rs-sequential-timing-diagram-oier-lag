# 🛠️ Cronograma de Circuitos Secuenciales / Zirkuitu Sekuentzialen Kronograma / Sequential Circuit Timing Diagram

| **Alumnos** | **Curso** | **Módulo** |
|-------------|-----------|------------|
| 2ME         | 1º        | EEM (Equipos Microprogramables) |



**Ariketa (EU): (ZENBAKIA IDATZI)**  
| Izena                     | Txip Zenbakia | Sinboloa         | Funtzionamendu Describapena                                                                |
|---------------------------|------------------|------------------|---------------------------------------------------------------------------------|
| RS | 4044          | <img width="99" height="76" alt="image" src="https://github.com/user-attachments/assets/ec4d5758-4966-4475-bfd1-8b30966aa5c8" />
 | Ez dauka erloju-sarrerarik (Clock). Set edo Reset aktibatzean, irteera momentuan aldatzen da, itxaron gabe.|  



---

## Tabla de la verdad

| Entrada A | Entrada B | Entrada C | Salida    | Salida |
|-----------|-----------|-----------|-----------|--------|
| 0         | 0         | 0         | ░0░       | ░0░    |
| 0         | 0         | 1         | ░1░       | ░1░    |
| 1         | 1         | 0         | ░1░       | ░1░    |
| 1         | 1         | 1         | ░0░       | ░0░    |

----

## 🔲 Circuitos a Simular / Simulatzeko Zirkuituak / Circuits to Simulate

*(<img width="566" height="518" alt="image" src="https://github.com/user-attachments/assets/525bab23-925c-4881-a1bc-4626ddceda4a" />
)*

---

## 🔲 Resultado del Cronograma / Kronogramaren Emaitza / Timing Diagram Result
(nire zenbakia 1 da,RS-ko 5 ariketak hauek dira, ordenean daude)

1-
*(<img width="586" height="342" alt="image" src="https://github.com/user-attachments/assets/6007a606-5634-4093-827c-d700d5d17423" />
)*
2-
<img width="574" height="367" alt="image" src="https://github.com/user-attachments/assets/b95fb557-077e-4b6d-b78c-9709c7dbb5f4" />
3-
<img width="572" height="339" alt="image" src="https://github.com/user-attachments/assets/e9a2a3e2-0e3c-42b5-88e4-bc91d7b5bbfe" />
4-
<img width="596" height="331" alt="image" src="https://github.com/user-attachments/assets/543bbd0b-1e14-4f73-a91d-d5350be9892a" />
5-
<img width="562" height="334" alt="image" src="https://github.com/user-attachments/assets/07704e2c-f614-492f-93d3-479e621f2716" />



---


## 🔲 Código del Cronograma / Kronogramaren Kodea / Timing Diagram Code
hemen ordenean berriro jarriko ditut kodigoak
1-

{signal: [
  {name: 'Set',   wave: 'hl.h.lhl.h...l..h'},
  {name: 'Reset', wave: 'l.h.l.h.lhlhl..h.'},
  {},
  {name: 'Q',     wave: '1.0x1.x0.x1x1..0x'},
  {name: '~Q',    wave: '0.1x0.x1.x0x0..1x'}
]}



2-

3-

4-

5-




## 📤 Entrega / Igo / Upload  

➡️ **Instrucciones:**  

- **ES:** Sube los siguientes archivos. Todos los archivos subidos han de tener tu nombre.  
  - Una foto del símbolo.  
  - El archivo en Proteus y una captura de imagen de cada circuito en Proteus.  
  - Capturas de cada resultado del Wavedrom (solo el gráfico).  
  - **ATENCIÓN:** El código del cronograma TIENE que ser código, no una imagen.

- **EU:** Igo hurrengo fitxategiak. Igotako fitxategi guztiek zure izena eduki behar dute.  
  - Sinboloaren argazki bat.  
  - Proteus fitxategia eta zirkuitu bakoitzaren irudia (captura) Proteusen.  
  - Wavedrom bakoitzaren emaitzaren kaptura (grafikoa bakarrik).  
  - **KONTUZ:** Kronogramaren kodea kodea izan behar da, ez irudi bat.

- **EN:** Upload the following files. All uploaded files must include your name.  
  - A photo of the symbol.  
  - The Proteus file and an image capture of each circuit in Proteus.  
  - Uno capture of each Wavedrom result (graph only).  
  - **ATTENTION:** The schedule code MUST be real code, not an image.



