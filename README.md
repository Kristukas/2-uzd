# ***v0.5***

Programos versijoje atliktas spartos testavimas su std::vector, std::deque, std::list tipo konteineriais.

***Kompiuterio parametrai***

|      CPU      |      RAM      |      SSD      |
| ------------- | ------------- | ------------- |
|   i7 7700K 4.20Ghz   | Corsair Vengance 16Gb 3200Mhz    |  MP500 120GB M.2 SSD   |


# ***Naudojant std::list Studentai***

|               |     1000      |     10000     |     100000    |    1000000    |    10000000   |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
|   Skaitymas   |   0.0056877   |   0.0539884   |    0.548987   |    5.67447    |    55.231     |
|  Rušiavimas   |   0.0001273   |   0.0013562   |    0.0154812  |    0.155869   |    1.58987    |



# ***Naudojant std::deque Studentai***

|               |     1000      |     10000     |     100000    |    1000000    |    10000000   |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
|   Skaitymas   |   0.0057067   |   0.0638156   |    0.580284   |    5.59991    |    57.4952    |
|  Rušiavimas   |   0.0003898   |   0.0034929   |    0.0386168  |    0.364254   |    3.78832    |




# ***Naudojant std::vector Studentai***

|               |     1000      |     10000     |     100000    |    1000000    |    10000000   |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
|   Skaitymas   |   0.0081365   |   0.0697041   |    0.585953   |    5.6079     |    56.0802    |
|  Rušiavimas   |   0.0001577   |   0.0020361   |    0.0168702  |    0.179203   |    1.90676    |

Testavimas kiekvienam konteineriui atliktas su tais pačiais 5 skirtingo dydžio failais.

Rezultate matome, kad naudojant std::deque programos veikimo laikas pailgėja, tačiau naudojant std::list programos sparta padidėja ir veikimo laikas sumažėja. 

Nors naudojant std::list programos sparta padidėja, bet programos vygdymo metu reikalaujama daugiau RAM atminties.
