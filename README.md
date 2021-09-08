# (Titlu)
Boomerang with a twist (vocoder)

## (Instalare)
Se deschide fisierul Boomerang (fisierul boomerang si robot_pfft trebuie sa se afle in acelasi folder)

## (Utilizare)

1. Se apasa butonul de pe microfon pt a enabla intrarea micofonului. 
2. Dupa aceea activam toggle pentru a enabla inregistrarea informatiei in buffer.
3. Alegem tipul de intrarea pe care-l dorim.
4. Apasam space pentru a inregistra. Facem release la butonul space ca sa oprim inregistrarea.

Aplicatia foloseste un buffer loop care o sa tina minta informatia si unde vom adauga informatie noua. Are si un button clear care ne ajuta sa golim informatia din buffer.
Userul selecteaza ce voce (voce normala, voce robot) doreste sa inregistreze in buffer cu ajutorul selectorului din stanga.

Primul gain controleaza volumul vocoderului.
Al doilea gain controleaza volumul din interiorul bufferului.
Al treilea gain controleaza volumul vocii live din vocoder pentru a putea alege cum sa sune vocea utilizatorului. Alaturi avem un meter care ne poate ajuta sa controlam nivelul vocii.


## (Istoric)
Am ales sa fac un program in Max cunoscut ca un program boomerang, ce se bazeaza pe faptul ca userul are o inregistrare (un loop) si poate adauga informatie peste ea (daca alege) apasand un singur buton.
M am gandit ca e o aplicatie simpla si fun de facut.
Cu ajutorul unui vocoder reusim sa inseram un efect pe voce cand alegem sa facem lucrul acesta.




## (Link-uri)


# Dezvoltarea proiectului

Pentru început:

1. Creează-ți cont pe Github
2. Download și install [Github Desktop](https://desktop.github.com/)
3. Citește [acest ghid](https://charlesmartin.com.au/blog/2020/08/09/student-project-repository) și ține la îndemână [Markdown Cheat Sheet](https://www.markdownguide.org/cheat-sheet).

Apoi, procesul este următorul (inspirat de [aici](https://cs.anu.edu.au/courses/comp1720/deliverables/05-major-project/#submission-process)):

1. *fork* al acestui template către propriul tău cont de Github

![](assets/fork.gif)

_(dacă preferi cumva ca repo-ul să nu fie vizibil de către public, îl poți seta ca Private din Settings - "Change visibility". Atunci trebuie să mă adaugi drept colaborator, ca eu să am acces.)_

2. *clone* al repo-ului din Github Desktop pentru a-l downloada local

![](assets/clone.gif)

3. *commit* și *push* pe măsură ce lucrezi la proiect. Ultima versiune push-ată pe server înainte de deadline va conta pentru evaluare.

![](assets/commit.gif)

## Elemente obligatorii

1. Acest readme completat. Titlu, descriere, mod de utilizare, istoric, link-uri utile.

   Poți include și imagini și chiar [gif-uri animate](https://www.screentogif.com/), sau link-uri către materiale audio/video.
   
   Vezi [aici](https://charlesmartin.com.au/blog/2020/08/09/student-project-repository) mai multe sugestii.

2. [Declarația de originalitate](statement-of-originality.yml) completată. Tot ce nu este inclus acolo va fi considerat 100% contribuție proprie.

    *(formatul este adaptat de [aici](https://gitlab.cecs.anu.edu.au/comp1720/2018/comp1720-2018-major-project/-/blob/master/statement-of-originality.yml). Da, este un pic ironic să refolosim un doc [de altundeva](https://cs.anu.edu.au/courses/comp1720/resources/faq/#how-do-i-fill-out-my-statement-of-originality), dar menționăm sursa deci nu este plagiat!)*

3. Proiectul în sine. Tot codul trebuie să fie prezent, proiectul trebuie să poată rula conform instrucțiunilor din readme. Dacă e nevoie de asset-uri mari (sunete, video etc), [folosește Git LFS](https://git-lfs.github.com/) sau include link de download în instrucțiunile de instalare.

